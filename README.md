# Multimodal Anesthesia Protocol for Robot-Assisted Total Knee Arthroplasty

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Version](https://img.shields.io/badge/Version-1.1-blue.svg)]()
[![Last Updated](https://img.shields.io/badge/Updated-December%202025-green.svg)]()
[![Evidence Base](https://img.shields.io/badge/Evidence-2023--2025-orange.svg)]()

## At a Glance

**What:**  
Evidence-based, three-pathway anesthesia framework for **robot-assisted total knee arthroplasty (rTKA)** with:

1. Opioid-free intraoperative anesthesia (OFIA) + ACB/IPACK (preferred ERAS pathway)  
2. Opioid-free intraoperative anesthesia without blocks (block-free alternative)  
3. Conventional opioid-inclusive anesthesia (fallback / special indications)

**Who:**  
Anesthesia trainees, medical students, CRNAs, attending anesthesiologists, QI teams, and researchers studying multimodal and opioid-sparing strategies in arthroplasty.

**Why:**  
To support **Enhanced Recovery After Surgery (ERAS)** implementation, reduce perioperative opioid exposure, preserve quadriceps strength, and optimize pain control, PONV rates, and time to mobilization in rTKA.

**Evidence:**  
Synthesized from **Level 1-2 evidence (2023-2025)** including RCTs, meta-analyses, and updated ERAS / ASRA / ASA / APSF guidance.

**Terminology Note:**  
"**Opioid-free anesthesia**" in this project refers specifically to **opioid-free intraoperative anesthesia (OFIA)**.  
Postoperative opioid rescue remains available when clinically indicated and **does not constitute pathway failure.**

---

## Table of Contents

- [Overview](#overview)  
- [Quick Start](#quick-start)  
- [How to Use This Repository](#how-to-use-this-repository)  
- [Three Standardized Pathways](#three-standardized-pathways)  
- [Repository Structure](#repository-structure)  
- [File Descriptions](#file-descriptions)  
- [Key Protocol Features](#key-protocol-features)  
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

- Opioid-free intraoperative anesthesia (OFIA)  
- Quadriceps-sparing regional techniques (ACB + IPACK)  
- Evidence-based pharmacologic adjuncts (ketamine, dexmedetomidine, magnesium, NSAIDs, acetaminophen)  
- Standardized pre-op, intra-op, PACU, and communication tools

The project is intentionally **educational and non-validated**: it is designed to showcase evidence synthesis and protocol development, not to function as an institutional order set.

---

## Quick Start

### For First-Time Users

1. **See the big picture:**  
   Start with the pathway overview image:  
   
   ![Pathway Overview](docs/images/pathway_overview.png "Figure 1: Overview of Three Anesthesia Pathways")

2. **Understand the three options:**  
   [`03_Anesthesia_Protocols/Protocol_Comparison_Table.md`](03_Anesthesia_Protocols/Protocol_Comparison_Table.md)

3. **Walk through the clinical workflow:**
   1. Pre-op checklist → [`01_PreOp_Checklist.md`](01_PreOp_Checklist.md)  
   2. Patient counseling → [`02_Patient_Counseling_Script.md`](02_Patient_Counseling_Script.md)  
   3. Choose a pathway → [`03_Anesthesia_Protocols/`](03_Anesthesia_Protocols/)  
   4. Intra-op decision support → [`04_IntraOp_Flowcharts/`](04_IntraOp_Flowcharts/)  
   5. PACU handoff → [`05_PACU_Handoff_Templates.md`](05_PACU_Handoff_Templates.md)

4. **Review evidence base:**  
   [`07_References_Evidence_2024.md`](07_References_Evidence_2024.md)

### For Educational Use

**Medical Students:**
- Read through `01` → `02` → `03` → `05` to see **end-to-end perioperative care** in rTKA
- Use `07_References_Evidence_2024.md` to see how protocols map back to primary literature

**Residents and CRNAs:**
- Use the comparison table and quick reference cards:  
  [`03_Anesthesia_Protocols/Protocol_Quick_Reference_Cards.md`](03_Anesthesia_Protocols/Protocol_Quick_Reference_Cards.md)
- Practice patient counseling with:  
  [`02_Patient_Counseling_Script.md`](02_Patient_Counseling_Script.md)

**Researchers / QI Teams:**
- Treat this as a **template for protocol design** and documentation  
- Adapt sections (with local approval) for QI projects or IRB-approved pilot studies

---

## How to Use This Repository

### Navigation by Clinical Workflow
```text
Clinical Workflow → Repository Files

Pre-Op Assessment    → 01_PreOp_Checklist.md
Patient Counseling   → 02_Patient_Counseling_Script.md
Protocol Selection   → 03_Anesthesia_Protocols/Protocol_Comparison_Table.md
Intra-Op Management  → 03_Anesthesia_Protocols/[selected pathway].md
                       03_Anesthesia_Protocols/Protocol_Medication_Dosing_and_Timing.md
                       03_Anesthesia_Protocols/Protocol_Adjuncts_and_Contraindications.md
                       04_IntraOp_Flowcharts/
PACU Handoff         → 05_PACU_Handoff_Templates.md
Team Coordination    → 06_Surgeon_OnePage_Summary.md
Evidence Review      → 07_References_Evidence_2024.md
```

### Downloading for Offline Use

**Clone the repository:**
```bash
git clone https://github.com/collingeorge/rTKA-Multimodal-Anesthesia-Protocol.git
```

**Or download as ZIP:**
- Click the green "Code" button → "Download ZIP"

### Printing for Binder / Pocket Reference

- Open any `.md` file in your browser → Print → Save as PDF
- Recommended print order:  
  `01 → 02 → 03/README → selected protocol(s) → 04 → 05 → 06 → 07`
- Quick-reference cards:  
  [`03_Anesthesia_Protocols/Protocol_Quick_Reference_Cards.md`](03_Anesthesia_Protocols/Protocol_Quick_Reference_Cards.md)  
  are designed for double-sided badge card printing

---

## Three Standardized Pathways

![Pathway Overview](docs/images/pathway_overview.png "Figure 1: Overview of Three Anesthesia Pathways")

*Figure 1: High-level overview of the three multimodal anesthesia pathways for rTKA*

1. **Pathway 1 – OFIA + ACB/IPACK (Preferred ERAS Pathway)**
   - Opioid-free intra-op
   - ACB + IPACK for quad-sparing, circumferential analgesia

2. **Pathway 2 – OFIA, No Blocks**
   - Opioid-free intra-op
   - Periarticular local anesthetic infiltration by surgeon

3. **Pathway 3 – Conventional Opioid-Inclusive Anesthesia**
   - Fentanyl / hydromorphone-based
   - Used for chronic opioid users, severe anxiety, or OFIA contraindications

---

## Repository Structure
```
rTKA-Multimodal-Anesthesia-Protocol/
├── README.md
├── docs/
│   └── images/
│       ├── pathway_overview.png
│       ├── spinal_vs_ga_flowchart.png
│       └── pacu_rescue_algorithm.png
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
│   ├── Spinal_vs_GA_Decision.md
│   └── PACU_Pain_Rescue_Algorithm.md
├── 05_PACU_Handoff_Templates.md
├── 06_Surgeon_OnePage_Summary.md
└── 07_References_Evidence_2024.md
```

---

## File Descriptions

### Pre-Operative Phase

**[`01_PreOp_Checklist.md`](01_PreOp_Checklist.md)**  
ERAS-aligned pre-op checklist: identity, comorbidities, frailty/PONV risk, anticoagulation timing (ASRA 2024), pre-op medications, block planning, and transport readiness.

**[`02_Patient_Counseling_Script.md`](02_Patient_Counseling_Script.md)**  
Patient-facing script and FAQ explaining all three pathways, shared decision-making prompts, and documentation reminders.

### Intra-Operative Protocols

**Directory:** [`03_Anesthesia_Protocols/`](03_Anesthesia_Protocols/) (see its README.md for full detail)

- **`Protocol_1_ACB_IPACK_OFIA.md`** - Full OFIA + ACB/IPACK protocol (first-line ERAS pathway)
- **`Protocol_2_BlockFree_OFIA.md`** - OFIA pathway without nerve blocks, using surgeon periarticular infiltration
- **`Protocol_3_OpioidBased.md`** - Conventional opioid-inclusive general or spinal anesthesia protocol
- **`Protocol_Medication_Dosing_and_Timing.md`** - Weight-based dosing ranges, onset/offset timing, and sequencing for all pathways
- **`Protocol_Adjuncts_and_Contraindications.md`** - Contraindication tables and safety notes for ketamine, dexmedetomidine, magnesium, lidocaine infusions, and ACB/IPACK (including ASRA 2024-2025 anticoagulation windows)
- **`Protocol_Quick_Reference_Cards.md`** - Double-sided quick reference card with core doses and rescue strategies
- **`Protocol_Comparison_Table.md`** - Single-page comparison of all three pathways (analgesia source, motor preservation, PONV risk, ideal patients, workflow)

### Intra-Operative Decision Support

**Directory:** [`04_IntraOp_Flowcharts/`](04_IntraOp_Flowcharts/)

- **`Spinal_vs_GA_Decision.md`** - Text-based decision pathway for choosing spinal vs general anesthesia (anticoagulation timing, anatomy, patient preference, hemodynamics)
- **`PACU_Pain_Rescue_Algorithm.md`** - Logical PACU algorithm for pain rescue (ketamine first-line for OFIA pathways, then escalation to opioids)

### PACU & Team Communication

**[`05_PACU_Handoff_Templates.md`](05_PACU_Handoff_Templates.md)**  
Standardized handoff structure for each pathway: expectations, infusions used, block status, rescue plans, and monitoring priorities.

**[`06_Surgeon_OnePage_Summary.md`](06_Surgeon_OnePage_Summary.md)**  
One-page, surgeon-facing overview of all three pathways, with key messages about mobilization, PONV, and workflow.

### Evidence Base

**[`07_References_Evidence_2024.md`](07_References_Evidence_2024.md)**  
Vancouver-style bibliography and evidence grading for the core protocol decisions (ACB/IPACK, OFIA, magnesium, ketamine, celecoxib, dexamethasone, lidocaine, ASRA timing, etc.).

---

## Key Protocol Features

### Pharmacologic Updates (2023-2025)

**Removed:**  
- Routine gabapentinoids (gabapentin/pregabalin) due to increased sedation, delirium, and respiratory depression in elderly TKA patients when modern multimodal regimens are used

**Standardized:**
- Celecoxib 400 mg PO pre-op (or equivalent COX-2 strategy)
- Dexamethasone 8-10 mg IV for antiemetic/analgesic effect
- Magnesium sulfate 30-50 mg/kg IV (typical 40 mg/kg) for analgesic and opioid-sparing effect
- Ketamine 0.3-0.5 mg/kg induction, 0.1-0.25 mg/kg/hr infusion
- Dexmedetomidine infusion 0.2-0.7 μg/kg/hr (lower range in elderly/frail), avoiding large bolus doses

### Regional Anesthesia

**Adductor Canal Block (ACB):**
- 20-30 mL ropivacaine 0.2-0.25%
- Quadriceps-sparing, preserving knee extension strength
- Anterior / medial knee analgesia

**IPACK Block:**
- 20 mL ropivacaine 0.2-0.25%
- Posterior capsule analgesia
- Combined with ACB → circumferential knee analgesia with minimal motor impairment

### Safety & Quality

- Anticoagulation timing aligned with ASRA 2024-2025 for deep peripheral and neuraxial techniques
- PACU pain rescue algorithm emphasizing ketamine first, opioids second on OFIA pathways
- Explicit contraindications and cautions for OFIA adjuncts (e.g., psych history, AV block, renal impairment)
- Structured handoffs and checklists to reduce communication failures

---

## Pathway Comparison

| Feature | Pathway 1: OFIA + Blocks | Pathway 2: OFIA No Blocks | Pathway 3: Opioid-Based |
|---------|-------------------------|--------------------------|------------------------|
| Intra-op opioids | None | None | Yes |
| Regional techniques | ACB + IPACK | None (surgeon infiltration) | Optional |
| Analgesia quality | Excellent | Good | Good |
| Quadriceps strength | Preserved | Not targeted | Variable |
| PONV risk | Minimal | Low | Moderate-High |
| Typical mobilization | Same-day | Same-day | Often delayed |
| Workflow complexity | Moderate (blocks) | Low | Low |
| Ideal use case | ERAS optimization | Block contraindication/refusal | Chronic opioid use / OFIA contraindication |

---

## Implementation Guide for Institutions

This section outlines a conceptual roadmap if a site chooses to adapt these ideas (with full local review and approval).

### Phase 1: Preparation
- Assemble multidisciplinary team (anesthesia, ortho, PACU, pharmacy, QI)
- Assess readiness: ultrasound availability, formulary, block training, PACU familiarity with ketamine/dexmedetomidine

### Phase 2: Local Adaptation
- Adjust medication choices and doses to formulary and institutional norms
- Customize flowcharts and handoff templates to local EHR and order sets
- Obtain appropriate departmental / P&T / QI or IRB approvals

### Phase 3: Education
- Train anesthesia team on ACB/IPACK and OFIA adjuncts
- Educate PACU nurses on OFIA patients and ketamine rescue
- Brief surgeons on workflow, periarticular infiltration, and expectations

### Phase 4: Pilot & Evaluation
- Start with a small pilot (e.g., 20-30 primary unilateral rTKA cases)
- Track pain scores, opioid consumption, PONV, mobilization time, PACU LOS, and adverse events
- Compare to historical or conventional pathway outcomes

### Phase 5: Scale Up & Continuous QI
- Refine protocols based on pilot data
- Scale to broader patient populations if outcomes are favorable
- Reassess data at regular intervals; update based on new evidence

Suggested audit metrics and committee engagement strategies are described in more detail in the original comprehensive README sections and can be adapted as needed.

---

## Target Audience

**Primary:**
- Anesthesiology residents and fellows
- CRNAs and attending anesthesiologists
- QI teams working on ERAS and opioid-sparing programs

**Secondary:**
- Medical students exploring anesthesiology / perioperative medicine
- Orthopedic surgeons interested in multimodal analgesia planning
- Researchers designing trials or implementation studies in arthroplasty anesthesia

---

## Scope and Disclaimer

### Project Scope

This repository is a literature synthesis and protocol development project, created to:
- Demonstrate evidence-based clinical reasoning
- Provide an example of structured perioperative protocol design
- Facilitate discussion around multimodal and opioid-sparing anesthesia strategies in rTKA

### Critical Disclaimers

**These materials have NOT been:**
- Prospectively validated in clinical practice
- Reviewed or approved by any IRB or institutional committee
- Adopted as official hospital policy
- Tested across diverse patient populations or practice settings

**Any clinical use would require:**
- Formal review and adaptation by supervising anesthesiologists
- Institutional approval through QI / IRB and appropriate governance
- Compliance with local policies, credentialing, regulatory requirements
- Ongoing monitoring and outcome assessment

This repository does not constitute medical advice and must not be used for patient care without appropriate validation and oversight.

---

## Limitations and Future Directions

### Current Limitations

- No prospective clinical outcomes yet associated with these exact pathways
- No cost-effectiveness or resource utilization analysis performed
- Not tailored to specific EHR systems or local formularies
- Flowchart images (spinal_vs_ga_flowchart.png, pacu_rescue_algorithm.png) are placeholders for institution-specific graphics

### Future Directions

- Single-center pilot implementation with IRB or QI approval
- Multi-center validation and comparative effectiveness studies
- Integration into EHR-based order sets and decision support tools
- Expansion to other arthroplasty procedures (hip, shoulder)

Collaboration and feedback are welcome via GitHub issues and pull requests.

---

## References

Complete Vancouver-style references are provided in:  
[`07_References_Evidence_2024.md`](07_References_Evidence_2024.md)

Selected key references include:

1. Memtsoudis SG, et al. Multimodal pain management in joint arthroplasty. Anesthesiology. 2023.
2. Soffin EM, et al. Perioperative opioid-sparing strategies in total joint arthroplasty. Anesth Analg. 2023.
3. Thacher RR, et al. ACB + IPACK for rTKA. J Bone Joint Surg Am. 2022.
4. ASRA Guidelines on antiplatelet and anticoagulant medications. Reg Anesth Pain Med. 2024.

(See `07_References_Evidence_2024.md` for full list and evidence grading.)

---

## Author and Contact

**Author:** Collin George  
**Affiliation:** UW Medical Center (personal project; not an official UW document)

This work was developed as part of a medical school application and academic portfolio, demonstrating independent literature review, protocol design, and ERAS-aligned perioperative thinking.

**For feedback or collaboration:**
- Open a GitHub issue on this repository
- Or submit a pull request with proposed edits

---

## Acknowledgments

This protocol framework was informed by:
- ERAS Society hip and knee arthroplasty guidelines
- American Society of Regional Anesthesia and Pain Medicine (ASRA) practice advisories
- ASA and APSF guidance on perioperative safety and opioid stewardship
- Ongoing contributions from clinicians and researchers advancing opioid-sparing arthroplasty care

---

## Citation

If you reference this work in presentations or academic writing:
```
George C. Multimodal & Opioid-Free Anesthesia Protocol for 
Robot-Assisted Total Knee Arthroplasty. GitHub repository.
https://github.com/collingeorge/rTKA-Multimodal-Anesthesia-Protocol
Accessed [date].
```

---

## License

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made

**Important:**  
The CC BY 4.0 license covers the educational content only and does not authorize direct clinical use without appropriate institutional validation and approval.

Full license text: https://creativecommons.org/licenses/by/4.0/

---

## Contribute

We welcome contributions to improve this protocol framework:

- **Open issues** for evidence updates or suggestions
- **Submit pull requests** for refinements (e.g., local adaptations, clarity improvements)
- **Fork the repository** for institutional customization with appropriate attribution

All contributions should maintain the educational and evidence-based nature of this project.

---

## Changelog

### Version 1.1 (December 03, 2025)

**Added:**
- `Protocol_Medication_Dosing_and_Timing.md`
- `Protocol_Adjuncts_and_Contraindications.md`
- `Protocol_Quick_Reference_Cards.md`
- Expanded `03_Anesthesia_Protocols/README.md` to describe all seven protocol-related files
- Added images directory and `pathway_overview.png`
- Clarified OFIA terminology and safety framing
- Evidence current through December 2025
- Next planned evidence review: June 2026

### Version 1.0 (November 2025)

**Initial Release:**
- Initial three-pathway protocol framework
- Pre-op checklist, counseling script, three anesthesia protocols, comparison table
- Basic intra-op flowcharts, PACU handoff templates, surgeon one-page summary
- Evidence synthesis through January 2026

---

**For questions about protocol content, evidence updates, or implementation concepts, please open a GitHub issue.**
