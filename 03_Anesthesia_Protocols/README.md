---
title: Multimodal & Opioid-Free Anesthesia Protocols for Robot-Assisted TKA
version: 1.4
last-updated: 2025-12-14
---

# Multimodal & Opioid-Free Anesthesia Protocols for Robot-Assisted TKA (rTKA)

A unified, evidence-informed set of perioperative anesthesia pathways and supporting clinical tools for robot-assisted total knee arthroplasty (rTKA), integrating 2023–2025 literature, ERAS Society guidance, ASA/APSF safety recommendations, and ASRA 2024–2025 anticoagulation standards.

**Educational Use Only. Not a clinical guideline. Not institutional policy. Requires attending anesthesiologist oversight for any clinical application.**

---

## Terminology

In this repository:

- **OFA** refers specifically to **Opioid-Free *Intraoperative* Anesthesia (OFIA)**.
- **Postoperative opioid rescue** remains available when clinically required and **does not constitute pathway failure**.

---

## Directory Overview

This directory contains the integrated components of the rTKA anesthesia framework:

1. **Three primary anesthesia pathways (Protocols 1–3)**
2. **Medication dosing and timing module** (repository-wide pharmacology backbone)
3. **Adjuncts / contraindications / safety module** (including LAST and special populations)
4. **Protocol comparison table** (one-page clinician-facing overview)
5. **Quick-reference cards** (printable, laminate-friendly)
6. **Cross-links to PACU handoff / perioperative templates** (parent directories)
7. **Complete evidence citations** (parent directory)

Each file is cross-referenced and intended to remain internally consistent.

---

## 1. Core Anesthesia Pathways

<p align="center">
  <img src="../docs/images/pathway_overview.png" alt="Pathway Overview" width="90%">
</p>

*Figure 1: Overview of the three anesthesia pathways (Protocols 1–3). See individual protocol files for complete details, contraindications, and monitoring requirements.*

---

### Protocol 1 — OFIA With ACB + IPACK (Preferred First-Line When Feasible)  
**File:** [`Protocol_1_ACB_IPACK_OFIA.md`](Protocol_1_ACB_IPACK_OFIA.md)

**Summary:**  
ERAS-preferred pathway for most opioid-naïve rTKA patients when regional anesthesia is feasible and ASRA-safe. Combines quadriceps-sparing regional anesthesia (ACB + IPACK) with an OFIA adjunct strategy (ketamine ± dexmedetomidine ± magnesium) on a propofol-based anesthetic platform.

**Why it is preferred (typical trends):**
- Lowest PONV incidence
- Most reliable early mobilization (POD 0)
- Strongest early analgesia (PACU NRS commonly 0–3)
- Motor-sparing profile supporting safe ambulation

**Block summary (typical ranges):**
- **ACB:** 20–30 mL ropivacaine 0.2–0.25%
- **IPACK:** 20 mL ropivacaine 0.2–0.25%
- Maximum ropivacaine dose (conservative): **≈3 mg/kg**
- **LAST preparedness mandatory:** lipid emulsion 20% immediately available

---

### Protocol 2 — OFIA Block-Free (No Nerve Blocks)  
**File:** [`Protocol_2_BlockFree_OFIA.md`](Protocol_2_BlockFree_OFIA.md)

**Summary:**  
Used when regional blocks are not performed (patient refusal, ASRA anticoagulation timing, anatomy/workflow constraints). Relies on **surgeon periarticular infiltration** plus systemic OFIA adjuncts.

**Why choose this pathway (typical trends):**
- Avoids anticoagulation timing constraints related to blocks
- Faster workflow (no block placement)
- Preserves OFIA benefits compared with conventional opioid-heavy strategies

**Key features (typical):**
- Higher analgesic reliance on systemic adjuncts (ketamine/dexmedetomidine/magnesium ± lidocaine infusion)
- **Surgeon periarticular infiltration is essential** (not optional)
- Infiltration should be **dose-capped**: volume/concentration adjusted so total local anesthetic dose remains within conservative weight-based limits (see Adjuncts/Safety module)

---

### Protocol 3 — Conventional Opioid-Inclusive General Anesthesia  
**File:** [`Protocol_3_OpioidBased.md`](Protocol_3_OpioidBased.md)

**Summary:**  
Reserved for patients where OFIA components are contraindicated, not desired, or not appropriate (e.g., high opioid tolerance, selected psychiatric/cardiac conduction contraindications to OFIA adjuncts, or strong patient/attending preference).

**Key characteristics (expected trends):**
- Intraoperative opioids (e.g., fentanyl boluses ± hydromorphone)
- Higher PONV and sedation risk than OFIA pathways
- Greater postoperative respiratory monitoring requirements (especially OSA/elderly/opioid-naïve)

---

## 2. Pharmacology Backbone

### Medication Dosing & Timing (Repository Standardization)  
**File:** [`Protocol_Medication_Dosing_and_Timing.md`](Protocol_Medication_Dosing_and_Timing.md)

This module standardizes:
- ERAS pre-op medications
- Induction dosing ranges and timing
- Maintenance strategy and adjunct infusion ranges
- Emergence timing / infusion stop points
- PACU rescue dosing logic

**Repository-wide standard:**  
- **Propofol is the universal induction agent and default maintenance platform.**  
- **Sevoflurane may be used as an optional hybrid/transition/institutional preference**, not as the primary “either/or” framing.

