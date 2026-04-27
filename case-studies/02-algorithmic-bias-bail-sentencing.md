# Case Study 02: Algorithmic Bias in Bail and Sentencing Decisions Under Indian Law

**Repository:** Indian AI Regulation Tracker — Emerging-Tech Legal Frameworks  
**Maintained by:** Dr. Anjum Hassan (Ph.D., Law — Amity University, Noida; LL.M. First Class — GGSIPU, New Delhi)  
**Series:** Annotated Case Studies — Applying Existing Indian Law to AI Fact-Patterns  
**Status:** Living Document | Last Updated: April 2026

---

## 1. Overview

Algorithmic decision-support tools are increasingly being evaluated — and in some jurisdictions already deployed — in criminal justice contexts, including pre-trial bail assessments, risk scoring for sentencing, and parole eligibility determinations. This case study examines the legal implications of such tools under **Indian constitutional and statutory law**, focusing on the right to a fair trial, the principles of natural justice, anti-discrimination provisions, and the emerging data protection framework under the **Digital Personal Data Protection Act, 2023 (DPDPA)**.

India has not yet formally deployed a standardised AI risk-assessment tool in its criminal courts, but the trajectory of judicial digitisation — including the eCourts Mission Mode Project and SUPACE (Supreme Court Portal for Assistance in Courts Efficiency) — makes this a near-term legislative and judicial challenge. This case study applies existing law to the anticipated fact-pattern to identify where Indian law is adequate, where it is silent, and what reform is required.

---

## 2. The AI Fact-Pattern

> **Hypothetical:** A sessions court in a metropolitan jurisdiction uses an AI-based risk assessment tool — trained on historical conviction and recidivism data — to generate a "flight risk score" and a "reoffending probability score" for an undertrial prisoner seeking bail. The tool outputs a high-risk classification. The judge relies substantially on this output in refusing bail. The accused is not informed of the tool's existence, the data used, or the weight assigned to its output. The accused is from a marginalised socioeconomic community historically overrepresented in conviction data.

This fact-pattern is modelled on documented concerns with tools such as COMPAS (USA) and similar instruments, adapted to the Indian procedural and constitutional context.

---

## 3. Constitutional Framework

### 3.1 Article 21 — Right to Life and Personal Liberty

Article 21 of the Constitution of India guarantees that no person shall be deprived of life or personal liberty except according to **procedure established by law**. The Supreme Court has progressively interpreted this to require that such procedure be **fair, just, and reasonable** (*Maneka Gandhi v. Union of India*, AIR 1978 SC 597).

**Application:**  
Reliance on an opaque algorithmic score — without disclosure to the accused, without opportunity to challenge the inputs or methodology, and without the judge independently evaluating the underlying factors — arguably violates the procedural fairness standard embedded in Article 21. The deprivation of liberty (refusal of bail) based on an unexplained machine output is not "procedure established by law" in the *Maneka Gandhi* sense.

**Gap Identified:**  
Article 21 is a constitutional guarantee enforced through writ jurisdiction. It does not provide a direct statutory cause of action against the tool's developer or the court administration that procured it.

---

### 3.2 Article 14 — Right to Equality and Non-Discrimination

Article 14 prohibits the State from denying any person equality before the law. Algorithmic tools trained on historically biased criminal justice data may systematically assign higher risk scores to individuals from communities that have been disproportionately policed and prosecuted — reproducing and amplifying existing structural discrimination.

**Application:**  
If a risk assessment tool produces statistically disparate outcomes across caste, religion, or socioeconomic class — protected and proximate characteristics under Indian constitutional law — its use by a State institution (the court) constitutes State action that may be challenged under Article 14. The arbitrary classification created by a biased algorithm does not satisfy the requirement of a rational nexus to a legitimate object.

**Gap Identified:**  
There is no Indian equivalent of disparate impact doctrine as a statutory cause of action. Proving algorithmic discrimination under Article 14 requires establishing that the State *adopted* a discriminatory classification — courts may resist characterising reliance on a third-party tool as State action in the Article 14 sense.

---

### 3.3 Article 20(3) — Right Against Self-Incrimination

