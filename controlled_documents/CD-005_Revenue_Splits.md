# CD-005 Revenue Splits and Payment Terms

## Change History

| Version | Date       | Description  | Author          |
| ------- | ---------- | ---------- | ------|
| 0.2     | 2024-05-28 | Initial documentation |                 |
| 0.3     | 2024-12-19 | Revenue split adjustment, payment terms added    |      |
| 1.0     | 2026-02-17 | Updated revenue splits to v1.0 terminology. Scoped to streaming license revenue. | Andrew Woodruff |

The key words "MUST", "MUST NOT", "SHOULD", "SHOULD NOT", and "MAY" in this document are to be interpreted as described in [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119).

## Amendment Protection

Amendments to this document require supermajority voting and Board approval as specified in CD-008 Section 4.2.

## 1. Streaming License Revenue Splits

Streaming license revenue MUST be allocated as follows:

- 60% to the Creator (distributed per the content's split sheet)
- 10% to the Showrunner
- 7.5% to the Broadcaster
- 17.5% to the Technology Provider
- 5% to the OCME Treasury for ecosystem operations

## 2. Payment Address Requirements

### 2.1 Payment Information Obligation

- All OCME members who contribute content to the catalog MUST provide a valid payment address compatible with OCME's supported payment networks (Section 3.1), or they will forfeit their right to payment for contributed content.

### 2.2 Payment Address Provision Timeline

- A payment address MAY be provided at any time.
- A payment address MAY be updated at any time.
- Members MUST provide payment information by the last day of the settlement period to prevent forfeiture.

### 2.3 Forfeiture of Payment Rights

- OCME members MUST verify the accuracy of the information that they provide, including address and network. Members MUST verify the network they are submitting is on the Supported Payment Networks list (Section 3.1).
- Members who do not provide payment information by the payment deadline SHALL forfeit their payment rights.
- Forfeited payments SHALL NOT be held in escrow or reserve by OCME.
- Forfeited payments SHALL return to the treasury for the next payment period.
- Forfeited payments SHALL be considered waived for that payment period.
- Members MAY become eligible for the next payment period by providing valid payment information.
- OCME SHALL NOT maintain individual member account balances or provide mechanisms for retrieving unclaimed payments from prior periods.

## 3. Payment Network Requirements

### 3.1 Supported Payment Networks

- OCME payments MUST be settled in USDC. The following networks that transact USDC are supported:
  - Base
  - Ethereum
  - Near
  - Polygon
  - Solana

### 3.2 Transaction Fee Responsibility

- Members are solely responsible for all transaction fees associated with their chosen payment network. This includes:
  - Blockchain network transaction fees
  - Smart contract execution fees (if applicable)
- OCME MUST NOT process transactions that result in the recipient receiving less than $0.

### 3.3 Network Management

- OCME MUST provide 30 days written notice of changes to the supported payment networks.
- OCME does not operate any blockchain network and is not responsible for network uptime, transaction speed, or transaction fees.

## 4. Payment Period

- OCME payments MUST be processed on a monthly basis.
