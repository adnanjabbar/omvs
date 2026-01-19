![Status](https://img.shields.io/badge/status-active_development-blue)
![Emergency Medicine](https://img.shields.io/badge/emergency_medicine-60%25-green)
![License](https://img.shields.io/badge/license-open_source-brightgreen)


# Open Medical Vocabulary Schema (OMVS)

**OMVS** is an open, clinician-led medical vocabulary and language normalization framework designed
to support **medical transcription**, **structured reporting**, and **AI-assisted clinical documentation**
across multiple medical specialties.

OMVS provides a standardized, specialty-aware medical language layer that can be safely used by
humans, software systems, and artificial intelligence in clinical environments.

---

## 📊 Project Development Status

OMVS is under active development with transparent progress tracking.

👉 **[View detailed progress → PROGRESS.md](PROGRESS.md)**

### Snapshot
- 🚑 Emergency Medicine: **80% complete**
- 🩺 Internal Medicine: **20%**
- ❤️ Cardiology: **30%**
- 🟦 Urology: **30%**

---

## 🌍 Why OMVS Exists

Medical language today suffers from several critical problems:

- Fragmentation across specialties and vendors  
- Heavy reliance on proprietary dictation vocabularies  
- Unsafe abbreviation expansion in AI systems  
- Loss of clinical context during transcription  
- Poor interoperability between documentation systems  

OMVS was created to address these gaps by providing an **open, auditable, and extensible**
medical vocabulary framework built by clinicians for clinicians.

---

## 🧠 What OMVS Provides

OMVS is **not** a language model.  
It is a **medical language infrastructure layer**.

### Core Capabilities

- Normalized medical vocabulary schema
- Explicit specialty separation
- Context-aware abbreviation resolution
- Structured reporting templates
- Rule-based clinical safety constraints
- OpenAPI service specification
- AI transcription integration support

OMVS can be used **with any speech-to-text engine or AI model**.

---

## 🏥 Completed Core Specialties (v1.0)

OMVS v1.0 includes fully populated, production-ready vocabularies for:

- **Family Medicine**
- **Radiology**
  - Ultrasound
  - CT
  - MRI
  - X-ray
  - Doppler
- **Emergency Medicine**
- **Internal Medicine**
- **Cardiology**
  - Clinical cardiology
  - ECG
  - Echocardiography
- **Urology**
  - Ultrasound-heavy
  - Doppler-focused
  - Prostate, renal, andrology workflows

Additional specialties are scaffolded and open for contribution.

---

## 📁 Project Structure

OMVS is organized in a modular and extensible way:

specialties/ # Specialty-specific vocabularies
api/ # OpenAPI definitions
integration/ # AI & transcription integration guides
docs/ # Documentation & whitepaper
tools/ # Validation and tooling
governance/ # Governance & code of conduct
adoption/ # Hospital & academic adoption guides


Each specialty follows a consistent schema:

- `meta.yaml`
- `terms.yaml`
- `abbreviations.yaml`
- `phrases.yaml`
- `templates.yaml`
- `rules.yaml`
- `CHANGELOG.md`

---

## 🤖 Intended Use Cases

OMVS is designed to support:

- Medical dictation and transcription engines
- AI-based clinical note generation
- Radiology and ultrasound reporting systems
- Academic research and medical NLP benchmarking
- Hospital documentation platforms
- Clinical decision support tooling (language layer only)

---

## 🧩 Design Principles

OMVS is built on the following principles:

- **Clinician-first**, not vendor-first
- **Open and auditable**
- **Specialty-aware**
- **AI-compatible but AI-agnostic**
- **Safe for clinical environments**
- **Non-diagnostic and non-prescriptive**

OMVS does **not** replace clinical judgment.

---

## 👤 Creator & Maintainer

**Dr. Adnan Jabbar**

- Medical Doctor (MBBS, DFM, MH, MPH (Cont.), Clinical Embryology, Family & Emergency Medicine)
- Family Medicine, Emergency Medicine, Fertility Medicine, IVF Embryology Specialist.
- Experience in clinical documentation and clinical infrastructure.
- Strong interest in medical AI, transcription systems, and open clinical infrastructure.
- [LinkedIn](https//www.linkedin.com/in/adnanjabbar)

OMVS was initiated to bridge the gap between **clinical reality** and **medical AI systems**.

---

## 🤝 Governance & Community

OMVS follows a **clinician-led open governance model**.

Contributions are welcome from:
- Clinicians
- Medical trainees
- Researchers
- Developers working in healthcare

Please refer to:
- `docs/contributing.md`
- `governance/GOVERNANCE.md`
- `governance/CODE_OF_CONDUCT.md`

---

## 📄 Licensing & Use

OMVS is released as an open-source project intended for:
- Community use
- Academic research
- Institutional pilots
- Commercial integration (subject to license terms)

See the `LICENSE` file for details.

---

## 🚀 Project Status

- **Current Release:** v1.0
- **Core Specialties:** Complete
- **Project State:** Production-ready foundation, expanding coverage

OMVS is actively maintained and open to collaboration.

---

## 📬 Contact

For collaboration, contribution, or institutional interest,  
please use the GitHub repository discussion and issue system.

---

**OMVS — building an open medical language layer for the future of clinical AI.**