---

## 3. Adjuncts, Contraindications, and Safety

### Adjuncts / Contraindications / Safety (LAST, Special Populations, Monitoring)  
**File:** [`Protocol_Adjuncts_and_Contraindications.md`](Protocol_Adjuncts_and_Contraindications.md)

Summarizes absolute/relative contraindications and safety considerations for:
- Ketamine (including hemodynamic guardrails)
- Dexmedetomidine (bradycardia/AV block risk)
- Magnesium sulfate (**avoid if CrCl <30 mL/min**)
- Lidocaine infusion (optional; toxicity monitoring)
- Regional anesthesia (ACB/IPACK) per **ASRA 2024–2025**
- LAST prevention and treatment expectations (lipid rescue availability)

Also reinforces:
- **Avoid routine gabapentinoids** (ASA/APSF 2024 safety emphasis)
- Risk-stratified monitoring in OSA, frailty, renal/hepatic impairment, and cardiac disease

---

## 4. Comparison and Quick-Reference Tools

### Pathway Comparison Table  
**File:** [`Protocol_Comparison_Table.md`](Protocol_Comparison_Table.md)

One-page overview of:
- Analgesic mechanisms
- Expected pain trajectory
- Suitability by patient phenotype
- PONV expectations
- Mobilization goals
- Workflow considerations

### Quick Reference Cards (Laminate-Friendly)  
**File:** [`Protocol_Quick_Reference_Cards.md`](Protocol_Quick_Reference_Cards.md)

Back-of-badge style card summarizing:
- Pre-op medications
- Block recipes (when applicable)
- Induction/maintenance dosing ranges
- PACU rescue algorithm
- Safety reminders (MAP goals, dexmed bradycardia response, LA dose-capping, LAST readiness)

---

## 5. Protocol Selection Guide (High-Level)

### Prefer Protocol 1 (OFIA + Blocks) when:
- ASRA timing permits safe ACB/IPACK
- Patient consents to regional anesthesia
- Early ambulation (POD 0) and minimal PONV are high priority

### Use Protocol 2 (OFIA Block-Free) when:
- Blocks are declined or not feasible (ASRA timing, anatomy, workflow)
- Surgeon can perform consistent periarticular infiltration
- OFIA strategy remains appropriate and desired

### Use Protocol 3 (Conventional Opioid-Inclusive) when:
- High opioid tolerance or chronic opioid use requires conventional strategy
- OFIA adjuncts are contraindicated or undesirable for the specific patient
- Patient/attending preference favors a conventional approach after counseling

---

## 6. Clinical Implementation Notes (For QI / Institutional Adaptation)

If adapting for institutional use, recommended prerequisites include:
- Medication/formulary confirmation (ketamine, dexmedetomidine, magnesium, lidocaine)
- Credentialing and competency for ultrasound-guided ACB/IPACK
- PACU nursing education on OFIA recovery patterns and ketamine rescue
- Confirm **lipid emulsion 20% is immediately accessible** wherever blocks are performed
- Pharmacy alignment for infusion concentrations and labeling
- Standardized documentation of total local anesthetic dose (blocks + infiltration)

Suggested quality metrics for QI/IRB workflows:
- Pain scores (PACU arrival, 2h, 12h, 24h)
- 24-hour opioid consumption (MME)
- PONV incidence and rescue
- Time to ambulation and PT milestones
- Length of stay (PACU + inpatient)
- Patient-reported recovery measures

---

## 7. Version History

**Version 1.4 — December 2025**
- Updated repository-wide standardization: **propofol default maintenance platform**, sevoflurane optional hybrid/transition framing
- Harmonized OFIA language across protocols (selection-dependent ketamine guidance and hemodynamic guardrails)
- Reinforced dose-capped surgeon infiltration language in block-free pathway
- Improved cross-linking to pharmacology backbone and safety module

**Version 1.3 — December 2025**
- Added quick reference cards
- Harmonized pharmacology across protocols
- Updated anticoagulation and safety language
- Revised selection guide and methodology

**Next planned review:** **June 2026** (or earlier if major guideline changes occur)

---

## 8. Scope and Legal Disclaimer

These materials are:
- Educational
- Non-validated
- Not institutional policy
- Not medical advice

Any clinical implementation requires:
- Supervising anesthesiologist review
- Institutional adaptation and approval processes
- Alignment with pharmacy, nursing, and credentialing requirements
- Compliance with ASRA anticoagulation standards and local policies

---

## 9. Related Repository Links

**Pre-Operative**
- [`01_PreOp_Checklist.md`](../01_PreOp_Checklist.md)
- [`02_Patient_Counseling_Script.md`](../02_Patient_Counseling_Script.md)

**Intra-Operative**
- [`04_IntraOp_Flowcharts/`](../04_IntraOp_Flowcharts/)

**Post-Operative**
- [`05_PACU_Handoff_Templates.md`](../05_PACU_Handoff_Templates.md)

**Team Coordination**
- [`06_Surgeon_OnePage_Summary.md`](../06_Surgeon_OnePage_Summary.md)

**Evidence Base**
- [`07_References_Evidence_2024.md`](../07_References_Evidence_2024.md)

---

**← Return to Main Repository Overview**  
[../README.md](../README.md)
