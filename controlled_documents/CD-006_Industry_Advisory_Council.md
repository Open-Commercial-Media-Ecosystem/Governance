# CD-006 Industry Advisory Council

## Change History

| Version | Date       | Description                                                                         | Author          |
| ------- | ---------- | ----------------------------------------------------------------------------------- | --------------- |
| 0.3     | 2024-12-19 | Initial documentation                                                               |                 |
| 1.0     | 2025-02-17 | Moved voting rules to CD-008. Added Colony IAC acknowledgment. Updated terminology. | Andrew Woodruff |
| 1.1     | 2026-02-17 | Added CD-005 Revenue Splits to OCME IAC authority. Removed revenue percentages from Colony IAC authority. | Andrew Woodruff |
| 1.2     | 2026-02-18 | Added RFC 2119 keywords throughout for formal requirements language. | Andrew Woodruff |

The key words "MUST", "MUST NOT", "SHOULD", "SHOULD NOT", and "MAY" in this document are to be interpreted as described in [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119).

## 1. Overview

The Industry Advisory Council (IAC) is a collection of [actors](https://trustoverip.github.io/essiflab/glossary#actor) that represent persons of influence and industry leaders. Their objective is to advise, administer, and maintain the OCME Governance Framework.

This document defines the structure and operations of the OCME IAC — the ecosystem-wide governing body. Individual colonies establish their own Colony IACs as defined in their respective Colony Governance Extensions. Colony IACs operate under the authority of the OCME Governance Framework and MUST maintain compliance with the OCME Primary Document.

### 1.1 OCME IAC Authority

The OCME IAC governs the shared core of the ecosystem. This includes:

- DID types and the DID method specification
- Revenue splits and payment terms (CD-005) — requires supermajority voting per CD-008
- Member onboarding and profile management
- The payment engine and supported payment networks
- The Code of Conduct (CD-007)
- Information Trust Requirements (CD-003)
- The Media Registry

Changes to these areas require OCME IAC approval regardless of which Colony is affected.

### 1.2 Colony IAC Authority

Colony IACs independently govern domain-specific rules within their Colony Governance Extension. This includes:

- Supported media file types and format requirements
- Technical requirements for content distribution
- Content-specific standards and quality requirements
- Colony-specific license types

Colony IACs MAY create colony-specific Controlled Documents for these areas without OCME IAC approval, provided they do not conflict with the OCME Primary Document or OCME-level Controlled Documents.

## 2. IAC Responsibilities

IAC members are not limited to, but have the following responsibilities:

- The IAC SHALL review and handle any proposed Governance Framework updates, including any Controlled Document updates, in a timely manner.
- Be a positive steward of the OCME Ecosystem.

The IAC Chair is not limited to, but has the following responsibilities:

- The IAC Chair SHALL be responsible for organizing meetings and one or more communication channel(s), as well as checking quorum and administering votes as needed.

## 3. IAC Membership

After formation of the original IAC members, formalized no later than 2024-09-19, additional members MUST be voted in following the standard voting procedure. An updated list of members MUST be maintained by the IAC Chair. The IAC MUST have one Chair position.

### 3.1 Membership Limits

The OCME IAC SHALL have a maximum of 11 members. The Executive Director is allocated one of these seats. OCME Board Members MUST NOT hold an IAC Member position.

### 3.2 Terms

IAC member terms last one year. There are no term limits — members MAY serve consecutive terms. Members MUST be voted in through the voting process defined in CD-008 Review and Amendment Procedures.

### 3.3 Removal

IAC members MAY be removed for violations of the Code of Conduct (CD-007).

## 4. Voting and Amendment Procedures

Voting rules, amendment procedures, and the governance change proposal process are defined in CD-008 Review and Amendment Procedures.

## 5. Colony IACs

Each Colony within the OCME Ecosystem establishes its own Colony IAC as the governing body for colony-specific decisions. Colony IACs:

- MUST maintain compliance with the OCME Primary Document.
- Are subject to OCME IAC compliance review.
- SHALL manage colony-specific Controlled Documents using the format CD-[ColonyTag]-###.
- SHALL follow the same voting rules defined in CD-008 Review and Amendment Procedures unless their Colony Governance Extension specifies otherwise with OCME IAC approval.
