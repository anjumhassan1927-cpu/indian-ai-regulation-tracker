# India's AI Regulatory Framework — A Legal Analysis

**Part of the Indian AI Regulation Tracker**
*Maintained by Dr. Anjum Hassan | Ph.D. (Law), Amity University, Noida (2021)*

---

## Overview

India does not yet have a dedicated Artificial Intelligence Act. As of April 2026,
AI governance in India is distributed across a patchwork of existing statutes,
ministry-level advisory guidelines, and proposed legislative instruments that were
drafted without AI specifically in mind. This document maps that landscape
systematically — identifying what each instrument covers, where the gaps lie, and
what a future Indian AI governance framework must address.

The absence of binding AI-specific legislation places India behind the European
Union, which enacted the world's first comprehensive AI Act in 2024, and in a
similar position to the United States and United Kingdom, both of which have
opted for sector-led, principles-based approaches rather than a unified statute.
For a constitutional democracy of India's scale — where AI is already deployed
in public administration, law enforcement, judicial support systems, and social
welfare delivery — the absence of a binding framework raises acute concerns
under Articles 14, 19, and 21 of the Constitution of India.

---

## 1. Information Technology Act 2000

### What It Covers
The Information Technology Act 2000 (IT Act) is India's foundational statute
governing electronic commerce, cybercrime, and digital intermediaries. It was
enacted before artificial intelligence existed as a mainstream technology and
contains no reference to AI, machine learning, or algorithmic systems.

### How It Applies to AI (By Analogy)
Despite its age, several provisions of the IT Act apply to AI-related harms
by analogy:

- **Section 43** — Unauthorised access to computer systems: applies where AI
  tools are used to access data without authorisation
- **Section 66** — Computer-related offences: applies to AI systems used to
  commit fraud, identity theft, or data manipulation
- **Section 66E** — Violation of privacy: applies to AI-powered surveillance,
  facial recognition, and biometric data collection without consent
- **Section 66F** — Cyber terrorism: applies where AI is weaponised for
  critical infrastructure attacks
- **Section 67A/67B** — Publishing obscene content: applies to AI-generated
  non-consensual intimate imagery (deepfakes)
- **Section 79** — Safe harbour for intermediaries: the most contested
  provision in the AI context — whether AI platforms qualify as intermediaries
  and whether algorithmic amplification of harmful content destroys safe harbour
  protection remains unresolved

### Critical Gap
The IT Act's intermediary liability framework, last significantly amended in
2021 through the Information Technology (Intermediary Guidelines and Digital
Media Ethics Code) Rules, was not designed for generative AI platforms.
A platform that uses AI to generate — rather than merely host — content
cannot straightforwardly claim Section 79 safe harbour protection. This gap
has not yet been addressed by Indian courts or the legislature.

---

## 2. Digital Personal Data Protection Act 2023

### What It Covers
The Digital Personal Data Protection Act 2023 (DPDP Act) is India's first
comprehensive data protection statute. It received Presidential assent on
11 August 2023 and governs the processing of digital personal data within
India and outside India where such processing relates to the offering of
goods or services to data principals in India.

### Key Provisions Relevant to AI

**Section 4** — Grounds for processing personal data: establishes that
personal data may only be processed for a lawful purpose with the consent
of the data principal, or for certain legitimate uses. AI systems that
process personal data — including facial recognition, behavioural profiling,
and predictive analytics — must satisfy this requirement.

**Section 6** — Consent requirements: consent must be free, specific,
informed, unconditional, and unambiguous. AI systems that derive inferences
from personal data without explicit consent for those specific inferences
may violate Section 6.

**Section 8** — Obligations of data fiduciaries: organisations that deploy
AI systems processing personal data must ensure accuracy, completeness, and
consistency of data — directly relevant to algorithmic decision-making systems
in credit scoring, recruitment, and public administration.

**Section 9** — Processing of children's data: prohibits behavioural
monitoring of children and targeted advertising directed at children.
AI-driven recommendation algorithms on platforms used by minors engage
this provision directly.

**Section 17** — Exemptions: grants the Central Government broad exemption
powers for reasons of state security and public order. The scope of these
exemptions in the context of AI-powered surveillance by state agencies is
a significant constitutional concern.

### Critical Gap
The DPDP Act addresses data protection but does not regulate AI decision-making
as such. It does not require algorithmic transparency, explainability of
automated decisions, or human oversight of AI systems — all of which are
mandatory under the EU AI Act 2024. A person adversely affected by an
automated decision — denial of a loan, rejection of a job application,
or flagging by a predictive policing system — has no statutory right under
the DPDP Act to an explanation of how that decision was reached.

---

## 3. Bharatiya Nyaya Sanhita 2023

### What It Covers
The Bharatiya Nyaya Sanhita 2023 (BNS) replaced the Indian Penal Code 1860
with effect from 1 July 2024. It is India's principal criminal statute and,
like its predecessor, was not drafted with AI-specific offences in mind.

### How It Applies to AI (By Analogy)

- **Section 318** — Cheating: applies where AI systems are used to deceive
  victims through automated fraud, phishing, or synthetic impersonation
- **Section 336** — Forgery: applies to AI-generated fake documents,
  deepfake videos, and synthetic identity fraud
- **Section 351** — Criminal intimidation: applies where AI-generated
  content is deployed to threaten or harass individuals
- **Section 356** — Defamation: applies to AI-generated false content
  published to harm reputation, though mens rea requirements complicate
  attribution to anonymous AI users

