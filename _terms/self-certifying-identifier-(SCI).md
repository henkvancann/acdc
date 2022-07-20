---
layout: term
short-name: SCI
name:  Self-Certifying Identifier
categories: [ "KERI", "ACDC" ]
author: Henk van Cann
peer-review:
---

## Definition

A Self-Certifying Identifier cryptographically binds an identifier to a public and private key pair. It is an identifier that can be proven to be the one and only identifier tied to a public key using cryptography alone.

## Signing

A [controller](controller) issues an own Identifier by binding a generated public private key pair to an identifier. After this a controller is able to sign the identifier and create a certificate. Also called a _cryptonym_. The simplest form of a self-certifying identifier includes either the public key or a unique fingerprint of the public key as a [prefix](prefix) in the identifier.
