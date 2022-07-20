---
layout: term
short-name: validator
name:  Validator
categories: [ "KERI", "ACDC" ]
date: 2022-07-15 12:00
author: Henk van Cann
peer-review:
---

## Definition
- Validator of any verifiable data structure
- Validator as a node in distributed consensus or participant
Validator and verifier are synonyms for our purposes.

A `validator` in [KERI](key-event-receipt-infrastructure-(KERI)) and [ACDC](authentic-chained-data-container-(ACDC)) is anybody that wants to establish control-authority over an identifier, created by the controller of the identifier. Validators verify the log, they apply duplicity detection or they leverage somebody else's duplicity detection or apply any other logic so they can say "Yes, these are events I can trust".

## Example

During validation of virtual credentials for example, a `verifier` checks to see if a `verifiable [credential](credential)` (VC) has been signed by the controller of this VC using the applicable verification method.