# Multimodal Anesthesia Protocol for Robot-Assisted Total Knee Arthroplasty

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Version](https://img.shields.io/badge/Version-1.2-blue.svg)]()
[![Last Updated](https://img.shields.io/badge/Updated-December%207%2C%202025-green.svg)]()
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
Synthesized from **Level 1-2 evidence (2023-2025)** including RCTs, meta-analyses, and updated ERAS / ASRA / ASA / APSF guidance. **Incorporates clinical practice feedback from Drs. Shane Mandalia, Dr. Pauldine, and Chief CRNA Brian Buchanan** regarding standard anesthetic practices including midazolam anxiolysis, sevoflurane/propofol maintenance, and multimodal adjunct dosing.

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
- **Standard anxiolytic and maintenance agents (midazolam, sevoflurane, propofol) per clinical consensus**
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
   1. **OR Checklist** [`OR_Checklist_Pre-Induction.md`](OR_Checklist_Pre-Induction.md) - **Comprehensive pre-case safety verification**
   2. Pre-op checklist → [`01_PreOp_Checklist.md`](01_PreOp_Checklist.md)  
   3. Patient counseling → [`02_Patient_Counseling_Script.md`](02_Patient_Counseling_Script.md)  
   4. Choose a pathway → [`03_Anesthesia_Protocols/`](03_Anesthesia_Protocols/)  
   5. Intra-op decision support → [`04_IntraOp_Flowcharts/`](04_IntraOp_Flowcharts/)  
   6. PACU handoff → [`05_PACU_Handoff_Templates.md`](05_PACU_Handoff_Templates.md)

4. **Review evidence base:**  
   [`07_References_Evidence_2024.md`](07_References_Evidence_2024.md)

### For Educational Use

**Medical Students:**
- Read through `OR_Checklist` → `01` → `02` → `03` → `05` to see **end-to-end perioperative care** in rTKA
- Use `07_References_Evidence_2024.md` to see how protocols map back to primary literature
- Review `OR_Checklist_Pre-Induction.md` to understand comprehensive pre-case safety verification

**Residents and CRNAs:**
- Use the comparison table and quick reference cards:  
  [`03_Anesthesia_Protocols/Protocol_Quick_Reference_Cards.md`](Protocol_Quick_Reference_Cards.md)
- Practice patient counseling with:  
  [`02_Patient_Counseling_Script.md`](02_Patient_Counseling_Script.md)
- Master pre-case setup with:
  [`OR_Checklist_Pre-Induction.md`](OR_Checklist_Pre-Induction.md)
- Review pathway-specific medication dosing:
  [`03_Anesthesia_Protocols/Protocol_Medication_Dosing_and_Timing.md`](03_Anesthesia_Protocols/Protocol_Medication_Dosing_and_Timing.md)

**Researchers / QI Teams:**
- Treat this as a **template for protocol design** and documentation  
- Adapt sections (with local approval) for QI projects or IRB-approved pilot studies
- Use structured outcome metrics for comparative effectiveness studies

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
- Click the green "Code" button → "Download ZIP"

### Printing for Binder / Pocket Reference

- Open any `.md` file in your browser → Print → Save as PDF
- Recommended print order:  
  `OR_Checklist → 01 → 02 → 03/README → selected protocol(s) → 04 → 05 → 06 → 07 → 08`
- Quick-reference cards:  
  [`08_Quick_Reference_Cards.md`](08_Quick_Reference_Cards.md)  
  are designed for double-sided badge card printing and lamination

---

## Three Standardized Pathways

![Pathway Overview](docs/images/pathway_overview.png "Figure 1: Overview of Three Anesthesia Pathways")

*Figure 1: High-level overview of the three multimodal anesthesia pathways for rTKA*

### Pathway 1 – OFIA + ACB/IPACK (Preferred ERAS Pathway)
- Opioid-free intra-op with **midazolam anxiolysis (1-2 mg IV)**
- ACB + IPACK for quad-sparing, circumferential analgesia (ropivacaine 0.2-0.25%)
- **Maintenance:** Sevoflurane 0.8-1.2 MAC OR propofol TIVA 75-150 mcg/kg/min
- **Expected PACU pain:** 0-3/10 (excellent analgesia from blocks)
- **Benefits:** Minimal PONV, preserved motor function, same-day mobilization

### Pathway 2 – OFIA, No Blocks
- Opioid-free intra-op with **midazolam anxiolysis (1-2 mg IV)**
- Periarticular local anesthetic infiltration by surgeon (100-150 mL ropivacaine 0.2%)
- **Maintenance:** Sevoflurane 0.8-1.2 MAC OR propofol TIVA 75-150 mcg/kg/min
- **Expected PACU pain:** 3-6/10 (good analgesia, higher than with blocks)
- **Benefits:** Fast workflow, no block contraindications, low PONV

### Pathway 3 – Conventional Opioid-Inclusive Anesthesia
- Fentanyl/hydromorphone-based with **midazolam anxiolysis (1-2 mg IV)**
- **Maintenance:** Sevoflurane 0.8-1.2 MAC + opioid boluses PRN
- Optional ACB/IPACK for improved analgesia
- **Expected PACU pain:** Variable (2-6/10 depending on blocks)
- **Indications:** Chronic opioid use, severe anxiety, OFIA contraindications

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
├── OR_Checklist_Pre-Induction.md ← NEW
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
Comprehensive OR readiness and safety checklist ensuring equipment integrity, medication preparation (including **pathway-specific staging of midazolam, propofol, sevoflurane, ketamine, dexmedetomidine, magnesium**), crisis preparedness, and team communication before patient arrival. **Optimized for rTKA with ASA/APSF machine checkout standards.**

**[`01_PreOp_Checklist.md`](01_PreOp_Checklist.md)**  
ERAS-aligned pre-op checklist: identity verification, comorbidities, frailty/PONV risk assessment, anticoagulation timing (ASRA 2024-2025), pre-op medications (acetaminophen, celecoxib, dexamethasone, scopolamine, **midazolam**), block planning with ASRA timing verification, and transport readiness.

**[`02_Patient_Counseling_Script.md`](02_Patient_Counseling_Script.md)**  
Patient-facing script and FAQ explaining all three pathways with plain language, **including midazolam anxiolysis explanation, spinal vs GA options**, shared decision-making prompts, and comprehensive documentation reminders. Includes special population considerations (elderly, OSA, anxiety).

### Intra-Operative Protocols

**Directory:** [`03_Anesthesia_Protocols/`](03_Anesthesia_Protocols/) (see its README.md for full detail)

- **`Protocol_1_ACB_IPACK_OFIA.md`** - Full OFIA + ACB/IPACK protocol with **midazolam, sevoflurane/propofol, ketamine, dexmedetomidine, magnesium** (first-line ERAS pathway with best evidence for pain control and early mobilization)

- **`Protocol_2_BlockFree_OFIA.md`** - OFIA pathway without nerve blocks, using surgeon periarticular infiltration with **midazolam, sevoflurane/propofol, higher-dose ketamine, optional lidocaine infusion** (for anticoagulation contraindications or patient refusal of blocks)

- **`Protocol_3_OpioidBased.md`** - Conventional opioid-inclusive protocol with **midazolam, sevoflurane, fentanyl/hydromorphone** (for chronic opioid users, severe anxiety, or OFIA contraindications)

- **`Protocol_Medication_Dosing_and_Timing.md`** - Comprehensive weight-based dosing ranges, onset/offset timing, and sequencing for all pathways including **midazolam 1-2 mg IV, propofol induction 1.5-2 mg/kg, propofol TIVA 75-150 mcg/kg/min, sevoflurane 0.8-1.2 MAC, ketamine, dexmedetomidine, magnesium**

- **`Protocol_Adjuncts_and_Contraindications.md`** - Detailed contraindication tables and safety notes for **midazolam, sevoflurane, propofol**, ketamine, dexmedetomidine, magnesium, lidocaine infusions, and ACB/IPACK with ASRA 2024-2025 anticoagulation timing windows, LAST preparedness, and special population dose adjustments

- **`Protocol_Quick_Reference_Cards.md`** - Double-sided laminated quick reference card with core doses, rescue strategies, and pathway selection criteria

### Intra-Operative Decision Support

**Directory:** [`04_IntraOp_Flowcharts/`](04_IntraOp_Flowcharts/)

- **`README.md`** - Directory overview, navigation guide, and key clinical principles for flowchart use

- **`Spinal_vs_GA_Decision.md`** - Comprehensive text-based decision pathway for choosing spinal vs general anesthesia incorporating anticoagulation timing (ASRA 2024), anatomical considerations, patient preference, hemodynamics, airway assessment, with **midazolam use for both approaches** and detailed technique sections (spinal dosing, GA induction)

- **`PACU_Pain_Rescue_Algorithm.md`** - Stepwise PACU pain management algorithm with pathway-specific expectations, ketamine first-line for OFIA pathways (0.1-0.15 mg/kg q10-15 min, max 3 doses), opioid escalation criteria, and **special population considerations** (elderly/frail, OSA, opioid-tolerant with specific dose adjustments)

### PACU & Team Communication

**[`05_PACU_Handoff_Templates.md`](05_PACU_Handoff_Templates.md)**  
Standardized handoff templates for each pathway with clear section headers (no blockquotes for improved readability): patient identification, anesthesia type, **midazolam administration**, regional block details (volumes, sensory coverage, motor-sparing confirmation), intraoperative course with specific medication doses (**propofol/sevoflurane, ketamine, dexmedetomidine, magnesium**), analgesia expectations with NRS ranges, antiemetic strategy, current vital signs, anticipated issues (dexmedetomidine bradycardia, LAST risk), rescue plans, and disposition. Includes special considerations for elderly/frail, OSA, and anticoagulation patients.

**[`06_Surgeon_OnePage_Summary.md`](06_Surgeon_OnePage_Summary.md)**  
One-page, surgeon-facing overview of all three pathways with key messages about **midazolam use, sevoflurane/propofol maintenance options**, expected pain scores (NRS ranges), mobilization timing (POD 0 ambulation expectations), PONV profiles, periarticular infiltration technique for Pathway 2 (volume, concentration, additives), workflow considerations, ASRA anticoagulation timing requirements for blocks, and quick reference medication table.

### Evidence Base & Quick Reference

**[`07_References_Evidence_2024.md`](07_References_Evidence_2024.md)**  
Comprehensive Vancouver-style bibliography and evidence grading for all protocol decisions: ACB/IPACK efficacy and motor-sparing (Thacher 2022, Wang 2023), OFIA adjuncts (**midazolam pharmacology - Reves 1985**, **sevoflurane/propofol recovery profiles - Wachtel 2011**, ketamine dosing - Laskowski 2024, dexmedetomidine - Li 2023, magnesium - Chen 2023, lidocaine - Albrecht 2024), gabapentinoid avoidance rationale (Angst 2024, ASA/APSF 2024), multimodal analgesia (celecoxib, dexamethasone), ASRA 2024-2025 anticoagulation timing, LAST preparedness (Neal 2017), and PONV/delirium prevention. **Includes clinical practice integration section documenting standard medication evidence base.**

**[`08_Quick_Reference_Cards.md`](08_Quick_Reference_Cards.md)**  
Laminated pocket card format (fits badge holder) with all three pathways side-by-side, **including midazolam 1-2 mg IV, sevoflurane 0.8-1.2 MAC OR propofol TIVA 75-150 mcg/kg/min**, induction sequences, adjunct dosing (ketamine, dexmedetomidine, magnesium), emergence protocols (ondansetron, sugammadex), PACU rescue strategies, and universal safety reminders. Designed for point-of-care reference at anesthesia workstation.

---

## Key Protocol Features

### Standard Medications Across All Pathways

**Anxiolysis:**
- **Midazolam 1-2 mg IV** - Standard anxiolytic with rapid onset (1-3 min), short duration (30-60 min), excellent amnesia for block procedures. Does not compromise OFIA principles. Reduce to 1 mg in elderly/frail patients (>70 years, frailty index >0.3).

**Maintenance (Practitioner Choice):**
- **Sevoflurane 0.8-1.2 MAC** - Preferred volatile agent for ease of titration, favorable recovery profile, hemodynamic stability. Well-tolerated in cardiac patients. Vaporizer must be filled and locked pre-case.
  
- **Propofol TIVA 75-150 mcg/kg/min** - Preferred for total intravenous anesthesia approach. Benefits: lower PONV risk in highly susceptible patients, no volatile trigger for MH-susceptible patients, potentially faster emergence in some populations. Requires dedicated IV line and infusion pump. Consider remifentanil co-administration if opioid pathway selected.

**Selection Considerations:**
- **Choose Sevoflurane:** Standard cases, practitioner comfort, easier titration, established institutional workflow
- **Choose Propofol TIVA:** High PONV risk (STOP-Bang ≥3, female, non-smoker, history severe PONV), MH susceptibility, practitioner preference, research protocols comparing TIVA vs volatile

**Multimodal Analgesia Foundation:**
- Acetaminophen 1 g PO preop (30-60 min prior), then 1 g q6h postop
- Celecoxib 400 mg PO preop (1-2 hrs prior) or ketorolac 15 mg IV intraop
- Dexamethasone 8-10 mg IV (PONV prophylaxis + analgesic synergy)
- Ondansetron 4 mg IV near emergence (additional PONV prophylaxis)
- Scopolamine 1.5 mg patch (night before or ≥2 hrs preop for high PONV risk)

### Pharmacologic Updates (2023-2025)

**Removed from Routine Use:**  
- **Gabapentinoids (gabapentin/pregabalin)** - Removed based on 2024 evidence (Angst, Memtsoudis) and ASA/APSF guidance showing increased sedation, delirium, and respiratory depression in elderly TKA patients when combined with modern multimodal regimens. No additional analgesic benefit demonstrated. Reserved only for patients already on chronic gabapentinoid therapy for other indications.

**Standardized Across Pathways:**
- **Midazolam 1-2 mg IV** for anxiolysis (all pathways, all patients except severe frailty)
- **Sevoflurane 0.8-1.2 MAC OR Propofol TIVA 75-150 mcg/kg/min** for maintenance (practitioner and patient-specific selection)
- **Celecoxib 400 mg PO** preop (or institutional NSAID equivalent: ketorolac 15 mg IV, meloxicam 15 mg PO)
- **Dexamethasone 8-10 mg IV** for antiemetic and analgesic effect (not >10 mg - no additional benefit, unnecessary hyperglycemia risk)
- **Magnesium sulfate 30-50 mg/kg IV** (typical 40 mg/kg, ~3 g for 70 kg patient) over 15-20 min for NMDA antagonism and opioid-sparing
- **Ketamine** - OFIA pathways: induction 0.3-0.5 mg/kg, infusion 0.1-0.25 mg/kg/hr (higher end for block-free pathway)
- **Dexmedetomidine infusion 0.2-0.7 mcg/kg/hr** (lower range 0.2-0.4 in elderly/frail), optional loading 0.5 mcg/kg over 10-20 min, avoiding large bolus doses to minimize bradycardia/hypotension

### Regional Anesthesia Techniques

**Adductor Canal Block (ACB):**
- **Local anesthetic:** 20-30 mL ropivacaine 0.2-0.25% (typical 25 mL of 0.25% = 62.5 mg)
- **Target:** Subsartorial/vastoadductor compartment (below sartorius muscle)
- **Ultrasound guidance:** High-frequency linear probe (10-15 MHz), short-axis view of femoral artery at mid-thigh
- **Benefits:** Quadriceps-sparing (motor-sparing), preserving knee extension strength for early ambulation
- **Coverage:** Anterior and medial knee analgesia (saphenous nerve, nerve to vastus medialis)
- **Anxiolysis:** Midazolam 1-2 mg IV before block placement for patient comfort and amnesia
- **Documentation:** Sensory coverage (medial leg/foot), motor function testing (quad strength preserved)

**IPACK Block (Interspace between Popliteal Artery and Capsule of posterior Knee):**
- **Local anesthetic:** 20 mL ropivacaine 0.2-0.25% (typical 20 mL of 0.25% = 50 mg)
- **Target:** Between popliteal artery and posterior knee capsule
- **Ultrasound guidance:** Popliteal fossa, above joint line, infiltrate between artery and femur
- **Benefits:** Posterior capsule analgesia without sciatic nerve block (no foot drop risk)
- **Coverage:** Posterior knee pain (complement to ACB for circumferential analgesia)
- **Combined effect:** ACB + IPACK provides excellent analgesia with minimal motor impairment, enabling same-day ambulation (typically 4-6 hours post-op)

**Total Local Anesthetic Dose:**
- Combined ACB + IPACK: ~112.5 mg ropivacaine (well below max ~3 mg/kg = 210 mg for 70 kg patient)
- Document total dose for LAST risk assessment
- Lipid emulsion 20% must be immediately available

### Safety & Quality Measures

**LAST (Local Anesthetic Systemic Toxicity) Preparedness:**
- **Lipid emulsion 20% (100-250 mL)** immediately available in block area
- ASRA LAST protocol accessible (initial bolus 1.5 mL/kg lean body weight over 1 min, then infusion)
- Early recognition: perioral numbness, tinnitus, metallic taste, agitation, seizures, arrhythmias
- Resuscitation equipment ready: airway management, oxygen, suction, defibrillator

**Anticoagulation Safety (ASRA 2024-2025):**
- Deep peripheral blocks (ACB, IPACK) treated like neuraxial for timing
- **DOACs:** ≥72 hours off (CrCl >50 mL/min), ≥120 hours (CrCl <50 mL/min)
- **Dabigatran:** 72-120 hours depending on renal function
- **Therapeutic LMWH:** ≥24 hours off
- **Prophylactic LMWH:** ≥12 hours off
- **Warfarin:** INR ≤1.4
- **Antiplatelets:** Generally safe for peripheral blocks per ASRA
- Document anticoagulation status and timing in pre-op checklist

**PACU Pain Management Algorithm:**
- **Pathway 1 & 2 (OFIA):** Ketamine first-line rescue (0.1-0.15 mg/kg IV q10-15 min, max 3 doses = ~0.3-0.45 mg/kg total), then low-dose opioids (hydromorphone 0.2 mg IV) only if inadequate
- **Pathway 3 (Opioid-based):** Hydromorphone 0.2 mg IV q10-15 min PRN with careful titration and respiratory monitoring
- **Special populations:** Reduce doses by 50% in elderly/frail, enhanced monitoring for OSA (continuous pulse ox, consider capnography)

**Dexmedetomidine-Related Bradycardia Management:**
- **Glycopyrrolate 0.2-0.4 mg IV** preferred over atropine (longer duration, less tachycardia, less CNS penetration)
- Treat if HR <50 with symptoms (hypotension, dizziness, chest discomfort) or HR <45 regardless of symptoms
- Stop dexmedetomidine 10-15 min before emergence to allow clearance

**Communication & Handoff:**
- Structured handoffs using standardized templates reduce communication failures
- Pre-induction huddle with surgeon/CRNA/circulator: pathway selection, blocks, tourniquet plan, periarticular infiltration, disposition
- PACU handoff includes: pathway used, midazolam/propofol/sevoflurane details, block quality, pain expectations, rescue plans, special monitoring needs

---

## Pathway Comparison

| Feature | Pathway 1: OFIA + Blocks | Pathway 2: OFIA No Blocks | Pathway 3: Opioid-Based |
|---------|-------------------------|--------------------------|------------------------|
| **Anxiolysis** | Midazolam 1-2 mg IV | Midazolam 1-2 mg IV | Midazolam 1-2 mg IV |
| **Maintenance** | Sevoflurane 0.8-1.2 MAC OR Propofol TIVA 75-150 mcg/kg/min | Sevoflurane 0.8-1.2 MAC OR Propofol TIVA 75-150 mcg/kg/min | Sevoflurane 0.8-1.2 MAC (propofol TIVA optional) |
| **Intra-op opioids** | None | None | Fentanyl 1-2 mcg/kg OR Hydromorphone 0.2-0.4 mg |
| **Regional techniques** | ACB + IPACK (ropivacaine 0.2-0.25%) | None (surgeon infiltration 100-150 mL ropivacaine 0.2%) | Optional ACB + IPACK |
| **OFIA adjuncts** | Ketamine, dexmedetomidine, magnesium | Ketamine (higher dose), dexmedetomidine, magnesium, optional lidocaine infusion | Not routinely used |
| **Analgesia quality** | Excellent (NRS 0-3/10) | Good (NRS 3-6/10) | Good (variable, NRS 2-6/10) |
| **Block duration** | 12-18 hours | N/A (infiltration 6-8 hours) | 12-18 hours if blocks done |
| **Quadriceps strength** | Preserved (motor-sparing) | Full (no blocks) | Preserved if ACB done, full if no blocks |
| **PONV risk** | Minimal (<10% incidence) | Low (10-20% incidence) | Moderate-High (30-40% incidence) |
| **Delirium risk** | Lowest (opioid-free) | Low | Higher (opioid-related) |
| **Typical mobilization** | Same-day (4-6 hrs post-op) | Same-day (may require more analgesia) | Often delayed (sedation/PONV) |
| **Workflow complexity** | Moderate (block time ~15 min) | Low (no block room) | Low |
| **PACU rescue** | Ketamine → opioids | Ketamine → opioids | Opioids primary |
| **Ideal use case** | ERAS optimization, opioid-naïve, elderly, high PONV risk | Block contraindication (anticoagulation), patient refusal, rapid workflow | Chronic opioid use (>30 MME/day), severe anxiety, OFIA contraindications |

---

## Implementation Guide for Institutions

This section outlines a conceptual roadmap if a site chooses to adapt these ideas (with full local review and approval).

### Phase 1: Preparation
- Assemble multidisciplinary team (anesthesia, ortho, PACU, pharmacy, QI)
- Assess readiness: ultrasound availability, formulary, block training, PACU familiarity with ketamine/dexmedetomidine
- Review **midazolam and sevoflurane** availability and institutional protocols

### Phase 2: Local Adaptation
- Adjust medication choices and doses to formulary and institutional norms
- Customize flowcharts and handoff templates to local EHR and order sets
- **Integrate midazolam anxiolysis and sevoflurane maintenance** into existing workflows
- Obtain appropriate departmental / P&T / QI or IRB approvals

### Phase 3: Education
- Train anesthesia team on ACB/IPACK and OFIA adjuncts
- Educate PACU nurses on OFIA patients and ketamine rescue
- Brief surgeons on workflow, periarticular infiltration, and expectations
- **Clarify that midazolam does not compromise OFIA principles**

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
- **Incorporate standard anesthetic practices (midazolam anxiolysis, sevoflurane maintenance) per clinical consensus**

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
- **Ongoing evidence updates** for midazolam, sevoflurane, and OFIA adjuncts

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
5. **Reves JG, et al. Midazolam: pharmacology and uses. Anesthesiology. 1985.** ← **NEW**
6. **Wachtel RE, et al. Meta-analysis of desflurane and propofol for recovery profiles. Anesth Analg. 2011.** ← **NEW**

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
- **Clinical practice feedback from Drs. Shane Mandalia, Dr. Pauldine, and Chief CRNA Brian Buchanan** regarding standard anesthetic practices including midazolam anxiolysis and sevoflurane maintenance ← **NEW**

---

## Citation

If you reference this work in presentations or academic writing:
```
George C. Multimodal & Opioid-Free Anesthesia Protocol for 
Robot-Assisted Total Knee Arthroplasty. GitHub repository.
https://github.com/collingeorge/rTKA-Multimodal-Anesthesia-Protocol
Version 1.2. Accessed [date].
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

### Version 1.2 (December 7, 2025) ← **NEW**

**Major Updates:**
- **Added comprehensive OR readiness checklist** (`OR_Checklist_Pre-Induction.md`)
- **Integrated midazolam 1-2 mg IV** as standard anxiolytic across all protocols per clinical feedback from Drs. Mandalia, Pauldine, and Chief CRNA Buchanan
- **Integrated sevoflurane 0.8-1.2 MAC** as preferred volatile agent with propofol TIVA alternatives
- **Enhanced all protocols** with pathway-specific medication preparation sections
- **Updated PACU handoff templates** with improved formatting (removed blockquotes for better readability)
- **Expanded evidence base** with midazolam and sevoflurane references
- **Added glycopyrrolate** as preferred agent for dexmedetomidine-related bradycardia
- **Enhanced patient counseling script** with midazolam education and special population considerations
- **Updated surgeon summary** with midazolam, sevoflurane, and ASRA anticoagulation timing
- **Improved quick reference cards** with comprehensive medication dosing
- **Added special considerations** for elderly/frail, OSA, and opioid-tolerant patients throughout
- **Clarified clinical principles** emphasizing that midazolam does not compromise OFIA goals

**Evidence Updates:**
- Added foundational midazolam pharmacology references (Reves 1985, Kain 1998, Dundee 1980)
- Added sevoflurane recovery profile evidence (Wachtel 2011, De Hert 2018)
- Expanded OFIA adjunct evidence with consensus guidelines
- Updated through December 7, 2025

### Version 1.1 (December 3, 2025)

**Added:**
- `Protocol_Medication_Dosing_and_Timing.md`
- `Protocol_Adjuncts_and_Contraindications.md`
- `Protocol_Quick_Reference_Cards.md`
- Expanded `03_Anesthesia_Protocols/README.md` to describe all protocol-related files
- Added images directory and `pathway_overview.png`
- Clarified OFIA terminology and safety framing
- Evidence current through December 2025
- Next planned evidence review: June 2026

### Version 1.0 (November 2025)

**Initial Release:**
- Initial three-pathway protocol framework
- Pre-op checklist, counseling script, three anesthesia protocols, comparison table
- Basic intra-op flowcharts, PACU handoff templates, surgeon one-page summary
- Evidence synthesis through January 2025

---

**For questions about protocol content, evidence updates, or implementation concepts, please open a GitHub issue.**
