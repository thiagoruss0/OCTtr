---
title: Use Case Scenarios for OCT Analysis GPT
version: 1.0
last_updated: 2025-01
---

# Use Case Scenarios

This document outlines practical scenarios where the OCT Analysis Assistant provides clinical value.

---

## Use Case 1: Daily Clinical Workflow Support

### Scenario
Busy retina clinic with 40+ OCT reviews per day. Physician needs efficient biomarker documentation.

### How the GPT Helps

**User Input**: "Quick review: DME patient, post 3 anti-VEGF injections. CST 310, was 380. Some residual cysts in ONL. EZ intact. DRIL absent."

**GPT Response**:
Provides structured documentation:
- Treatment response: Partial response (CST decreased 70µm, 18%)
- Positive indicators: Intact EZ, absent DRIL
- Monitoring: Residual ONL cysts - continue treatment
- Recommendation: Good candidate for interval extension trial

### Value
- Rapid, standardized biomarker documentation
- Consistent prognostic assessment
- Treatment decision support

---

## Use Case 2: Complex Case Analysis

### Scenario
Atypical presentation requiring careful biomarker interpretation and differential consideration.

### How the GPT Helps

**User Input**: "Unusual case: bilateral macular thickening with temporal cystic spaces, no improvement after extensive anti-VEGF. Patient is frustrated."

**GPT Response**:
- Flags MacTel Type 2 as likely diagnosis
- Explains why anti-VEGF doesn't work
- Provides distinguishing features to confirm
- Offers patient communication guidance
- References appropriate knowledge base files

### Value
- Prevents prolonged inappropriate treatment
- Reduces diagnostic delay
- Improves patient communication

---

## Use Case 3: Trainee Education

### Scenario
Ophthalmology resident learning OCT interpretation needs to understand biomarker significance.

### How the GPT Helps

**User Input**: "Can you explain what DRIL is, how to measure it, and why it matters in DME?"

**GPT Response**:
- Definition with visual description
- Measurement protocol (central 1mm, >500µm threshold)
- Evidence for prognostic significance
- Clinical application examples
- References to supporting literature

### Value
- Comprehensive educational resource
- Evidence-based learning
- Practical application guidance

---

## Use Case 4: Prognostic Counseling Preparation

### Scenario
Preparing for a difficult conversation with patient about limited visual prognosis.

### How the GPT Helps

**User Input**: "Patient has DME with DRIL >500µm, disrupted EZ and ELM. Edema resolved with treatment but vision hasn't improved. Need to explain prognosis."

**GPT Response**:
- Explains biomarker significance in accessible terms
- Provides evidence-based VA outcome predictions
- Suggests counseling approach
- Notes that structural damage limits recovery despite anatomic success

### Value
- Evidence-based patient communication
- Realistic expectation setting
- Supports difficult conversations

---

## Use Case 5: Treatment Decision Support

### Scenario
Deciding whether to switch anti-VEGF agents or add steroid in partial responder.

### How the GPT Helps

**User Input**: "DME patient on ranibizumab x 6 months. Initial response but now plateaued with persistent INL cysts and HRF. CST stable at 330. What are my options?"

**GPT Response**:
- Assesses as partial responder with specific biomarkers
- Notes INL cysts associated with reduced response
- Options presented:
  1. Switch to aflibercept or faricimab
  2. Add/switch to dexamethasone implant
  3. Continue if VA acceptable
- Factors for each decision
- References treatment protocols

### Value
- Evidence-based treatment options
- Biomarker-guided decision making
- Comprehensive option review

---

## Use Case 6: AMD Risk Stratification

### Scenario
Determining follow-up interval and counseling for intermediate AMD patient.

### How the GPT Helps

**User Input**: "Intermediate AMD with large drusen, some RPD, and I think I see IHRF. How high-risk is this and what should I tell the patient?"

**GPT Response**:
- Stratifies as HIGH RISK based on multiple biomarkers
- Provides specific odds ratios for progression
- Recommends:
  - Shortened follow-up interval
  - Home monitoring setup
  - AREDS2 confirmation
  - Patient education checklist
- Communication framework for explaining risk

### Value
- Risk-stratified follow-up planning
- Evidence-based risk communication
- Comprehensive prevention strategy

---

## Use Case 7: Quality Assurance

### Scenario
Reviewing OCT with potential artifacts before making treatment decisions.

### How the GPT Helps

**User Input**: "OCT shows apparent improvement but signal strength is 5/10 and I see what might be segmentation errors. Should I trust the measurements?"

