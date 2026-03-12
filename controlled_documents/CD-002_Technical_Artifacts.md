# CD-002 Technical Artifacts

## Change History

| Version | Date       | Description                                                                                                             | Author          |
| ------- | ---------- | ----------------------------------------------------------------------------------------------------------------------- | --------------- |
| 0.2     | 2024-05-28 | Initial Documentation                                                                                                   |                 |
| 0.3     | 2025-11-20 | Removed credentials section. Added details to Identifiers and License Types.                                            |                 |
| 1.0     | 2026-02-11 | Updated DID method from TDW to WEBVH. Restructured identifier types. OCME as DID issuer. Cleaned up document structure. | Andrew Woodruff |
| 1.1     | 2026-02-17 | Designated all DID types as Core ecosystem types. Updated descriptions for colony neutrality.                           | Andrew Woodruff |

The following technical artifacts are governed and managed in this Governance Framework:

- **Identifier Types**: Decentralized Identifiers used within the OCME Ecosystem
- **License Types**: Different ways content is allowed to be used

## 1. Identifier Specifications

The OCME Ecosystem uses Decentralized Identifiers (DIDs) to ensure authenticity, traceability, and secure management of content, creators, and related artifacts.

### 1.1 DID Method

The OCME uses the `did:webvh` (Web + Verifiable History) method.

Specification reference: [did:webvh v1.0](https://identity.foundation/didwebvh/v1.0/)

The `did:webvh` method enhances the `did:web` approach by introducing cryptographic verification features including a self-certifying identifier (SCID), a verifiable chain of DID document updates, and optional witness approval mechanisms. Rather than relying on a blockchain ledger, `did:webvh` maintains a DID log — a ledger-like history file published via HTTPS — allowing resolvers to verify the complete lineage and integrity of a DID from its inception.

### 1.2 DID Issuer

The OCME is the only issuer of DIDs in the OCME Ecosystem.

### 1.3 Core DID Types

The following DID types are universal to the OCME Ecosystem. All colonies MUST support these types:

| DID Type | Description |
|----------|-------------|
| Creator | Identifies an individual or group that produces original work within the OCME Ecosystem. |
| Content | Identifies a specific piece of content uploaded to the Content Library. |
| Media | Identifies a specific media file associated with content. |
| Split Sheet | Identifies a split sheet listing all creators, their revenue share percentages, and payment addresses for a piece of content. |
| Playlist | Identifies a curated collection of content. |
| Member | Identifies a team member within an organization operating within the OCME Ecosystem. |
| Play Record | Identifies a content consumption event used as the basis for revenue calculation. |
| Payment | Identifies a payment transaction record. |
| Revenue Receipt | Identifies a revenue receipt documenting income distribution. |
| Governance | Identifies a governance configuration record. |

## 2. License Types

| Title | Version | Description |
|-------|---------|-------------|
| Streaming | 1.0 | This license gives a Broadcaster the right to stream the referenced content. |

