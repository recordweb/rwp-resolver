# RWP Resolver

> Status: Proof-of-Concept maturity. This component is designed as 
> reusable infrastructure for the RecordWeb ecosystem and is currently 
> being developed in the context of the "Fragestunde" PoC. It is 
> intended as a reference implementation, not a mandatory dependency.

## Purpose

The RWP Resolver resolves Decentralized Identifiers (DIDs) using the 
`did:rwp` method and returns the associated DID document, as defined 
in the RecordWeb Protocol (RWP) Technical Specification, Chapter 2.

The resolver is deliberately designed independently of any single 
PoC application. It manages one or more namespaces and can be used 
by any RWP-compliant system.

## Used by

- poc-fragestunde
- further PoCs to follow

## Related documents

- RecordWeb Protocol ([RWP](https://recordweb.github.io/rwp/)) Technical Specification, Chapter 2,
  (Record Identity / DID) and Chapter 12 (Federation)
- RecordWeb Concept ([RWC](https://recordweb.github.io/rwc/))

## Reference implementation

This repository is intended as a reference implementation. 
Organisations adopting RecordWeb in production are free to use this 
implementation, adapt it, or build their own resolver against the 
same DID specification.

## License

Licensed under the W3C Software and Document License 
(https://www.w3.org/copyright/software-license-2023/).
