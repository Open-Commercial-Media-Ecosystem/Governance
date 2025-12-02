# Appendix B - Technical Artifacts

The following technical artifacts are governed and managed in this GF:

- Identifier Types
- Decentralized Identifiers 
- License Types
- Different ways the content is allowed to be used.
- Authorized Issuers
- Issuers who are authorized to issue specific credential types.

The DID URL for this Controlled Document is:

## Change History

|GF Version|Document Version|Date|Description of Change|
|---|---|---|---|
|0.2|0.2|May 28, 2024|Initial Documentation|
|0.3|0.3|November 20, 2024|Removed credentials section. Added details to Identifiers, and License Types.|

## Identifier Specifications

Specification references:

DID:tdw -  [https://identity.foundation/didwebvh/v1.0/](https://identity.foundation/didwebvh/v1.0/)

## Identifier Types

### Introduction

This document specifies the implementation of Decentralized Identifiers (DIDs) for media files using the DID:TDW method within the Open Commercial Media Ecosystem (OCME). The specification focuses on integrating DIDs into AIFF, MOV, MP4, and MP3 media files to ensure authenticity, traceability, and secure management. DIDs are also used for membership credentials.

### Objectives

- Authenticity and Traceability: Ensure each media file is uniquely identifiable and traceable back to its origin.
- Interoperability: Provide a standard that can be widely adopted across different platforms and services.
- Security: Use encrypted storage and DID technology to secure media files.
- Open Source: Allow the community to implement and improve upon the specification

### DID:TDW Method

The DID:TDW (Trusted Data Web) method is an evolution of the DID:WEB method, specifically designed for decentralized applications and services. It leverages the benefits of DID:WEB, providing a more flexible and robust mechanism for integrating DIDs into various types of media files.

### DID Structure

The general structure of a DID:TDW looks like this:
`did:tdw:{SCID}:ocmeregistry.com`

- did: The prefix indicating a decentralized identifier.
- tdw: The method used for this specific DID.
- SCID: A unique string generated for each media file.
- ocmeregistry.com: The domain representing the organization or community.

### Identifiers

The following identifier types are in use in the OCME:

- OCME Membership: 
- Split-sheet: A list of all Creators who created the content, the percentage of the royalties each Creator is paid for revenue derived from Commercial use of the content, and a payment address for each Creator for receipt of payment.
- Playlists:
- Channels:
- Licenses:

## B.3 License List

|Title|Version|Description|
|---|---|---|
|Streaming|1.0|This license gives a Curator the right to stream the referenced content.|

## B.4 Issuer List

- This needs to represent our identifiers instead of credential issuers.
