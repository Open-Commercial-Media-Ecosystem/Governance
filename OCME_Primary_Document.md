# Open Commercial Media Ecosystem Governance Framework
Version 0.3

## 1 Primary Document
This document is the Governance Framework for the Open Commercial Media Ecosystem.

### Authors
- Darrell O’Donnell, Continuum Loop Inc.
- Andrew Woodruff, OCME

### Contributors
- Tony Rose
- Laura Brugioni

### Revision History
- v.1 Voyager Program Launch May 1, 2024
- v.2 AI Music Video Channel Beta Launch Jun 1, 2024
- v.3 IAC added with rev split adjustment Dec 19, 2024

### Sign Offs

- v.1 Tony Rose, The AI Music Video Show, LLC, Apr 29, 2024
- v.2 Tony Rose The AI Music Video Show, LLC, May 28, 2024
- v.3 Tony Rose, The AI Music Video Show, LLC, Dec 19, 2024

### Terms of Use

This document intends to establish a Governance Framework and is a learning tool for the OCME Voyager Program. OCME is the Governing Authority of this Governance Framework (GF). These materials are made available under and are subject to the Creative Commons Attribution 4.0 International license [Creative Commons](http://creativecommons.org/licenses/by/4.0/legalcode).
THESE MATERIALS ARE PROVIDED “AS IS.” The Trust Over IP Foundation, established as the Joint Development Foundation Projects, LLC, Trust Over IP Foundation Series ("ToIP"), and its members and contributors (each of ToIP, its members and contributors, a "ToIP Party") expressly disclaim any warranties (express, implied, or otherwise), including implied warranties of merchantability, non-infringement, fitness for a particular purpose, or title, related to the materials. The entire risk as to implementing or otherwise using the materials is assumed by the implementer and user. 
IN NO EVENT WILL ANY ToIP PARTY BE LIABLE TO ANY OTHER PARTY FOR LOST PROFITS OR ANY FORM OF INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER FROM ANY CAUSES OF ACTION OF ANY KIND WITH RESPECT TO THESE MATERIALS, ANY DELIVERABLE OR THE ToIP GOVERNING AGREEMENT, WHETHER BASED ON BREACH OF CONTRACT, TORT (INCLUDING NEGLIGENCE), OR OTHERWISE, AND WHETHER OR NOT THE OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
This document is based on ToIP-Governance-Metamodel-Specification-V1.0. It has been modified to fit into the Trust Continuum™.

## 1.1 Introduction 
This governance framework (GF) provides a set of guidelines and principles for the governance of the Open Commercial Media Ecosystem (OCME) trust community. This GF outlines the roles and responsibilities of the governing authority and governed party, as well as the processes and procedures for managing the OCME ecosystem in a secure, transparent, and accountable manner.
This GF has been structured following the Trust Continuum methodology. It is partially based on the ToIP Foundation’s Governance Metamodel Specification. The ToIP Foundation and the ToIP stack play a critical role in advancing the field of decentralized identity, and this GF is designed to align with the foundation's principles and objectives.

## 1.2 Terminology and Notation 
The following conventions are used in this document:
- 1.2.1	Words and abbreviations that are in bold font have a specific meaning in this document and are defined in the Glossary.  All terms and patterns or mental models used in this document SHALL be defined in the Glossary, a controlled document of the governance framework (GF).  
- 1.2.2	The GF is written in plain language.  
- 1.2.3	The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and  "OPTIONAL" in this document are to be interpreted as described in RFC 2119

### ToIP Governance Requirements Glossary

| Term | Definition |
| --- | --- |
| requirement | In the context of a governance framework (GF), a requirement states a condition that an actor (human or machine) must meet in order to be in conformance. In ToIP-compliant GFs, all requirements MUST be expressed using RFC 2119 keywords. |
| mandatory | A requirement expressed using one of the following RFC 2119 keywords: "MUST," "MUST NOT," "REQUIRED," "SHALL," "SHALL NOT." |
| recommendation | A requirement expressed using one of the following RFC 2119 keywords: "SHOULD," "SHOULD NOT," "RECOMMENDED." |
| option | A requirement expressed using one of the following RFC 2119 keywords: "MAY", "OPTIONAL." |
| human-auditable requirement | A requirement expressed in a human language that can only be fulfilled by a human actor performing a set of processes and practices against which conformance can only be tested by an auditor of some kind. In a ToIP-compliant governance framework, human-auditable requirements are expressed as policies. |
| machine-testable requirement | A requirement written in a machine-readable format such that conformance of a software actor implementing the requirement can be tested by an automated test suite or rules engine. In a ToIP-compliant governance framework, machine-readable requirements are expressed as rules in a rules-based language. |
| policy | A human-auditable requirement that specifies some set of processes and practices that an actor must follow in order to be in conformance with the requirement. |
| process | A specified set of actions that an actor must take in order to be in conformance with a policy. A process may consist of a set of practices. |
| practice | A specified activity that an actor must perform as part of a process. |
| rule | A machine-testable requirement written in a machine-readable language that can be processed by a rules engine.|
| specification | A document or set of documents containing any combination of human-auditable requirements and machine-testable requirements needed to produce interoperability amongst implementers. Specifications may be included in (as controlled documents) or referenced from a governance framework. |

## 1.3 Localization 
The official language for this GF is currently English (IETF BCP 47 language tag “en”), and there are currently no translations. Should a translation be required, any person or entity MAY create the translations. Submissions should include the contact details of contributors and the trust community (if applicable) so that future updates can be translated. OCME MUST approve translations of this GF and ensure that translations are added to the official GF website.

## 1.4 Governing Authority
The Governing Authority for the Open Commercial Media Ecosystem Governance Framework (OCMEGF) is the OCME, specifically the governing board within the OCME.
The OCME governing board is the governing authority responsible for developing, maintaining and implementing this GF:
- Legal entity: The AI Music Video Show, LLC
- Entity Name: OCME Governing Board
- Jurisdiction: California, US
- DID: TBD
- OCME Governing Board: Tony Rose, Laura Brugioni, Darrell O’Donnell, Stephen Maloney
This GF MUST be available on the OCME website. The published GF MUST clearly state the version history and what has changed so the trust registry (TR) reflects the latest accurate version of the GF used within particular ecosystems.

## 1.5 Administering Authority
The administering authority will be the Industry Advisory Council. 
The administering authority is responsible for the administration of OCME in accordance with the GF. This includes:
- Managing the list of entities authorized to perform various Key Activities, including issuing credentials under this GF.
- Managing and Maintaining the OCME website and related applications.
The governing authority retains overall responsibility for the governance of OCME, including:
- Managing the identifier and credential types that are controlled under this GF.
- Managing the governed processes (Key Activities) that are controlled under this GF. 
- Making decisions to add/remove/suspend an entity where operating procedures aren’t clear.
The administering authority is authorized to make decisions related to their delegated administrative responsibilities, subject to oversight and approval by the governing authority. The administering authority will provide regular reports to the governing authority regarding their activities and consult with the governing authority on any issues or decisions that may impact the overall governance of the OCME trust community.
See Appendix F for more information.

## 1.6 Purpose 
This GF will establish the OCME Trust Ecosystem consisting of Creators, Curators, and Subscribers -  enabling content to be licensed by Creators for commercial use by Curators who create channels and build audiences of Subscribers. The GF is aimed at a closed-loop ecosystem, which will be opened up over time.

## 1.7 Scope
The scope of this GF is limited to a closed-loop pilot project focused on establishing the Minimum Viable Ecosystem (MVE) and building one subscription revenue-based 24x7x365 Music and Video channel (MusicVideoChannel.ai).    It demonstrates simple use cases guided by OCME to demonstrate to Creators, Curators, Subscribers, and other players in the OCME ecosystem how adding, consuming, and monetizing streaming content works in the OCME Trust Network.
This GF covers the following components:
- Content: Any type of media or material created for the purpose of entertainment, information, or communication. This includes videos, music, images, text, and other multimedia elements consumed by an audience. 
- Content Engine: The content engine is where the Creator adds content to the OCME. It is responsible for receiving the split-sheet data, and performing the Key Activities defined by this GF related to registering the split-sheet data, and content management.
- Channel: A curated set of content that a Subscriber consumes and pays for.  
- Channel Engine: The channel engine records when OCME content is played, as defined in the Key Activities.
- Subscription Engine: The subscription engine captures payment information from Subscribers and handles processing subscription payments into the Treasury, as well as other Key Activities related to Subscriber payment handling as defined in this GF.
- Clearing and Settlement Engine: The clearing and settlement engine is responsible for clearing: collecting all of the play records the channel engines have written, and settling: performing the Payment Function as defined in the Key Activities of this GF, determining the amount owed to each Creator for the period, and processing the payout to each Creator utilizing a smart-contract.

### 1.7.1 Key Roles
The following Key Roles will participate in this GF as Governed Roles:
- Content Creator: A human or group of humans who create content and split sheets and add them to the OCME.
- Content Submitter: An individual or entity that contributes content for inclusion in the OCME ecosystem, bearing legal liability for the provided material.
- Content Curator: A human or group of humans who curate content to create a streaming Channel experience and build a Subscriber audience. 
- Subscriber: Someone who pays a monthly subscription for access to Curated Content.
- Trustees: The humans responsible for making and/or ratifying governance decisions. In time, some aspects of the Trustee will be automated (e.g. in a DAO). 
- Treasury Custodian: A person or organization responsible for managing the collection and distribution of funds within the OCME ecosystem, ensuring that all transactions are conducted in accordance with established rules and regulations.
- Clearing: A human or service that calculates the appropriate payouts for Creators, Curators, and the OCME subsystems. This role is responsible for determining the correct amounts and addresses for payments of each party involved.
- Settling: Final processing and sending of all the money owed to each party in a settlement period.

### 1.7.2 Key Processes
The following processes will participate in this GF as Governed Processes:
- Curator Membership Administration: Covering Curator Applications, roles / responsibilities, and enforcement.  
- Sign Split Sheet:  Split sheets are legally binding documents that assign payments for Creators.
- Submit Content:  Content needs to be submitted for use in the OCME, including a signed split sheet.
- Initiate Subscription:  A Subscriber accepts terms and initiates subscription services to access channels.
- Receive Subscription Funds: The subscription engine receives funds from subscribers and directs them to the Treasury.
- Payout: The bulk payment that covers a particular time period “settlement period” and set of content plays in the OCME. 
- Clear Payout: Calculate how much each party in a payout is due and align those payments with the payee’s payment address.
- Settle Payments:  The process of sending funds to the parties of a Payout.
- Play Content: When content is played in a channel, the appropriate data must be stored reliably. This includes writing a Verifiable Play Record (see Appendix TK for technical detail) in the OCME ecosystem.

### 1.7.3 Out of Scope
The use of OCME credentials by anyone for any purpose other than in the OCME ecosystem.

## 1.8. Objectives 

This GF SHOULD achieve the following concrete outcomes:
- Allow members of the OCME ecosystem to understand the credential types that are controlled by this GF.
- Allow members of the OCME ecosystem to understand the identifier types that are controlled by this GF.
- Allow members of the OCME ecosystem to determine if an issuer is authorized to issue a particular identifier or credential type.
- Allow a closed-loop pilot that will help inform the future direction of this GF.

## 1.9 Principles 
- Encourage Creators
  - The GF should always keep the creators front of mind.
- Minimal Control
  - The GF should impose the least governance feasible.
- Leverage, Don’t Invent
  - Wherever possible, the OCME will leverage already-existing systems, which must align with the principles of the OCME GF. 
- Open By Default
  - The OCME ecosystem is intended to operate openly and will embrace an open-by-default posture. Information will be private only under exceptional circumstances.
- Open By Design
  - The OCME ecosystem should provide open design in its architecture, governance, and community approach.

## 1.10 Revisions 
This GF is subject to periodic revisions to ensure it remains up-to-date and effective in governing the OCME ecosystem.  The GF can change for the following reasons (non-exhaustive):
- Changes in laws or regulations
- Changes proposed by the existing community
- Changes proposed by potential new community members.
To facilitate transparent and collaborative revision management, revisions to this GF will be managed using suggestions on Google Docs. Suggestions on Google Docs provides a transparent and accountable platform for stakeholders to provide feedback and suggest revisions to the GF. Google Docs avoids the technical barrier presented by more advanced version control systems.
All revisions to the GF will be subject to the review and approval of the administering authority and governing authority. Initial review and approval of revisions will be done by the administering authority. The governing authority retains the final authority to approve, reject, or modify any suggested revisions to the GF upon administering authority approval. 

## 1.11 Extensions 
At this time, this GF is not allowing an extension. However, the governing authority intends to allow for extension in the future. When extension is allowed the GF will follow the general pattern for GF extension that Trust Over IP recommends. This approach will include:
- Specifying the requirements an extension GF must meet to be approved.
- Specifying the approval process by which a GF extension will get created.
- Defining requirements for registration, activation, and deactivation of an approved extension GF.
- Defining the requirements to notify trust community members about activating or deactivating an approved extension GF.

## 1.12 Schedule of Controlled Documents 
The following are the controlled documents:

| Document Title | Link | Description |
| --- | --- | --- |
| Glossary | Appendix A | Glossary of terms used by the OCME |
| Technical Artifacts | Appendix B | Sections include: Identifier Types, Licenses, Authorized Issuers, Split Sheets |
| Information Trust Requirements | Appendix C | Defines the requirements that all governed parties must meet.
| Growth and Evolution | Appendix D | As the OCME ecosystem grows and evolves beyond the closed-loop pilot there are some key principles and approaches being applied. |
| Revenue Splits | Appendix E | Initial Revenue Share splits |
| Industry Advisory Council | Appendix F | Defines the IAC structure and how it operates. |
