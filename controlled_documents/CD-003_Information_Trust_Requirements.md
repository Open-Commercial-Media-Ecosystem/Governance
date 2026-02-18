# CD-003 Information Trust Requirements

## Change History

| Version | Date       | Description                                                                                                                                                       | Author          |
| ------- | ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| 0.2     | 2024-05-28 | Initial documentation                                                                                                                                             |                 |
| 1.0     | 2025-02-11 | Structural cleanup. Content unchanged — specific requirements to be developed as ecosystem matures. Added role-specific MUST/SHOULD requirements to all sections. | Andrew Woodruff |

The following requirements apply to all [governed parties](https://trustoverip.github.io/toip/glossary#governed-party) within the OCME Ecosystem. The key words "MUST", "MUST NOT", "SHOULD", "SHOULD NOT", and "MAY" in this document are to be interpreted as described in [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119).

## 1. Information Security

Governed parties must ensure that the information they are responsible for is protected against unauthorized access, use, disclosure, modification, or destruction. This includes implementing appropriate technical, physical, and administrative safeguards to prevent security incidents and promptly responding to any security incidents.

1. All governed parties MUST implement security practices appropriate to their role in the OCME Ecosystem.
2. Technology Providers MUST protect DID signing keys and verification methods against unauthorized access or compromise.
3. Technology Providers MUST promptly respond to any security incidents affecting the Content Library, DID infrastructure, or payment systems, and MUST notify affected governed parties.
4. Creators MUST protect the credentials used to access their OCME accounts and MUST NOT share authentication credentials with unauthorized parties.
5. Curators MUST ensure that their streaming infrastructure does not introduce vulnerabilities that could compromise content integrity or creator data.

## 2. Information Availability

Governed parties must ensure that the information they are responsible for is available when needed by authorized users. This includes implementing appropriate backup and recovery procedures to minimize downtime in the event of an outage or disaster and monitoring system performance to identify and address issues that could impact availability proactively.

1. Technology Providers MUST maintain the availability of the Content Library, DID resolution services, and payment processing systems.
2. Technology Providers MUST implement backup and recovery procedures sufficient to prevent loss of DID documents, split sheets, and play records.
3. Technology Providers MUST maintain records to evidence the availability of their services.
4. Curators SHOULD maintain the availability of their streaming services to end users.

## 3. Information Processing Integrity

Governed parties must ensure that the information they are responsible for is accurate, complete, and valid. This includes implementing appropriate controls to prevent errors, omissions, or unauthorized modifications to information and ensuring that data is processed consistently and reliably.

1. Technology Providers MUST ensure that DID documents are accurate, verifiable, and reflect the complete history of updates as required by the `did:webvh` method.
2. Technology Providers MUST ensure that split sheet calculations and revenue distributions are computed accurately and consistently.
3. Technology Providers MUST ensure that play records accurately reflect streaming activity and are not subject to unauthorized modification.
4. Creators MUST ensure that the information provided during content registration — including metadata, split sheet allocations, and payment addresses — is accurate and complete.

## 4. Information Confidentiality

Governed parties must ensure that the information they are responsible for is kept confidential and only disclosed to authorized parties on a need-to-know basis. This includes implementing appropriate access controls to prevent unauthorized disclosure and monitoring access logs to detect and investigate suspicious activity.

1. All governed parties MUST keep payment addresses and financial data confidential and MUST NOT disclose them to unauthorized parties.
2. Technology Providers MUST implement access controls that restrict access to creator and curator account data to authorized personnel only.
3. Curators MUST NOT disclose creator personal information obtained through the OCME Ecosystem to third parties without the creator's consent.

## 5. Information Privacy

Governed parties must ensure that the information they are responsible for is handled per applicable laws and regulations related to privacy. This includes implementing appropriate privacy policies and procedures to govern the collection, use, disclosure, and disposal of personal information and ensuring that individuals are provided with clear and transparent information about how their personal information is being handled.

1. All governed parties MUST comply with applicable data protection and privacy legislation in their jurisdiction.
2. Technology Providers MUST clearly specify what personal data is collected, how it is processed, and how long it is retained.
3. Technology Providers MUST provide creators with the ability to access, correct, and request deletion of their personal data.
4. Creators SHOULD review the privacy policies of Technology Providers and Curators before participating in the OCME Ecosystem.