### Critical Gap
The BNS contains no provision specifically addressing AI-generated harm.
The mens rea requirements across BNS offences — which require proof of
intention or knowledge — are difficult to satisfy in cases where harm
is caused by an autonomous AI system acting without direct human instruction
at the point of harm. The question of criminal liability for AI developers,
deployers, and users remains entirely unaddressed in Indian criminal law.

---

## 4. India's Draft National AI Policy and MeitY Guidelines

### What They Cover
The Ministry of Electronics and Information Technology (MeitY) has issued
advisory frameworks and discussion papers on AI governance, including:

- **National Strategy for Artificial Intelligence** (NITI Aayog, 2018):
  India's first AI policy document, focused on AI for social good across
  five sectors — healthcare, agriculture, education, smart cities, and
  smart mobility. Non-binding.
- **Responsible AI for All** (NITI Aayog, 2021): a principles-based
  framework identifying seven principles for responsible AI — safety,
  reliability, inclusivity, non-discrimination, privacy, transparency,
  and accountability. Non-binding.
- **MeitY Advisory on AI Platforms** (March 2024): directed AI platforms
  to label AI-generated content, seek government permission before
  deploying unreliable AI models, and ensure AI outputs do not threaten
  electoral integrity. Advisory only — not backed by statutory authority.
- **India AI Mission** (March 2024): a ₹10,372 crore government initiative
  to build AI compute infrastructure, datasets, and application ecosystems.
  Governance framework to follow.

### Critical Gap
Every Indian AI governance instrument to date is advisory, aspirational,
or infrastructure-focused. None creates binding obligations, enforceable
rights, or legal liability. The MeitY March 2024 advisory was criticised
for attempting to regulate AI platforms without statutory authority —
raising questions about its constitutional validity under Article 19(1)(a).

---

## 5. Constitutional Framework

### Articles 14, 19, and 21 as the Foundation for AI Rights

In the absence of AI-specific legislation, the Constitution of India
provides the most robust framework for challenging harmful AI systems.

**Article 14 — Equality before law**: algorithmic systems that produce
discriminatory outcomes — in credit, employment, education, or criminal
justice — violate the constitutional guarantee of equality. The Supreme
Court's proportionality doctrine, applied in *K.S. Puttaswamy v. Union
of India* (2017) 10 SCC 1, requires that any interference with fundamental
rights by the state (or state-sanctioned systems) must satisfy the tests
of legality, legitimate aim, proportionality, and procedural safeguards.

**Article 19(1)(a) — Freedom of speech**: AI-generated content, deepfakes,
and algorithmic content moderation all engage free expression rights.
The government's March 2024 advisory requiring AI platforms to seek
permission before deploying models raises a direct Article 19(1)(a)
question about prior restraint.

**Article 21 — Right to life and personal liberty**: the right to
privacy — established as a fundamental right in *Puttaswamy* — is the
constitutional foundation for challenging AI surveillance, biometric
data collection, predictive policing, and automated decision-making
in criminal justice. Every AI system deployed by the Indian state that
processes personal data or makes decisions affecting individual liberty
must satisfy the *Puttaswamy* proportionality standard.

---

## 6. Summary — India's AI Governance Gap Matrix

| Governance Need | Current Indian Instrument | Adequate? |
|---|---|---|
| Data protection in AI systems | DPDP Act 2023 | Partial |
| Algorithmic transparency | None | No |
| Explainability of automated decisions | None | No |
| AI liability framework | None | No |
| Judicial AI use rules | None | No |
| Deepfake-specific offences | None | No |
| AI in criminal justice regulation | None | No |
| Child protection from AI | DPDP Act 2023, Section 9 | Partial |
| State AI surveillance limits | Article 21 (constitutional) | Partial |
| Binding AI ethics framework | None | No |

---

## 7. Research Gaps and Future Directions

The following questions are identified as priorities for future
Scopus-targeted legal scholarship on Indian AI governance:

1. Does the DPDP Act 2023 satisfy India's obligations under the right
   to privacy as established in *Puttaswamy*, with particular reference
   to AI-driven data processing by state agencies?

2. Is a binding Indian AI Act constitutionally necessary, or can
   adequate AI governance be achieved through delegated legislation
   under the IT Act and DPDP Act?

3. How should Indian criminal law attribute liability for harm caused
   by autonomous AI systems — to developers, deployers, or users?

4. What constitutional constraints apply to the use of AI in Indian
   judicial proceedings, including predictive sentencing tools,
   AI-assisted evidence analysis, and algorithmic bail assessment?

5. Does the MeitY March 2024 advisory on AI platforms constitute
   an unconstitutional prior restraint on speech under Article 19(1)(a)?

---

## References and Authorities

- Constitution of India, Articles 14, 19, 21
- Information Technology Act 2000
- Digital Personal Data Protection Act 2023
- Bharatiya Nyaya Sanhita 2023
- *K.S. Puttaswamy v. Union of India* (2017) 10 SCC 1
- *Shreya Singhal v. Union of India* AIR 2015 SC 1523
- NITI Aayog, National Strategy for Artificial Intelligence (2018)
- NITI Aayog, Responsible AI for All (2021)
- MeitY Advisory on AI Platforms (March 2024)
- EU AI Act 2024 (Regulation EU 2024/1689)
- India AI Mission, Cabinet Approval (March 2024)

---

*Part of the Indian AI Regulation Tracker*
*Maintained by Dr. Anjum Hassan | Ph.D. (Law), Amity University, Noida*
*ORCID: [0009-0001-5212-2320](https://orcid.org/0009-0001-5212-2320)*
*Last updated: April 2026*
