# OCT Analysis Assistant - Custom GPT Project Overview

## Project Summary

This custom GPT is designed to support ophthalmologists in interpreting Optical Coherence Tomography (OCT) scans, identifying biomarkers, and making evidence-based clinical decisions for retinal diseases.

**Target User**: Ophthalmologists, Retina Specialists, Ophthalmic Imaging Technicians

**Primary Use Cases**:
- OCT biomarker identification and documentation
- Prognostic assessment based on imaging findings
- Differential diagnosis support
- Treatment response evaluation
- Clinical decision support

---

## Project Structure

```
custom-gpt-OCT/
├── instructions/
│   ├── custom-gpt-instructions.md    # Core GPT instructions (<7,500 chars)
│   ├── system-prompt.md              # System configuration
│   └── security-guidelines.md        # Privacy and safety protocols
│
├── knowledge-base/
│   ├── core-concepts/
│   │   ├── oct-anatomy.md            # Retinal layer terminology
│   │   └── biomarkers-overview.md    # Complete biomarker reference
│   │
│   ├── procedures/
│   │   ├── disease-analysis.md       # General analysis workflows
│   │   ├── diabetic-disease.md       # DME/DR protocol
│   │   ├── amd-analysis.md           # AMD (dry and wet) protocol
│   │   ├── vascular-occlusions.md    # RVO protocol
│   │   ├── mactel-analysis.md        # MacTel Type 2 protocol
│   │   └── pachychoroid.md           # CSC/pachychoroid spectrum
│   │
│   ├── best-practices/
│   │   ├── interpretation-guidelines.md  # Systematic approach
│   │   └── prognostic-factors.md         # Evidence-based prognosis
│   │
│   ├── troubleshooting/
│   │   ├── artifacts-pitfalls.md         # Quality and artifacts
│   │   └── differential-diagnosis.md     # DDx guidance
│   │
│   └── resources/
│       ├── treatment-protocols.md    # Current treatment guidelines
│       └── references.md             # Clinical references
│
├── examples/
│   ├── sample-conversations.md       # Example interactions
│   └── use-case-scenarios.md         # Clinical use cases
│
└── project-overview.md               # This file
```

---

## Diseases Covered

### Primary Conditions
1. **Diabetic Macular Edema (DME)** and Diabetic Retinopathy
2. **Age-Related Macular Degeneration** (Dry AMD, Geographic Atrophy, Neovascular AMD)
3. **Retinal Vein Occlusions** (BRVO, CRVO, HRVO)
4. **Macular Telangiectasia Type 2** (MacTel)
5. **Pachychoroid Spectrum Diseases** (CSC, PPE, PNV, PCV)

### Additional Topics
- Cystoid macular edema (various etiologies)
- Vitreoretinal interface disorders
- Post-surgical complications
- Differential diagnosis guidance

---

## Key Features

### 1. Biomarker Reference
Comprehensive documentation of OCT biomarkers including:
- DRIL, EZ, ELM integrity
- HRF, IHRF
- Fluid compartments (IRF, SRF, sub-RPE)
- Choroidal parameters
- Disease-specific markers

### 2. Evidence-Based Prognosis
Prognostic information drawn from:
- Systematic reviews and meta-analyses
- Landmark clinical trials
- Consensus guidelines

### 3. Disease-Specific Protocols
Structured analysis workflows for each major condition with:
- Key findings to document
- Measurement protocols
- Staging systems
- Treatment implications

### 4. Quality Assurance
Guidance on:
- Artifact recognition
- Quality assessment
- Interpretation pitfalls
- Common misdiagnoses

### 5. Treatment Support
Current treatment protocol reference including:
- Anti-VEGF agents and dosing
- Steroid options
- Treat-and-extend frameworks
- Response assessment

---

## How to Deploy

### For OpenAI Custom GPT

1. **Create New GPT** in ChatGPT

2. **Configure Instructions**:
   - Copy content from `instructions/custom-gpt-instructions.md`
   - Ensure character count is under 7,500

3. **Upload Knowledge Base**:
   - Upload all `.md` files from the `knowledge-base/` folder
   - These will be available for retrieval

4. **Configure Capabilities**:
   - Enable "Web Browsing" (optional, for guideline updates)
   - Enable "DALL-E" (not typically needed)
   - Enable "Code Interpreter" (not typically needed)

5. **Set Conversation Starters**:
   - "Analyze these OCT findings for DME: [describe findings]"
   - "What biomarkers predict poor prognosis in nAMD?"
   - "Help me differentiate MacTel from CME"
   - "Review this OCT quality before I interpret"

6. **Test with Sample Queries** from `examples/sample-conversations.md`

---

## Knowledge Base Cross-References

The knowledge base files extensively cross-reference each other. Key reference patterns:

### Core Concepts Referenced By:
- All procedure files
- Best practices files
- Troubleshooting files

### Procedures Referenced By:
- Instructions file
- Best practices
- Examples

### Best Practices Referenced By:
- Procedures (for interpretation approach)
- Examples (for prognosis)

### Troubleshooting Referenced By:
- Procedures (for differential)
- Best practices (for quality)

---

## Instruction File Details

### Character Count Compliance
The `custom-gpt-instructions.md` file is designed to be under 7,500 characters while:
- Providing comprehensive functional guidance
- Referencing knowledge base files for detailed information
- Including quick reference tables
- Specifying response structure

### Key Instruction Elements

1. **Primary Functions**: Biomarker ID, prognosis, differential, treatment
2. **Knowledge Base References**: Explicit file references
3. **Disease-Specific Guidance**: Quick reference for major conditions
4. **Response Structure**: Standardized output format
5. **Critical Rules**: Safety and scope limitations
6. **Quality Assessment**: Pre-interpretation checklist
7. **Terminology Standards**: IN-OCT consensus adherence

---

## Research Sources

The knowledge base was developed from:

### Clinical Guidelines
- AAO Preferred Practice Patterns
- EURETINA Guidelines
- Consensus statements

### Evidence Base
- DRCR.net Protocol Studies
- VIEW, RISE/RIDE, HARBOR trials
- CATT, IVAN studies
- Systematic reviews (2024-2025)

### Nomenclature
- IN-OCT Consensus 2014
- Beckman AMD Classification
- CAM Atrophy Classification

---

## Limitations and Disclaimers

### This GPT Does NOT:
- Provide definitive medical diagnoses
- Replace clinical examination
- Make treatment prescriptions
- Store patient data
- Constitute medical advice to patients

### Clinical Responsibility:
- All outputs require physician verification
- Final decisions rest with treating clinician
- Must correlate with complete clinical picture
- Guidelines evolve; verify current standards

---

## Maintenance Notes

### Recommended Updates
- Review clinical guidelines annually
- Update treatment protocols as new agents approved
- Incorporate new biomarker research
- Refine based on user feedback

### Version Control
- Document all changes with dates
- Maintain version history in frontmatter
- Test after major updates

---

## Support and Feedback

### For Technical Issues:
- Review instruction character count
- Verify knowledge base file uploads
- Check cross-references

### For Clinical Content:
- Compare to current published guidelines
- Verify against primary literature
- Consider specialty society updates

---

## License and Usage

This project is intended for clinical decision support and educational purposes.

**Important**: This tool is not a medical device and should not be used as the sole basis for clinical decisions.

---

## Contact

Developed for ophthalmology clinical practice support.

Last Updated: January 2025
Version: 1.0