**Application:**  
Where behavioural or biometric data collected from the accused (e.g., during interrogation or detention) is used as an input to the risk assessment algorithm, Article 20(3) concerns arise. The Supreme Court in *Selvi v. State of Karnataka* (2010) 7 SCC 263 held that involuntary administration of techniques that extract information engage Article 20(3). Feeding compulsorily collected personal data into an algorithmic scoring system may attract similar scrutiny.

---

## 4. Statutory Framework

### 4.1 Bharatiya Nagarik Suraksha Sanhita, 2023 (BNSS) — Bail Provisions

The BNSS (which replaced the Code of Criminal Procedure, 1973) governs bail in India. Section 480 BNSS sets out factors for bail in bailable offences; Section 483 governs bail in non-bailable offences, requiring the court to consider the nature of accusation, antecedents, and likelihood of fleeing.

**Application:**  
The BNSS does not contemplate algorithmic input into bail decisions. The listed factors are **judicially assessed** criteria — not outputs of a risk-scoring model. A court that substitutes or supplements its own assessment with an unexplained algorithmic score may be acting outside the statutory framework, rendering the order vulnerable to challenge in revision or appeal.

**Gap Identified:**  
The BNSS contains no provision requiring disclosure of AI tools used in bail proceedings, no requirement of explainability, and no mechanism for the accused to challenge algorithmic inputs.

---

### 4.2 Digital Personal Data Protection Act, 2023 (DPDPA)

| Provision | Relevance |
|-----------|-----------|
| **Section 4** — Lawful processing | Personal data of the accused (criminal record, biometrics, socioeconomic data) may only be processed for a lawful purpose with consent or legal authorisation. Use in an undisclosed algorithmic tool may lack valid legal basis. |
| **Section 12** — Deemed consent for State functions | Processing is permitted without consent for "performance of any function of the State." This broad exemption may legitimise data use — but does not override procedural fairness obligations. |
| **Section 13** — Rights of Data Principal | The accused as data principal has the right to know what personal data is being processed and for what purpose. Undisclosed use of their data in a risk scoring tool arguably violates this right. |
| **Section 17** — Exemptions for State security | Courts may claim this exemption for criminal justice data processing. The scope of this exemption in the bail context is untested. |

**Gap Identified:**  
The DPDPA does not contain an **algorithmic accountability** provision. There is no right to an explanation of automated decisions (unlike Article 22 of the EU GDPR), no prohibition on solely automated decisions affecting legal rights, and no requirement for algorithmic impact assessments in criminal justice contexts.

---

### 4.3 Information Technology Act, 2000 — Section 43A

Section 43A imposes liability on a body corporate that handles sensitive personal data negligently, causing wrongful loss. Where the algorithmic tool's developer or operator negligently processes criminal justice data — producing a biased output that results in wrongful continued detention — Section 43A may provide a civil remedy against the private entity.

**Gap Identified:**  
Section 43A applies to *body corporates*, not to the State or courts directly. Its application to a government-procured AI tool operated by a private vendor requires careful analysis of the contractual and data-sharing arrangement.

---

## 5. Principles of Natural Justice

Indian administrative and judicial law recognises two core principles of natural justice:

- ***Audi alteram partem*** — the right to be heard
- ***Nemo judex in causa sua*** — no person shall be a judge in their own cause

**Application to Algorithmic Bail Decisions:**

An accused who is not informed that an algorithmic tool has been used, who has no access to the data inputs or the scoring methodology, and who has no opportunity to challenge the output, is denied the right to be heard on a decisive factor in the bail determination. This is a textbook *audi alteram partem* violation.

The Supreme Court in *Mohd. Arif v. Supreme Court of India* (2014) 9 SCC 737 affirmed that procedural fairness is not a technicality but a substantive guarantee. Algorithmic opacity in bail proceedings is incompatible with this standard.

---

## 6. Comparative Snapshot

