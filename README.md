# Open Medical Vocabulary Schema (OMVS)

**OMVS** is an open-source, specialty-aware medical vocabulary and context resolution framework designed for clinical documentation, medical transcription, and AI-assisted healthcare workflows.

OMVS provides a **structured, extensible, and legally clean alternative** to proprietary medical vocabulary systems by focusing on:
- medical terminology
- abbreviations
- context-aware resolution
- specialty-specific language patterns

OMVS is **ASR-agnostic**, **LLM-friendly**, and **HIPAA-conscious by design**.

---

## 🎯 Project Goals

- Provide an **open medical vocabulary standard**
- Enable **context-aware abbreviation expansion**
- Support **specialty-specific clinical language**
- Integrate easily with:
  - speech-to-text engines
  - LLMs
  - EHR / EMR systems
- Encourage **community-driven medical language models**

---

## OMVS contains ** ❌ NO acoustic models**, ** ❌ NO patient information**, and ** ❌ NO proprietary vendor files**.

---

## 🧠 Core Concepts

### 1. Specialty-Aware Vocabulary
Each medical specialty maintains its own vocabulary, abbreviations, phrases, templates, and rules.

### 2. Context Resolution
Abbreviations and ambiguous terms are resolved using:
- surrounding text
- specialty bias
- clinical context
- confidence scoring

### 3. Human + Machine Friendly
OMVS uses **YAML and JSON** for readability and automation.
