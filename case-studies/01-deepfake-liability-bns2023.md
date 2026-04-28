# Case Study 01: Deepfake Liability Under the Bharatiya Nyaya Sanhita, 2023

**Repository:** Indian AI Regulation Tracker — Emerging-Tech Legal Frameworks  
**Maintained by:** Dr. Anjum Hassan (Ph.D., Law — Amity University, Noida; LL.M. First Class — GGSIPU, New Delhi)  
**Series:** Annotated Case Studies — Applying Existing Indian Law to AI Fact-Patterns  
**Status:** Living Document | Last Updated: April 2026

---

## 1. Overview

Deepfake technology — the use of generative AI and deep learning models to synthesise or manipulate audio-visual content depicting real persons — has emerged as one of the most legally complex challenges posed by artificial intelligence to Indian criminal and civil law. This case study maps the liability landscape for deepfake-related harms under the **Bharatiya Nyaya Sanhita, 2023 (BNS)**, which replaced the Indian Penal Code, 1860 with effect from 1 July 2024, while also identifying the residual role of the **Information Technology Act, 2000 (IT Act)** and the **Digital Personal Data Protection Act, 2023 (DPDPA)**.

---

## 2. The AI Fact-Pattern

> **Hypothetical:** A generative AI tool is used to produce a non-consensual sexually explicit deepfake video of a named female professional. The video is disseminated via a messaging platform. The subject is identifiable; the content was never consented to; and the creator is a private individual with no institutional affiliation.

This fact-pattern is chosen because it represents the most litigated and legislatively acknowledged deepfake scenario in India, and because it exposes the maximum tension between existing statutory provisions and the novel characteristics of AI-generated content.

---

## 3. Applicable Provisions Under the BNS, 2023

### 3.1 Section 95 — Circulating Obscene Material

**Text (relevant extract):** Whoever sells, lets to hire, distributes, exhibits, or circulates obscene material in electronic form shall be punished with imprisonment which may extend to three years and fine.

**Application:**  
The dissemination of the deepfake video via a messaging platform squarely engages Section 95. The critical analytical question is whether AI-generated content — depicting a real person in a fabricated scenario — satisfies the *Ranjit Udeshi v. State of Maharashtra* (1965) test of obscenity, now codified: that the material, taken as a whole, appeals to prurient interest and lacks serious literary, artistic, or scientific value. AI-generated sexually explicit deepfakes present no redemptive value; the provision applies.

**Gap Identified:**  
Section 95 addresses *circulation* but is silent on *creation*. The act of generating the deepfake — without dissemination — does not attract criminal liability under this provision.

---

### 3.2 Section 79 — Criminal Intimidation Using Digital Content

**Text (relevant extract):** Whoever threatens another with injury to that person's reputation with intent to cause alarm shall be punished with imprisonment of either description for a term which may extend to two years, or with fine, or with both.

**Application:**  
Where the deepfake is used as an instrument of coercion — e.g., threatened release to the victim's employer or family unless demands are met — Section 79 applies. The synthetic origin of the content does not diminish the threat; the reputational harm is real and calculable.

**Gap Identified:**  
Proof of *specific intent to cause alarm* may be difficult where the creator disseminates broadly rather than targets one individual. The provision is better suited to targeted harassment than mass publication.

---

### 3.3 Section 77 — Voyeurism

**Text (relevant extract):** Whoever watches or captures the image of a woman engaging in a private act without her consent shall be punished with imprisonment of not less than one year, which may extend to three years.

**Application:**  
This provision is drafted around *actual* observation or capture. A deepfake, by definition, does not involve real observation or real capture — no act of voyeurism occurs in the physical sense. Courts applying Section 77 to deepfakes must resolve whether a synthetically generated image of a woman in a fabricated private act is equivalent to a "captured image." There is no authoritative Indian precedent on this point.

**Gap Identified:**  
This is a significant statutory gap. Section 77 BNS does not cover non-consensual AI-generated intimate imagery (NCAII). The provision requires a real underlying act that was observed or recorded.

---

### 3.4 Section 72 — Assault or Criminal Force with Sexual Intent

*Not directly applicable to purely digital deepfake creation or dissemination. Noted here for completeness where deepfake is part of a physical intimidation campaign.*

---

## 4. Residual Liability Under the IT Act, 2000

| Provision | Relevance to Deepfakes |
|-----------|----------------------|
| **Section 66E** — Violation of privacy | Captures/publishes images of a person's private area without consent. Similar ambiguity as BNS Section 77: requires a real underlying image. |
| **Section 67** — Publishing obscene material electronically | Covers publication/transmission of obscene content online. Broader than BNS Section 95; does not require physical circulation. Directly applicable to deepfake dissemination. |
| **Section 67A** — Publishing sexually explicit material electronically | Specifically targets sexually explicit acts in electronic form. Strong application to non-consensual deepfake pornography. Punishment: up to five years imprisonment and fine on first conviction. |
| **Section 67B** — Child pornography | Where the depicted individual is a minor (or appears to be), this provision applies regardless of the synthetic nature of the content. Punishment: up to five years. |