| Jurisdiction | AI in Criminal Justice | Legal Safeguards |
|---|---|---|
| **India** | SUPACE (research assistance only, officially); no formal risk-scoring tool | No explicit statutory safeguard; constitutional challenge possible |
| **USA** | COMPAS, PSA widely used | *State v. Loomis* (Wis. 2016) upheld use with disclosure; due process concerns persist |
| **European Union** | AI Act 2024 classifies real-time criminal justice AI as **high-risk** (Annex III) | Mandatory human oversight, transparency, fundamental rights impact assessment |
| **United Kingdom** | Harm Assessment Risk Tool (HART) trialled | Suspended after bias findings; Bridges v. South Wales Police established judicial review ground |
| **Canada** | Gladue factors require individuated Indigenous offender assessment | Algorithmic tools must accommodate cultural context; no formal deployment |

---

## 7. SUPACE — India's Existing AI Judicial Tool

The Supreme Court of India launched **SUPACE** (Supreme Court Portal for Assistance in Courts Efficiency) as an AI research assistant for judges. Officially, SUPACE does not make decisions — it surfaces relevant case law and statutory provisions for judicial review.

**Legal significance:**  
Even a research-assistance tool that selectively surfaces precedents may introduce algorithmic bias into judicial reasoning if its retrieval logic is opaque or its training data is skewed. The distinction between "decision support" and "decision influence" is legally significant but practically difficult to maintain. SUPACE requires a transparency and audit framework that does not currently exist.

---

## 8. Identified Research Gaps

1. **Absence of algorithmic accountability in DPDPA:** India's data protection law contains no right to explanation for automated decisions affecting liberty — a gap relative to EU GDPR Article 22 that urgently requires legislative attention.

2. **No statutory framework for AI procurement in the judiciary:** The eCourts project and SUPACE operate without a published algorithmic impact assessment framework, vendor accountability standards, or bias audit requirements.

3. **Caste as a proxy variable:** Historical Indian criminal justice data reflects patterns of caste-based policing. Any risk-assessment tool trained on this data will embed caste as a proxy variable — a constitutional problem that has not been addressed in Indian AI policy literature.

4. **Standard of review for algorithmic bail orders:** It is unresolved whether a High Court in revision will scrutinise the use of an undisclosed algorithmic tool as a jurisdictional error, a violation of natural justice, or an error of law — each attracting a different standard and remedy.

5. **Civil liability of AI vendors in criminal justice:** The intersection of Section 43A IT Act, tort law (negligence), and government procurement contracts in fixing liability for a biased criminal justice AI tool is entirely unexplored in Indian scholarship.

---

## 9. Analytical Conclusion

Indian law — constitutional and statutory — contains the *normative foundations* to challenge algorithmic bias in bail and sentencing decisions: Article 14 (equality), Article 21 (procedural fairness), the *audi alteram partem* principle, and the data rights framework of the DPDPA. However, none of these instruments was designed with AI decision-support tools in mind, and each contains gaps that a well-advised State actor could exploit.

**Policy recommendations:**

1. Amend the BNSS to require **mandatory disclosure** to the accused whenever an AI tool contributes to a bail or sentencing determination.
2. Insert an **algorithmic accountability clause** in the DPDPA equivalent to EU GDPR Article 22 — prohibiting solely automated decisions affecting legal rights without human review and right of contest.
3. Establish an **AI Procurement Standard for the Judiciary** under the eCourts framework, requiring bias audits, explainability reports, and periodic independent review of any AI tool used in criminal proceedings.
4. Develop **Scheduled Caste / Scheduled Tribe impact assessment** as a mandatory component of any criminal justice AI deployment, given the constitutional mandate of Articles 15 and 17.

---

## 10. Citation & Use

This case study is part of an open-access living research repository. It is intended for legal scholarship, student research, and policy analysis. It does not constitute legal advice.

**Cite as:**  
Hassan, A. (2026). *Algorithmic Bias in Bail and Sentencing Decisions Under Indian Law: An Annotated Case Study*. Indian AI Regulation Tracker — Emerging-Tech Legal Frameworks. GitHub Repository. https://github.com/anjumhassan1927-cpu/Indian-AI-Regulation-Tracker-a-living-GitHub-repository-mapping-AI-emerging-tech-legal-frameworks

---

*Next in series: `03-admissibility-ai-evidence.md` — Admissibility of AI-Generated Evidence Before Indian Courts*
