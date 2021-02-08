# ToIP DP0004: Privacy by Design
- Authors: [Jim St.Clair](jum.stclair@lumedic.io), [Steve McCown]{smccown@anonyome.com}
- Status: [PROPOSED](https://trustoverip.github.io/deliverables/process/lifecycle_management/#proposed)
- Since: 2020-11-29
- Status Note: Draft
- Supersedes: N/A
- Start Date: 2020/11/20
- Tags: (see ../../../tags.md)

## Summary
Privacy by Design (PbD) is a systems design approach that offers a set of principles for incorporating privacy-protecting requirements in the system design phase rather than leaving them to the end of development processes [1].  The European Union's General Data Protection Regulation (GDPR) specifies Privacy By Design as a Key Issue [2] and the Privacy by Design concepts (data protection by design) have been codified in Article 25 of the GDPR [3].  [Dr. Cavoukian](https://www.ryerson.ca/tedrogersschool/trlc/our-people/fellows/dr--ann-cavoukian/), who created Privacy By Design, is the Executive Director of Ryerson University's Privacy and Big Data Institute, which has partnered with Deloitte to create a Privacy By Design Certification process[4], although such is not required by the GDPR.

## Motivation
"Privacy" has been subject to almost constant interpretation and societal pressures. As stated by the founder of PdB, Dr. Ann Couvikian, stated, "The importance of privacy cannot be overstated." Privacy as concept is further complicated constantly evolving and emerging technology. Privacy can and must co-exist alongside other critical requirements: security, functionality, operational efficiency, organizational control, business processes, and usability. PbD aims to inculcate privacy as part of every consideration of system design.  

## Scope
Privacy by Design prescribes that we build privacy directly into the design and operation, not only of technology, but also of operational systems, work processes, management structures, physical spaces and networked infrastructure. As such, the scope of the PbD supports each architectural layer and business and technical process flows. The PdB can only be excluded if the architecture and process flow(s) provides documented evidence that the system design does not use personal data.

## Design Goals
The goals of the PdB are to a) Promote trust in the design and use of the system by the user, b) Promote accountability to its users, stakeholders, and regulatory authorities and c) Build transparency into the systems design process and support Privacy Enhancing Technologies (PET)

## List of Principles
| Principle | Description |
| --- | --- |
| 1. Proactive not Reactive; Preventative not Remedial | To achieve this principle, data security SHALL be a priority from the beginning of the design process. The TIP SHALL demonstrate preventative controls that mitigate data loss and promote data loss prevention. |
| 2. Privacy as the Default | Personal data SHALL be automatically protected in any system or business practice. The TIP SHOULD limit any need for users to separately protect their data. |
| 3. Privacy Embedded into Design | Privacy controls SHALL NOT be considered as a "trade off" to user experience. The TIP SHALL promote doing principles that in implementation effectively manage user privacy. Privacy SHALL be integrated in a holistic and creative way. |
|4. Full Functionality — Postive-Sum, not Zero-Sum | Privacy measures SHALL be included as part of TIP design and architecture. The planned functionality of the TIP SHALL include privacy considerations as part of the system design. |
| 5. End-to-End Security — Lifecycle Protection | TIP architecture(s) and information models SHALL include privacy consideration and mapping of personal data. |
| 6. Visibility and Transparency | TIP design SHALL support Visibility and Transparency of user data and provide user guidance of exactly how personal data is captured, stored, processed, transmitted and can be deleted. |
| 7. Respect for User Privacy | TIP design SHALL include an approved ecosystem governance framework and trust assurance framework that inculcates all regulations, statues, standards and laws related to protecting user data. |

## Synopsis

### 1. Proactive not Reactive; Preventative not Remedial
The Privacy by Design approach is characterized by proactive rather than reactive measures. It anticipates and prevents privacy invasive events. It does not wait for risks to materialize, nor does it offer remedies for resolving infractions once they have occurred—it aims to prevent them from occurring. In short, Privacy by Design comes before-the-fact, not after.

### 2. Privacy as the Default
Privacy by Design seeks to deliver the maximum degree of privacy by ensuring that personal data are automatically protected in any given IT system or business practice. If an individual does nothing, their privacy remains intact. No action is required on the part of the individual to protect their privacy—it is built into the system, by default.

### 3. Privacy Embedded into Design
Privacy is embedded into the design and architecture of IT systems and business practices. It is not bolted on as an add-on, after the fact. The result is that privacy becomes an essential component of the core functionality being delivered. Privacy is integral to the system, without diminishing functionality.

### 4. Full Functionality - Positive Sum, not Zero Summary
Privacy by Design seeks to accommodate all legitimate interests and objectives in a positive-sum, or doubly enabling “win-win” manner, not through a dated, zero-sum approach, where unnecessary trade-offs are made. It avoids the pretense of false dichotomies, such as privacy vs. security, demonstrating
that it is possible to have both.

### 5. End-to-End Security — Lifecycle Protection
Privacy, having been embedded into the system prior to the first element of information being collected, extends throughout the entire lifecycle of the data involved, from start to finish. This ensures that at the end of the process, all data are securely destroyed, in a timely fashion. Thus, Privacy by Design ensures cradle to grave, lifecycle management of information, end-to-end.

### 6. Visibility and Transparency
Privacy by Design seeks to assure all stakeholders that whatever the business practice or technology involved, it is in fact, operating according to the stated promises and objectives, subject to independent verification. Its component parts and operations remain visible and transparent, to users and providers alike. Remember, trust but verify.

### 7. Respect for User privacy
Above all, Privacy by Design requires architects and operators to keep the interests of the individual uppermost by offering such measures as strong privacy defaults, appropriate notice, and empowering user-friendly options. Keep it user-centric—focused on the individual.

## Relevance

```
Explain the positioning of each principle against the overarching goals of this proposal.  How / where would they be used (example Use cases or industry sectors).
DELETE THIS COMMENT
```

## Trade-offs
While there is no question of the importance of embedding privacy into systems design, there may be trade-offs to consider in compliance with these principles:
1. Regulation - certain regulatory environments (such as finance and healthcare) may require identification or accountability of information that may limit incorporation of the PbD design principles.
2. System limitation - Despite best efforts to incorporate these principles, there may be limitations in the system design, such as software, platform, design cost, portability, or accessibility that impact the PdB system design.

## References
1. Cavoukian, Ann, Ph.D., Information & Privacy Commissioner, Ontario, Canada, "Privacy by Design: The 7 Foundational Principles Implementation and Mapping of Fair Information Practices", https://iapp.org/media/pdf/resource_center/pbd_implement_7found_principles.pdf
2. General Data Protection Regulation (GDPR), Key Issues, Privacy By Design, https://gdpr-info.eu/issues/privacy-by-design/
3. General Data Protection Regulation, Article 25, https://gdpr-info.eu/art-25-gdpr/
4. Deloitte, Ryerson University, Privacy By Design Certification, https://www2.deloitte.com/content/dam/Deloitte/ca/Documents/risk/ca-en-ers-privacy-by-design-brochure.PDF
