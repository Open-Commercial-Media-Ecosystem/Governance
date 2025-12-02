# Appendix A - Glossary

This GF includes a glossary that includes terms in the following three general categories:

- ToIP core terms that describe the common components of the ToIP model and MUST be used consistently across all ToIP deliverables and ToIP-compliant GFs. These terms are defined in the [ToIP Core Glossary](https://trustoverip.github.io/toip/glossary).
- ToIP governance terms are specialized terms used to describe ToIP governance concepts. They are defined in the [ToIP Governance Glossary](https://trustoverip.github.io/gswg/glossary).
- [Self-Sovereign Identity (SSI)](https://essif-lab.pages.grnet.gr/framework/docs/terms/self-sovereign-identity) terms as defined in the [eSSIF](https://trustoverip.github.io/essiflab/glossary) Glossary
- GF-specific terms are terms needed in the context of this GF.

The following list of terms from the [ToIP Core Glossary](https://trustoverip.github.io/toip/glossary) are used in this document:

| Term | Definition |
|------|------------|
| administering authority | The [party](https://essif-lab.github.io/framework/docs/essifLab-glossary#party) tasked with operating the management of a particular [governance framework](https://trustoverip.github.io/toip/glossary#governance-framework). The administering authority may or may not be the [governing authority](https://trustoverip.github.io/toip/glossary#governing-authority). For example, a government may be the governing authority for a governance framework administered by an NGO as the administering authority. |
| ecosystem | An Ecosystem is a set of at least two (autonomous) [parties](https://trustoverip.github.io/toip/glossary#party) (the members of the ecosystem) whose individual work complements that of other members, and is of benefit to the set as a whole. |
| governing authority | The [party](https://essif-lab.github.io/framework/docs/essifLab-glossary#party) responsible for governing a particular [governance framework](https://trustoverip.github.io/toip/glossary#governance-framework). The governing authority may or may not be the [administering authority](https://trustoverip.github.io/toip/glossary#administering-authority). For example, a government may be the governing authority for a governance framework administered by an NGO as the administering authority. |
| governed party | A [party](https://trustoverip.github.io/toip/glossary#party) whose [actors](https://trustoverip.github.io/toip/glossary#actor) perform in a [role] defined by a [governance framework](https://trustoverip.github.io/toip/glossary#governance-framework). |
| governance framework | A set of business, legal, and technical [definitions], [policies], [specifications], and contracts by which the members of a [trust community](https://trustoverip.github.io/gswg/glossary#trust-community) agree to be governed in order to achieve their desired [objectives](https://trustoverip.github.io/essiflab/glossary#objective). ToIP-compliant governance frameworks follow the [ToIP governance metamodel](https://github.com/trustoverip/gswg/wiki/toip-governance-metamodel). |
| self-sovereign identity | Self-Sovereign Identity (SSI) is a term that has many different interpretations, and that we use to refer to [concepts/ideas](https://trustoverip.github.io/toip/glossary#concept), architectures, processes and technologies that aim to support (autonomous) [parties](https://trustoverip.github.io/toip/glossary#party) as they negotiate and execute electronic [transactions](https://trustoverip.github.io/toip/glossary#transaction) with one another. |
| trust registry | A repository which contains a machine-readable listing of approved [governed parties](https://trustoverip.github.io/toip/glossary#governed-party) deemed compliant by a [governing authority](https://trustoverip.github.io/toip/glossary#governing-authority) over its attributable criteria of its [governance framework](https://trustoverip.github.io/toip/glossary#governance-framework). |
| verifiable credential | A tamper-evident [credential](https://essif-lab.github.io/framework/docs/essifLab-glossary#credential) whose authorship by an [issuer](https://essif-lab.github.io/framework/docs/terms/issuer) can be cryptographically verified. Verifiable credentials can be used to build [verifiable presentations](https://trustoverip.github.io/toip/glossary#verifiable-presentation), which can also be cryptographically verified. The [claims](https://trustoverip.github.io/toip/glossary#claim) in a credential can be about different [subjects](https://trustoverip.github.io/toip/glossary#subject). |

The following terms are used within this GF and defined by [eSSIF](https://trustoverip.github.io/essiflab/glossary): 

| Term | Definition |
|------|------------|
| credential type | The specification of the contents, properties, constraints etc. that credentials of this type must have/comply with. |
| Holder | Has the capability to handle presentation requests from a peer agent, produce the requested data (a presentation) according to its principal's holder-policy, and send that in response to the request. |
| Issuer | Has the capability to construct credentials from data objects, according to the content of its principal's issuer-Policy (specifically regarding the way in which the credential is to be digitally signed), and pass it to the wallet-component of its principal allowing it to be issued. |
| Verifier | Has the capability to request peer agents to present (provide) data from credentials (of a specified kind, issued by specified parties), and to verify such responses (check structure, signatures, dates), according to its principal's verifier policy. |

The following terms are used within and are specific to this GF:

| Term | Definition |
|------|------------|
| Authorized Issuers | The OCME are the authorized issuer of Creator, Curator, and Subscriber credentials.<br><br>For the MVE, there will be one authorized Curator: MusicVideoChannel.ai.<br><br>MusicVideoChannel.ai will be authorized to issue Subscriber credentials<br><br>For the MVE, MusicVideoShow.ai and SaturdayMorningCartoons.ai provide services for OCME credentialed Creators to add content to the OCME. |
| Assistant Curator         | This role works with a Curator to build, grow, and foster a supportive and thriving channel.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Compatible Issuer tool    | A compatible issuer tool is one that is used by an issuer or verifier that enables the issuing of VCs, receiving of verifiable presentations and the verification of the verifiable presentation for Creator, Curator, Subscriber, and Split-Sheet verifiable credentials.                                                                                                                                                                                                                                                                                                         |
| Compatible wallet         | A compatible wallet is one that is used by a holder or issuer that enables the issuing, storing and verifying of identity, cryptocurrency, and other data objects.                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Curator                   | The Curator role within OCME is pivotal in maintaining the quality and integrity of our content and community. By managing upload sites, fostering collaboration, and curating engaging video compilations, curators play a critical role in our organization’s success. The financial incentives ensure that curators are rewarded for their efforts, promoting growth and excellence within the community.<br><br>See [Curator Description Detailed](https://docs.google.com/document/d/1PXcc3UgOvY92Ru1VkskL_FL10xc1nDpYONbxn86JRFQ/edit?tab=t.0#heading=h.1tb5tu7bobwg) below. |
| Curator Applicant         | A [party](https://essif-lab.github.io/framework/docs/terms/party) who has submitted an application to join the OCME as a Curator.                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Dependent Processes       | Processes that are dependent on the credentials issued and verified within this GF.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Issuer tool               | The application/tool a party uses to issue VCs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Industry Advisory Council | The IAC is a group of [actors](https://trustoverip.github.io/toip/glossary#actor) who advise, administer and maintain the OCME GF. See [OCME GF - Appendix F - Industry Advisory Council](https://docs.google.com/document/u/3/d/1b232tpkboHqYNo8GYkRHcSc2fUrEUeZYN3CjRoMO55A/edit) for operating details.                                                                                                                                                                                                                                                                         |
| Infrastructure Provider   | An [organization](https://essif-lab.github.io/framework/docs/terms/organization) that provides all of the required infrastructure detailed in this GF.                                                                                                                                                                                                                                                                                                                                                                                                                             |
| OCME credentials          | Creator: Enables creation of split-sheets and uploading of commercial content to the OCME<br><br>Curator: Enables access to OCME content for the purposes as defined in the content license (streaming, Video on Demand, etc.).<br><br>Subscriber: Enables access to any OCME Curated Channel.<br><br>Split-Sheet: A list of Creators and their respective percentage revenue share for revenue generated from commercial interactions with the content.                                                                                                                           |
| Trust Community           | The parties that participate in a GF to enable a trusted ecosystem amongst parties that issue, hold and verify VCs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Verifiable Presentation   | The schema/set of data requested from a holder by a verifier.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Verified Credentials      | A verifiable credential (VC) is a digital representation of attributes that can be used to prove certain facts. VCs are cryptographically secure and tamper-evident, and can be verified by machines. They can represent information from physical credentials, like a driver's license or passport, as well as new things that don't have a physical equivalent, like content ownership, membership, and payment addresses.                                                                                                                                                       |

## A.1 Curator Description Detailed

### A.1.1 Channel Curator Responsibilities and Expectations

Channel Curators are responsible for maintaining an engaging channel that attracts subscribers, creators, advertisers and promotes community engagement. Their key responsibilities include:

- **Content Management:**
  - Ensure that all uploaded content adheres to the governance framework, brand guidelines, and labeling requirements.
  - Oversee the submission process to ensure that high-quality and relevant videos are uploaded.
- **Community Engagement in Micro Sites:**
  - Foster a collaborative environment within the creator community.
  - On-boarding new members into The OCME
  - Engage with creators, providing feedback and support to enhance the quality of their content.
  - Manage the community, ensuring all creators adhere to the governance framework.
- **Video Compilation:**
  - Curate 30-minute branded and labeled video compilations ("wheels") to ensure an engaging selection of content.
  - Select videos that align with audience preferences.
  - You will build compelling streaming content, not just video-on-demand
- **Quality Assurance:**
  - Monitor the uploaded content for adherence to standards and guidelines.
  - Ensure that all videos meet the technical and creative quality expected by the channel.
- **Advertising and Marketing:**
  - Promote the channel and its content through various platforms and social media.
  - Implement advertising strategies to attract new advertisers and Industry Members.
- **Reporting and Feedback:**
  - Provide regular updates to the Network on the performance and progress of the channel.
  - Offer feedback on the content and suggest improvements for future compilations and community engagement strategies.
- **Value Creation:**
  - As a Curator you are here to add value to the community, not syphon it away. This is done through the community engagement, quality assurance and uniqueness you bring.

The above list of responsibilities is expected to be much closer to a full time job than a couple hours per week, if not multiple full time jobs. 

## A.1.2 Process to Join OCME as a Curator

Process is subject to slight variation. This is a governed process and is administered by the IAC.

1. A Curator Applicant fills out an application and submits it. 
2. The application form MUST be hosted on the ocmeco.org website such that it is publicly accessible.
3. The IAC reviews and discusses the application. The application must be discussed in an IAC meeting. 
4. The IAC holds a vote at the next meeting (where quorum is met) following the discussion. This allows time for any open questions to get answered prior to the vote. 
5. The vote will be conducted and a supermajority of at least ⅔ vote is required to accept a new curator. 
6. A vote will either accept or reject the applicant.

## A.1.3 Curator Benefits

Being a curator at the OCME comes with many great benefits that include but are not limited to:

- Full access to our growing catalog of content (music videos, music, podcasts and more) to build out your channel.
- Access to the OCME mailing list to promote your channel and specials.
- Full community support.
- Access to cutting edge infrastructure technology that handles streaming, payments and more.

## A.1.4 Enforcement

The OCME takes its Curators very seriously and expects each curator to abide by the  responsibilities and expectations listed above. If a curator is no longer upholding the values expected of them, the IAC may intervene. The IAC should make a best faith effort to work with the curator to correct the situation. If the situation can not be corrected the IAC may call a vote to remove the Curator. A supermajority of at least ⅔ vote is required to remove a curator.

## A.1.5 Additional Information

There is no limit to the number of curators the OCME is allowed to have.
