---
title: Multimodal Anesthesia Protocol for Robot-Assisted Total Knee Arthroplasty
version: 1.2
last-updated: 2025-12-07
---

# Multimodal Anesthesia Protocol for Robot-Assisted Total Knee Arthroplasty

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Version](https://img.shields.io/badge/Version-1.2-blue.svg)]()
[![Last Updated](https://img.shields.io/badge/Updated-December%207%2C%202025-green.svg)]()
[![Evidence Base](https://img.shields.io/badge/Evidence-2023--2025-orange.svg)]()

---

## Educational Use Only

This repository contains educational materials developed for medical school application portfolio purposes and is not intended for clinical application.

**This is not:**
- Medical advice or clinical guidance
- An institutional guideline, policy, or order set
- Approved for clinical implementation
- A substitute for attending anesthesiologist judgment

**This is:**
- Independent pre-medical educational project
- Literature synthesis for learning demonstration
- Medical school application portfolio material

---

## Disclaimers

**Institutional Affiliation:**  
This is an independent educational project. It is not an official University of Washington or UW Medicine document and is not affiliated with, endorsed by, or approved by UW Medicine, its faculty, or staff.

**Clinical Use:**  
Any clinical consideration requires institutional review, governance approval, and attending anesthesiologist supervision. All medication dosing must be individualized to patient-specific factors and local protocols. Institutional policies supersede all content.

**Liability:**  
This work is provided "as is" without warranty of any kind. Users assume full responsibility for any use of these materials.

**Author Status:**  
Pre-medical student. Not a licensed healthcare professional.

---

## At a Glance

**What:**  
Evidence-based, three-pathway anesthesia framework for **robot-assisted total knee arthroplasty (rTKA)**:

1. **Opioid-free intraoperative anesthesia (OFIA)** + ACB/IPACK (preferred ERAS pathway)  
2. **OFIA without blocks** (block-free alternative)  
3. **Conventional opioid-inclusive anesthesia** (fallback / special indications)

**Who:**  
Anesthesia trainees, medical students, CRNAs, attending anesthesiologists, and researchers studying multimodal and opioid-sparing strategies in arthroplasty.

**Why:**  
To support **Enhanced Recovery After Surgery (ERAS)** implementation, reduce perioperative opioid exposure, preserve quadriceps strength, and optimize pain control, PONV rates, and time to mobilization in rTKA.

**Evidence:**  
Synthesized from **Level 1–2 evidence (2023–2025)** including RCTs, meta-analyses, and relevant professional publications and safety communications (e.g., ERAS/ASRA/ASA/APSF). **Incorporates clinical practice feedback from Drs. Shane Mandalia, Dr. Pauldine, and Chief CRNA Brian Buchanan** regarding standard anesthetic practices (e.g., midazolam anxiolysis, sevoflurane/propofol maintenance) and multimodal adjunct dosing.

**Terminology Note:**  
"**Opioid-free anesthesia**" in this project refers specifically to **opioid-free intraoperative anesthesia (OFIA)**.  
Postoperative opioid rescue remains available when clinically indicated and **does not constitute pathway failure**.

---

## Table of Contents

- [Overview](#overview)  
- [Quick Start](#quick-start)  
- [How to Use This Repository](#how-to-use-this-repository)  
- [Three Standardized Pathways](#three-standardized-pathways)  
- [Repository Structure](#repository-structure)  
- [File Descriptions](#file-descriptions)  
- [Key Protocol Features](#key-protocol-features)  
- [Ketamine Guardrails (Patient Selection, Hemodynamics, and Depth Monitoring)](#ketamine-guardrails-patient-selection-hemodynamics-and-depth-monitoring)  
- [Pathway Comparison](#pathway-comparison)  
- [Implementation Guide for Institutions](#implementation-guide-for-institutions)  
- [Target Audience](#target-audience)  
- [Scope and Disclaimer](#scope-and-disclaimer)  
- [Limitations and Future Directions](#limitations-and-future-directions)  
- [References](#references)  
- [Author and Contact](#author-and-contact)  
- [Acknowledgments](#acknowledgments)  
- [Citation](#citation)  
- [License](#license)  
- [Contribute](#contribute)  
- [Changelog](#changelog)

---

## Overview

This repository contains a **literature-based multimodal anesthesia framework** for robot-assisted total knee arthroplasty (rTKA). It integrates:

- **Opioid-free intraoperative anesthesia (OFIA)**  
- Quadriceps-sparing regional techniques (**ACB + IPACK**)  
- Evidence-based pharmacologic adjuncts (e.g., **ketamine**, **dexmedetomidine**, **magnesium**, NSAIDs, acetaminophen)  
- Standard anxiolytic and maintenance agents (**midazolam**, **sevoflurane**, **propofol**) per clinical consensus  
- Standardized pre-op, intra-op, PACU, and communication tools

The project is intentionally **educational and non-validated** and should be treated as a **discussion framework**, not an institutional protocol or order set. It is designed to demonstrate evidence synthesis and protocol documentation; any clinical use requires **attending anesthesiologist oversight** and local governance approval.

---

## Quick Start

### For First-Time Users

1. **See the big picture:**  
   Start with the pathway overview image:  

   ![Pathway Overview](https://github.com/collingeorge/rTKA-Multimodal-Anesthesia-Protocol/blob/main/docs/images/pathway_overview.png)

2. **Understand the three options:**  
   [`03_Anesthesia_Protocols/Protocol_Comparison_Table.md`](03_Anesthesia_Protocols/Protocol_Comparison_Table.md)

3. **Walk through the clinical workflow:**
   1. OR readiness → [`OR_Checklist_Pre-Induction.md`](OR_Checklist_Pre-Induction.md) – comprehensive pre-case safety verification  
   2. Pre-op checklist → [`01_PreOp_Checklist.md`](01_PreOp_Checklist.md)  
   3. Patient counseling → [`02_Patient_Counseling_Script.md`](02_Patient_Counseling_Script.md)  
   4. Choose a pathway → [`03_Anesthesia_Protocols/`](03_Anesthesia_Protocols/)  
   5. Intra-op decision support → [`04_IntraOp_Flowcharts/`](04_IntraOp_Flowcharts/)  
   6. PACU handoff → [`05_PACU_Handoff_Templates.md`](05_PACU_Handoff_Templates.md)

4. **Review evidence base:**  
   [`07_References_Evidence_2024.md`](07_References_Evidence_2024.md)

### For Educational Use

**Medical Students:**
- Read through `OR_Checklist_Pre-Induction.md` → `01_PreOp_Checklist.md` → `02_Patient_Counseling_Script.md` → `03_Anesthesia_Protocols/` → `05_PACU_Handoff_Templates.md` to see end-to-end perioperative care in rTKA.
- Use `07_References_Evidence_2024.md` to map protocol decisions back to primary literature.

**Residents and CRNAs:**
- Use the comparison table and quick reference cards:  
  [`03_Anesthesia_Protocols/Protocol_Quick_Reference_Cards.md`](03_Anesthesia_Protocols/Protocol_Quick_Reference_Cards.md)
- Practice patient counseling with:  
  [`02_Patient_Counseling_Script.md`](02_Patient_Counseling_Script.md)
- Master pre-case setup with:  
  [`OR_Checklist_Pre-Induction.md`](OR_Checklist_Pre-Induction.md)
- Review pathway-specific medication dosing:  
  [`03_Anesthesia_Protocols/Protocol_Medication_Dosing_and_Timing.md`](03_Anesthesia_Protocols/Protocol_Medication_Dosing_and_Timing.md)

**Researchers:**
- Treat this as a **template for protocol design and documentation**.
- Adapt sections (with local approval) for QI projects or IRB-approved studies.

---

## How to Use This Repository

### Navigation by Clinical Workflow
```text
Clinical Workflow → Repository Files

OR Checklist         → OR_Checklist_Pre-Induction.md
Pre-Op Assessment    → 01_PreOp_Checklist.md
Patient Counseling   → 02_Patient_Counseling_Script.md
Protocol Selection   → 03_Anesthesia_Protocols/Protocol_Comparison_Table.md
Intra-Op Management  → 03_Anesthesia_Protocols/[selected pathway].md
                       03_Anesthesia_Protocols/Protocol_Medication_Dosing_and_Timing.md
                       03_Anesthesia_Protocols/Protocol_Adjuncts_and_Contraindications.md
                       03_Anesthesia_Protocols/Protocol_Quick_Reference_Cards.md
                       04_IntraOp_Flowcharts/
PACU Handoff         → 05_PACU_Handoff_Templates.md
Team Coordination    → 06_Surgeon_OnePage_Summary.md
Evidence Review      → 07_References_Evidence_2024.md
Quick Reference      → 08_Quick_Reference_Cards.md
```

### Downloading for Offline Use

**Clone the repository:**
```bash
git clone https://github.com/collingeorge/rTKA-Multimodal-Anesthesia-Protocol.git
```

**Or download as ZIP:**
Click the green "Code" button → "Download ZIP"

### Printing for Binder / Pocket Reference

* Open any `.md` file in your browser → Print → Save as PDF.
* Recommended print order:
  `OR_Checklist_Pre-Induction → 01 → 02 → 03/README → selected protocol(s) → 04 → 05 → 06 → 07 → 08`
* Quick-reference cards:
  [`08_Quick_Reference_Cards.md`](08_Quick_Reference_Cards.md)
  are designed for double-sided badge card printing and lamination.

---

## Three Standardized Pathways

![Pathway Overview](docs/images/pathway_overview.png "Figure 1: Overview of Three Anesthesia Pathways")

*Figure 1: High-level overview of the three multimodal anesthesia pathways for rTKA*

### Pathway 1 – OFIA + ACB/IPACK (Preferred ERAS Pathway)

* Opioid-free intra-op with **midazolam anxiolysis (1–2 mg IV)**
* ACB + IPACK for quad-sparing, circumferential analgesia (ropivacaine 0.2–0.25%)
* **Maintenance:** Sevoflurane 0.8–1.2 MAC OR propofol TIVA 75–150 mcg/kg/min
* **Expected PACU pain:** 0–3/10 (excellent analgesia from blocks)
* **Benefits:** Minimal PONV, preserved motor function, same-day mobilization
* Optional adjuncts (e.g., ketamine, dexmedetomidine, magnesium) are **titrated to patient physiology** and may be omitted in hemodynamically fragile or high-risk patients.

### Pathway 2 – OFIA, No Blocks

* Opioid-free intra-op with **midazolam anxiolysis (1–2 mg IV)**
* Periarticular local anesthetic infiltration by surgeon (100–150 mL ropivacaine 0.2%)
* **Maintenance:** Sevoflurane 0.8–1.2 MAC OR propofol TIVA 75–150 mcg/kg/min
* **Expected PACU pain:** 3–6/10 (good analgesia, higher than with blocks)
* **Benefits:** Fast workflow, no block contraindications, low PONV
* Optional adjuncts (e.g., ketamine, dexmedetomidine, magnesium) are **titrated to patient physiology** and may be omitted in hemodynamically fragile or high-risk patients.

### Pathway 3 – Conventional Opioid-Inclusive Anesthesia

* Fentanyl/hydromorphone-based with **midazolam anxiolysis (1–2 mg IV)**
* **Maintenance:** Sevoflurane 0.8–1.2 MAC + opioid boluses PRN (propofol TIVA optional)
* Optional ACB/IPACK for improved analgesia
* **Expected PACU pain:** Variable (2–6/10 depending on blocks)
* **Indications:** Chronic opioid use, severe anxiety, OFIA contraindications

---

## Repository Structure
```text
rTKA-Multimodal-Anesthesia-Protocol/
├── README.md
├── docs/
│   └── images/
│       ├── pathway_overview.png
│       ├── spinal_vs_ga_flowchart.png
│       └── pacu_rescue_algorithm.png
├── OR_Checklist_Pre-Induction.md
├── 01_PreOp_Checklist.md
├── 02_Patient_Counseling_Script.md
├── 03_Anesthesia_Protocols/
│   ├── README.md
│   ├── Protocol_1_ACB_IPACK_OFIA.md
│   ├── Protocol_2_BlockFree_OFIA.md
│   ├── Protocol_3_OpioidBased.md
│   ├── Protocol_Medication_Dosing_and_Timing.md
│   ├── Protocol_Adjuncts_and_Contraindications.md
│   ├── Protocol_Quick_Reference_Cards.md
│   └── Protocol_Comparison_Table.md
├── 04_IntraOp_Flowcharts/
│   ├── README.md
│   ├── Spinal_vs_GA_Decision.md
│   └── PACU_Pain_Rescue_Algorithm.md
├── 05_PACU_Handoff_Templates.md
├── 06_Surgeon_OnePage_Summary.md
├── 07_References_Evidence_2024.md
└── 08_Quick_Reference_Cards.md
```

---

## File Descriptions

### Pre-Operative Phase

**[`OR_Checklist_Pre-Induction.md`](OR_Checklist_Pre-Induction.md)**
Comprehensive OR readiness and safety checklist ensuring equipment integrity, medication preparation (including pathway-specific staging of midazolam, propofol, sevoflurane, ketamine, dexmedetomidine, magnesium), crisis preparedness, and team communication before patient arrival. Optimized for rTKA with ASA/APSF machine checkout standards.

**[`01_PreOp_Checklist.md`](01_PreOp_Checklist.md)**
ERAS-aligned pre-op checklist: identity verification, comorbidities, frailty/PONV risk assessment, anticoagulation timing (ASRA 2024–2025), pre-op medications (acetaminophen, celecoxib, dexamethasone, scopolamine, midazolam), block planning with ASRA timing verification, and transport readiness.

**[`02_Patient_Counseling_Script.md`](02_Patient_Counseling_Script.md)**
Patient-facing script and FAQ explaining all three pathways in plain language, including midazolam anxiolysis, spinal vs GA options, shared decision-making prompts, and documentation reminders. Includes special population considerations (elderly, OSA, anxiety).

### Intra-Operative Protocols

**Directory:** [`03_Anesthesia_Protocols/`](03_Anesthesia_Protocols/) (see its `README.md` for full detail)

* **`Protocol_1_ACB_IPACK_OFIA.md`** – OFIA + ACB/IPACK framework with midazolam, sevoflurane/propofol options, and multimodal adjuncts.
* **`Protocol_2_BlockFree_OFIA.md`** – OFIA without nerve blocks, using surgeon periarticular infiltration with multimodal adjunct options.
* **`Protocol_3_OpioidBased.md`** – Conventional opioid-inclusive framework for chronic opioid use, severe anxiety, or OFIA contraindications.
* **`Protocol_Medication_Dosing_and_Timing.md`** – Weight-based dosing ranges, onset/offset timing, and sequencing for all pathways.
* **`Protocol_Adjuncts_and_Contraindications.md`** – Contraindications and safety notes for adjuncts and techniques; special population adjustments.
* **`Protocol_Quick_Reference_Cards.md`** – Laminated quick reference card with core doses, rescue strategies, and pathway selection criteria.
* **`Protocol_Comparison_Table.md`** – Side-by-side pathway comparison designed to reduce cognitive load and standardize communication.

### Intra-Operative Decision Support

**Directory:** [`04_IntraOp_Flowcharts/`](04_IntraOp_Flowcharts/)

* **`Spinal_vs_GA_Decision.md`** – Decision pathway for spinal vs general anesthesia incorporating anticoagulation timing, anatomy, patient preference, hemodynamics, and airway assessment.
* **`PACU_Pain_Rescue_Algorithm.md`** – Stepwise PACU pain management algorithm; pathway-specific expectations and escalation criteria.

### PACU & Team Communication

**[`05_PACU_Handoff_Templates.md`](05_PACU_Handoff_Templates.md)**
Standardized handoff templates for each pathway with explicit statement of pathway, blocks, hypnotic strategy, adjuncts used, pain expectations, rescue options, and monitoring needs (including high-risk populations).

**[`06_Surgeon_OnePage_Summary.md`](06_Surgeon_OnePage_Summary.md)**
Surgeon-facing overview of all pathways with key workflow messages, expected pain ranges, mobilization expectations, and block/infiltration considerations.

### Evidence Base & Quick Reference

**[`07_References_Evidence_2024.md`](07_References_Evidence_2024.md)**
Vancouver-style bibliography and evidence grading for protocol decisions (regional techniques, multimodal adjuncts, PONV/delirium mitigation, and perioperative safety publications).

**[`08_Quick_Reference_Cards.md`](08_Quick_Reference_Cards.md)**
Badge-card format quick reference with all pathways side-by-side, induction/maintenance outlines, adjunct dosing ranges, PACU rescue strategy, and universal safety reminders.

---

## Key Protocol Features

### Standard Medications Across All Pathways

**Anxiolysis:**

* **Midazolam 1–2 mg IV** – Standard anxiolytic with rapid onset and reliable amnesia. Reduce dose in elderly/frail patients.

**Maintenance (Practitioner Choice):**

* **Sevoflurane 0.8–1.2 MAC**
  Preferred volatile agent for titratability and familiarity within orthopedic workflows.
* **Propofol TIVA 75–150 mcg/kg/min**
  Consider for high PONV risk, MH susceptibility, or institutional preference; requires appropriate infusion setup.

**Multimodal Analgesia Foundation (All Pathways):**

* Acetaminophen, NSAID strategy (per institutional policy), dexamethasone (PONV + analgesic synergy), ondansetron near emergence, and other antiemetic measures based on PONV risk.

### Pharmacologic Updates (2023–2025)

**Removed from Routine Use:**

* **Gabapentinoids** – Removed from standard pathways due to sedation/delirium/respiratory risk signals in older arthroplasty populations with limited incremental analgesic benefit in modern multimodal regimens. Reserve for patients already taking them chronically for other indications.

**Standardized Across Pathways:**

* Midazolam anxiolysis (dose-reduced in elderly/frail)
* Sevoflurane or propofol maintenance options
* Multimodal non-opioid foundation (acetaminophen/NSAID/dexamethasone/antiemetics)

**Adjuncts (Selection-Dependent):**

* **Magnesium sulfate** as NMDA-adjunct (dose per institutional standards and patient factors)
* **Dexmedetomidine infusion** (avoid large bolus loading in hemodynamically fragile patients; dose-reduce in elderly/frail)
* **Ketamine (optional sub-anesthetic adjunct analgesic; not a default primary induction agent):** OFIA pathways may include a **low-dose bolus for analgesia/opioid-sparing** (typical range 0.2–0.5 mg/kg IV titrated to effect) and, when used, an infusion (typical range 0.1–0.25 mg/kg/hr; lower end favored in elderly/frail). Use is **patient- and hemodynamics-dependent** and may be omitted when risk outweighs benefit.

---

## Ketamine Guardrails (Patient Selection, Hemodynamics, and Depth Monitoring)

Ketamine is presented here as an **optional adjunct** for opioid-sparing analgesia. Its effects are **context-dependent** and it should not be treated as universally "hemodynamically protective."

**Use caution, reduce dose, or omit** ketamine bolus/infusion when any of the following are present (non-exhaustive):

* **Hemodynamic instability** or escalating vasopressor requirement; suspected **catecholamine-depleted physiology**
* **Frailty / advanced age** (e.g., higher ASA class, limited physiologic reserve) where hypotension, delirium, or prolonged recovery risk is elevated
* Clinically significant **tachyarrhythmia risk** or contexts where sympathetic stimulation may be undesirable
* Severe psychiatric disease with active psychosis (context-dependent)

**Depth monitoring caveat (BIS/EEG):** Ketamine can **increase BIS** and alter EEG-derived indices in ways that may not reflect inadequate hypnosis. Avoid titrating hypnotics solely to BIS values after ketamine; correlate with clinical context and, when available, raw EEG trends.

---

## Safety & Quality Measures (Selected)

* **LAST preparedness:** lipid emulsion immediately available wherever blocks are performed; team familiarity with LAST recognition and response.
* **Anticoagulation safety:** deep peripheral blocks follow updated ASRA timing guidance; anticoagulation status and timing must be documented explicitly.
* **PACU rescue approach:** OFIA pathways can use ketamine as first-line rescue in appropriate patients, with escalation to opioids as clinically indicated; dose-reduce in elderly/frail and monitor closely in OSA/respiratory disease.
* **Dexmedetomidine bradycardia/hypotension:** dose-reduce in elderly/frail; treat symptomatic bradycardia per local practice (e.g., glycopyrrolate) and discontinue/reduce infusion if recurrent.

---

## Pathway Comparison

| Feature                  | Pathway 1: OFIA + Blocks                                   | Pathway 2: OFIA No Blocks                                                  | Pathway 3: Opioid-Based                            |
| ------------------------ | ---------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------- |
| **Anxiolysis**           | Midazolam 1–2 mg IV (dose-reduce in elderly/frail)         | Midazolam 1–2 mg IV (dose-reduce in elderly/frail)                         | Midazolam 1–2 mg IV (dose-reduce in elderly/frail) |
| **Maintenance**          | Sevoflurane 0.8–1.2 MAC OR Propofol TIVA 75–150 mcg/kg/min | Sevoflurane 0.8–1.2 MAC OR Propofol TIVA 75–150 mcg/kg/min                 | Sevoflurane 0.8–1.2 MAC (Propofol TIVA optional)   |
| **Intra-op opioids**     | None (opioid rescue remains available post-op if needed)   | None (opioid rescue remains available post-op if needed)                   | Fentanyl/hydromorphone per clinician judgment      |
| **Regional techniques**  | ACB + IPACK                                                | None (surgeon periarticular infiltration)                                  | Optional ACB + IPACK                               |
| **Adjuncts**             | Selection-dependent (e.g., ketamine/dexmed/magnesium)      | Selection-dependent (e.g., ketamine/dexmed/magnesium ± lidocaine infusion) | Adjuncts per clinician judgment                    |
| **Analgesia quality**    | Excellent                                                  | Good                                                                       | Variable                                           |
| **PONV risk**            | Minimal–Low                                                | Low                                                                        | Moderate–High                                      |
| **Delirium risk**        | Lower (opioid-sparing)                                     | Low–Moderate (patient dependent)                                           | Higher (opioid exposure, especially elderly)       |
| **PACU rescue strategy** | Multimodal rescue → opioids if needed                      | Multimodal rescue → opioids if needed                                      | Opioids primary with multimodal foundation         |

---

## Implementation Guide for Institutions

This section outlines a conceptual roadmap if a site chooses to adapt these ideas (with full local review and approval).

1. **Preparation:** multidisciplinary team formation; workflow readiness; pharmacy and PACU alignment.
2. **Local adaptation:** adjust doses/agents per formulary and patient population; align with local policies and credentialing.
3. **Education:** clinician and PACU training on pathway selection, adjunct monitoring, and rescue escalation.
4. **Pilot evaluation:** track pain, MME consumption, PONV, mobilization, delirium, LOS, adverse events.
5. **Scale/QI:** refine and periodically re-review as evidence and local outcomes evolve.

---

## Target Audience

**Primary:**

* Anesthesiology residents and fellows
* CRNAs and attending anesthesiologists
* Researchers designing comparative effectiveness or implementation studies

**Secondary:**

* Medical students exploring anesthesiology and perioperative medicine
* Orthopedic surgeons interested in multimodal analgesia and ERAS

---

## Scope and Disclaimer

### Project Scope

This repository is a **literature synthesis and protocol design project**, created to:

* Demonstrate evidence-based perioperative reasoning
* Provide an example of structured protocol documentation
* Facilitate discussion around multimodal and opioid-sparing strategies in rTKA

### Critical Disclaimers

**These materials have NOT been:**

* Prospectively validated in clinical practice
* Reviewed or approved by any IRB, P&T committee, perioperative leadership, or hospital governance body
* Adopted as official policy by any institution
* Tested across diverse patient populations or practice environments

**Any clinical use would require:**

* Formal review and adaptation by supervising anesthesiologists and relevant committees
* Institutional approval through appropriate governance channels (QI/P&T/perioperative leadership; IRB where applicable)
* Compliance with local policies, credentialing requirements, and regulatory standards
* Ongoing monitoring, data collection, and quality review

This repository does **not** constitute medical advice and must **not** be used for patient care without appropriate validation and oversight.

---

## Limitations and Future Directions

### Current Limitations

- No formal cost-effectiveness analysis
- Not tailored to any specific EHR or order-entry system
- Flowcharts are conceptual and intended for educational use only
- No prospective validation or clinical trial data
- Evidence synthesis represents author's interpretation of published literature

### Future Directions

**For institutional implementation (requires governance approval):**
- Pilot implementation with quality improvement or IRB oversight
- Multi-center validation studies
- EHR order-set integration only after local governance approval
- Extension to other arthroplasty procedures and surgical populations

**For ongoing educational development:**
- Continuous evidence updates for OFIA adjuncts and monitoring considerations
- Incorporation of emerging guidelines and safety communications
- Refinement based on peer feedback and literature review

---

## References

Complete Vancouver-style references are provided in:  
[`07_References_Evidence_2024.md`](07_References_Evidence_2024.md)

---

## Author Information

**Author:** Collin B. George, BS  
**Project Type:** Independent pre-medical research and educational portfolio  
**Educational Context:** Literature synthesis informed by clinical observation at University of Washington Medical Center  
**Status:** Preparing for medical school matriculation 2026

**GitHub:** [github.com/collingeorge](https://github.com/collingeorge)  
**License:** CC BY 4.0

---

## Acknowledgments

This educational framework was informed by:

**Professional Guidelines:**
- ERAS Society arthroplasty publications
- ASRA practice advisories on regional anesthesia safety
- ASA/APSF safety communications on perioperative risk management

**Clinical Education:**
The author is grateful to University of Washington faculty and staff for clinical observation opportunities and mentorship that informed this educational work.

**Note:** Clinical observation informed educational learning. This does not constitute institutional collaboration or endorsement of this project.

---

## Contributing and Feedback

This is a living educational document. Constructive feedback is welcome:

- **Issues:** Open a GitHub issue for corrections or suggestions
- **Pull Requests:** Submit proposed edits or improvements
- **Discussions:** Use GitHub Discussions for questions

**Note:** This repository is not seeking clinical implementation partners. Feedback is welcome for educational improvement only.

---

## Citation

If you reference this work in presentations or academic writing:
```text
George CB. Multimodal and Opioid-Free Intraoperative Anesthesia Framework 
for Robot-Assisted Total Knee Arthroplasty (rTKA). GitHub Repository. 
Version 2.2. Published December 2025. Available from: 
https://github.com/collingeorge/rTKA-Multimodal-Anesthesia-Protocol 
[Accessed: date]
```

---

## License

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

**You are free to:**
- Share and redistribute the material in any medium or format
- Adapt, remix, transform, and build upon the material for any purpose

**Under the following terms:**
- **Attribution:** Give appropriate credit to Collin B. George, provide a link to the license, and indicate if changes were made
- Do not suggest that the author or any institution endorses you or your use

**Full license:** https://creativecommons.org/licenses/by/4.0/

© 2025 Collin B. George — Licensed under CC BY 4.0

---

## Contribute

We welcome contributions to improve this educational framework:

* Open issues for evidence updates or clarity improvements
* Submit pull requests for refinements
* Fork for local adaptation with appropriate attribution and governance review

All contributions should maintain the educational and evidence-based nature of this project.

---

## Changelog

### Version 1.2 (December 7, 2025)

* Added comprehensive OR readiness checklist (`OR_Checklist_Pre-Induction.md`)
* Standardized midazolam anxiolysis dosing across pathways (dose-reduce in elderly/frail)
* Clarified maintenance options (sevoflurane vs propofol TIVA)
* Expanded safety notes (dexmedetomidine bradycardia/hypotension management; special populations)
* Enhanced quick reference materials and handoff templates
* Evidence current through December 7, 2025; next planned review June 2026 or sooner if major guidance changes occur

### Version 1.1 (December 3, 2025)

* Added medication dosing/timing, adjuncts/contraindications, and protocol quick reference cards
* Expanded protocol directory README and images
* Clarified OFIA terminology and safety framing

### Version 1.0 (November 2025)

* Initial three-pathway educational framework release

---

**For questions about protocol content, evidence updates, or implementation concepts, please open a GitHub issue.**