**GPT Response**:
- Identifies quality issues (signal below threshold)
- Explains potential impact on measurements
- Recommends:
  - Review raw B-scans vs. automated report
  - Consider repeat scan
  - Factors that may have caused poor quality
  - How to optimize future scans

### Value
- Prevents decisions based on artifact
- Quality improvement guidance
- Patient safety protection

---

## Use Case 8: Differential Diagnosis Assistance

### Scenario
Distinguishing between similar-appearing conditions.

### How the GPT Helps

**User Input**: "Patient with SRF and thick choroid. Could be CSC or pachychoroid neovasculopathy. How do I tell the difference?"

**GPT Response**:
- Provides systematic comparison table
- Key distinguishing features:
  - PED characteristics
  - Double-layer sign presence
  - OCTA findings
- Suggests additional imaging if needed
- Treatment implications of each diagnosis

### Value
- Systematic differential approach
- Prevents misdiagnosis
- Appropriate treatment selection

---

## Use Case 9: Research and Publication Support

### Scenario
Writing case report or reviewing literature on OCT biomarkers.

### How the GPT Helps

**User Input**: "What are the key OCT biomarkers predicting anti-VEGF response in DME? Need this for a presentation."

**GPT Response**:
- Lists biomarkers with evidence levels
- Provides key study references
- Quantifies prognostic impact (e.g., ETDRS letter differences)
- Notes systematic review findings
- Organizes by favorable vs. unfavorable

### Value
- Quick literature synthesis
- Evidence-based presentation support
- Reference compilation

---

## Use Case 10: Multi-Disease Patient

### Scenario
Patient with multiple conditions requiring integrated analysis.

### How the GPT Helps

**User Input**: "Diabetic patient with intermediate AMD features in one eye. OCT shows drusen with some HRF, plus mild DME in the same eye. How do I interpret the HRF?"

**GPT Response**:
- Acknowledges complexity of dual pathology
- Differentiates HRF sources:
  - AMD-related IHRF (over drusen, predicts GA)
  - DME-related HRF (scattered, inflammatory)
- Location-based interpretation
- Management considerations for both conditions
- Monitoring priorities

### Value
- Complex case navigation
- Nuanced interpretation
- Integrated management approach

---

## Use Case 11: Post-Surgical Evaluation

### Scenario
Differentiating expected post-operative changes from complications.

### How the GPT Helps

**User Input**: "Patient 6 weeks post cataract surgery with new CME. OCT shows cystoid edema. Is this Irvine-Gass or could the prior intermediate AMD be converting?"

**GPT Response**:
- Reviews Irvine-Gass characteristics and timing
- Differentiates from nAMD conversion
- Key distinguishing features:
  - Timing (4-12 weeks typical for Irvine-Gass)
  - PED presence (suggests AMD)
  - OCTA findings if available
- Treatment differences
- When to be concerned about AMD conversion

### Value
- Post-operative differential
- Appropriate treatment selection
- Complication recognition

---

## Use Case 12: Longitudinal Monitoring

### Scenario
Interpreting progression or improvement over time.

### How the GPT Helps

**User Input**: "Comparing current OCT to 6 months ago. CST similar but DRIL seems more extensive and EZ looks worse. Is this progressing despite stable thickness?"

**GPT Response**:
- Emphasizes structural biomarkers over thickness alone
- Interprets worsening DRIL and EZ as progression
- Explains that:
  - Thickness may stabilize while damage progresses
  - DRIL extension indicates neuronal loss
  - EZ deterioration predicts VA decline
- Recommends:
  - Treatment reassessment
  - Documentation of structural changes
  - Patient counseling about expectations

### Value
- Nuanced progression detection
- Beyond simple thickness metrics
- Early intervention opportunity

---

## Summary: GPT Value Proposition

| Use Case Category | Primary Value |
|-------------------|---------------|
| Clinical Workflow | Efficiency, standardization |
| Complex Cases | Diagnostic accuracy |
| Education | Knowledge transfer |
| Counseling | Evidence-based communication |
| Treatment Decisions | Biomarker-guided therapy |
| Quality Assurance | Error prevention |
| Differential Diagnosis | Diagnostic accuracy |
| Research | Literature synthesis |
| Multi-disease | Integrated management |
| Longitudinal Care | Progression detection |

---

## Cross-References

- Sample conversations: `sample-conversations.md`
- Disease protocols: `../knowledge-base/procedures/`
- Biomarkers: `../knowledge-base/core-concepts/biomarkers-overview.md`
- Best practices: `../knowledge-base/best-practices/`
