---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A detailed version of my CV can be found [here](https://vm2p.github.io/files/resume.pdf).

# Education

- Ph.D. in Computer Science, MAP-i Doctoral Program offered by Universidade do Minho, Universidade de Aveiro and Universidade do Porto, Portugal, 2020
- M.S. in Computer Science, Universidade do Minho, Portugal, 2015
- B.S. in Computer Science, Universidade da Beira Interior, Portugal, 2013

# Work experience

## Advanced Computer Scientist, SRI, Menlo Park, California

Menlo Park, CA, USA - *February 2021 - Ongoing*

My role at SRI involves participating in various US government-funded projects, as well as participating in different proposal efforts. My research directions focus on the intersection of theoretical cryptography and formal methods, particularly research based on computer-aided cryptography, with focus on the development of machine-checked implementations of cryptographic software via code synthesis from mechanically verified cryptographic proofs in EasyCrypt.

## Researcher, HASLab – INESC TEC & DCC FC Universidade do Porto

Porto, Portugal - *June 2020 - February 2021*

I was responsible for a collaboration project between INESC TEC and SRI International with the goal of formally verify a zero-knowledge proof protocol based on the MPC-in-the-Head (MitH) construction. This project was carried out under the Securing Information for Encrypted Verification and Evaluation (SIEVE) program funded by the Defense Advanced Research Projects Agency (DARPA).

## Researcher, HASLab – INESC TEC & DCC FC Universidade do Porto

Porto, Portugal - *July 2016 - April 2020*

Developed my Ph.D. thesis "*Integrated verification of cryptographic security proofs and implementations*", focusing on reducing the abstraction gap between cryptographic security proofs and real implementations.

## Intern, SRI International

Menlo Park, CA, United States - *September 2018 - December 2018*

The goal of this internship was the study and development of Multiparty Computation (MPC) techniques that could be applied to the particular case of Blockchain usage, and to provide formal proofs/implementation of the techniques explored.

Particularly, the work focused on the use of EasyCrypt to deliver formal proofs of proactive secret sharing and MPC primitives, as well developing a new EasyCrypt extraction tool that could be used to generate a verified implementations of such primitives.

## Intern, Instituto IMDEA Software

Madrid, Spain - *March 2016 - July 2016*

Finished the development of a security proof and a verified implementation in OCaml of a concrete instantiation of Yao’s Secure Function Evaluation protocol using EasyCrypt.

## Researcher, HASLab – INESC TEC & DI Universidade do Minho

Braga, Portugal - *January 2015 - March 2016*

Developed my master thesis "*A deductive verification platform for cryptographic software*". The project consisted in developing a deductive verification platform for the CAO language, using the EasyCrypt toolset as a backend for the tool.

Started the development of a security proof and a verified implementation in OCaml of a concrete instantiation of Yao’s Secure Function Evaluation protocol using EasyCrypt, in cooperation with the Cryptography team at IMDEA Software, Madrid.

## Junior Researcher, RELiablE And SEcure Computation Group, Universidade da Beira Interior

Covilhã, Portugal - *January 2013 - July 2013*

Developed my undergraduate project "*Cloud Security: Homomorphic Encryption Schemes*", funded by Portugal Telecom - Inovação, under the PRICE (Privacy and Security Issues in Cloud Environment) project.

# Skills

## Digital skills

- Software Formal Verification, including knowlege in COQ, Frama-C, Why3, F*, Model Checking and Abstract Interpretation
- Formal Verification of Cryptographic Primitives, including knowledge in EasyCrypt
- Analysis and Modeling of Software, including knowledge in Alloy
- Programming in Functional Languages, such as OCaml, Haskell, F* or F#
- Compilers Development, using OCaml
- Cryptography

# Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


# Talks

  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>


# Teaching

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