**Key observation:** Section 67A IT Act currently provides the most robust statutory basis for prosecuting creators and distributors of non-consensual sexual deepfakes, irrespective of BNS amendments.

---

## 5. Digital Personal Data Protection Act, 2023 — Regulatory Dimension

The DPDPA is not a criminal statute, but it introduces a parallel regulatory liability that is increasingly relevant to deepfake cases:

- **Section 4** — Personal data may only be processed for a lawful purpose with consent. Biometric data used to train or generate a deepfake (face geometry, voice patterns) constitutes personal data under the Act.
- **Section 9** — Processing of children's personal data requires verifiable parental consent and prohibits behavioural monitoring.
- **Enforcement:** The Data Protection Board of India (DPBI) may levy civil penalties. Criminal liability remains under BNS/IT Act.

**Gap Identified:** The DPDPA does not explicitly address *synthetic data* generated from personal data. Whether a deepfake constitutes "processed personal data" or a derivative work is unresolved.

---

## 6. Comparative Snapshot

| Jurisdiction | Primary Legal Instrument | Synthetic NCII Explicitly Covered? |
|---|---|---|
| **India** | BNS 2023 + IT Act 2000 + DPDPA 2023 | No explicit provision; reliance on analogue offences |
| **United Kingdom** | Online Safety Act 2023 | Yes — Section 188 criminalises sharing intimate deepfakes |
| **European Union** | AI Act 2024 (Art. 5) + existing member-state law | Prohibited use (manipulation of persons); enforcement varies |
| **United States** | No federal statute; state-level patchwork (TX, VA, CA) | Partial — no uniform federal framework |
| **Singapore** | Online Safety Act 2022 + Criminal Procedure Code amendments | Yes — explicit takedown obligations for NCII |

---

## 7. Identified Research Gaps

1. **Absence of a dedicated NCAII provision in the BNS:** India has not enacted the equivalent of the UK's Section 188 (Online Safety Act 2023). Legislative reform is overdue.

2. **Mens rea ambiguity for AI-generated content:** Where a user employs an automated tool without manually fabricating the image, questions arise as to whether the *dolus specialis* (specific intent) required under BNS provisions is established.

3. **Platform liability under Section 79 IT Act (Safe Harbour):** Whether an intermediary that hosts deepfake content loses safe harbour protection — and at what point of *actual knowledge* — is untested in the deepfake context post-BNS.

4. **Admissibility of AI-generated evidence:** A separate case study in this repository addresses the admissibility question (see: `03-admissibility-ai-evidence.md`). The evidentiary challenges in proving that content is AI-generated, and the chain of custody for digital forensic proof, remain acute.

5. **Civil remedies:** Tort law claims (defamation, passing off, breach of confidence, invasion of privacy) run parallel to criminal liability and may offer more accessible remedies for victims. This intersection is underexplored in Indian scholarship.

---

## 8. Analytical Conclusion

The BNS 2023, while a significant modernisation of Indian criminal law, does not explicitly address AI-generated non-consensual intimate imagery. Prosecutors must currently construct liability through provisions drafted for analogue-era offences — a process that introduces uncertainty at every element of the offence. Section 67A of the IT Act 2000 remains the strongest available instrument.

**Policy recommendation:** India should enact a standalone provision — either by amending the IT Act or through a dedicated AI liability instrument — that explicitly criminalises: (a) the creation, (b) the possession with intent to distribute, and (c) the distribution of non-consensual AI-generated intimate imagery, mirroring the structure of the UK Online Safety Act 2023 while calibrating penalties to Indian sentencing norms.

---

## 9. Citation & Use

This case study is part of an open-access living research repository. It is intended for legal scholarship, student research, and policy analysis. It does not constitute legal advice.

**Cite as:**  
Hassan, A. (2026). *Deepfake Liability Under the Bharatiya Nyaya Sanhita, 2023: An Annotated Case Study*. Indian AI Regulation Tracker — Emerging-Tech Legal Frameworks. GitHub Repository. https://github.com/anjumhassan1927-cpu/Indian-AI-Regulation-Tracker-a-living-GitHub-repository-mapping-AI-emerging-tech-legal-frameworks

---

*Next in series: `02-algorithmic-bias-bail-sentencing.md` — Algorithmic Bias in Bail and Sentencing Decisions Under Indian Law*
