---
title: "EVOCrypt: EasyCrypt Verified OCaml Cryptographic library"
collection: projects
permalink: /projects/evocrypt
---
EVOCrypt is a library that provides verified, high-assurance implementations of a series of cryptographic algorithms/protocols, including
- Commitment schemes
- MPC protocols
- Secret sharing schemes
- ZK protocols

All implementations have been first specified in EasyCrypt, where all security and functional correctness proofs have been formalized. OCaml code is then obtained via code synthesis using the [CoCoCrypt](https://github.com/SRI-CSL/cococrypt) toolchain. The properties proved in EasyCrypt are carried out to the final OCaml implementation, thus increasing the degree of assurance of our code.

Currently, EVOCrypt provides verified implementations for the following cryptographic primitives:
- Commitment schemes:
    - SHA3-based commitment scheme
- MPC protocols
    - BGW protocol, with unlimited party support
- Secret sharing schemes:
    - Shamir secret sharing, with unlimited party support
- ZK protocols:
    - MPC-in-the-Head, using BGW as the underlying MPC protocol
    - Line-Point Zero Knowledge (LPZK), assuming pre-computed correlated randomness

[EVOCrypt repository](https://github.com/SRI-CSL/evocrypt)