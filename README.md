# omvs
Open Medical Vocabulary Schema
open-medical-vocabulary/
│
├── README.md
├── LICENSE (Apache 2.0 recommended)
│
├── specs/
│   ├── schema.md
│   ├── context-resolution.md
│   └── specialty-guidelines.md
│
├── specialties/
│   ├── family-medicine/
│   │   ├── meta.yaml
│   │   ├── abbreviations.yaml
│   │   ├── terms.yaml
│   │   ├── phrases.yaml
│   │   ├── templates.yaml
│   │   └── rules.yaml
│   │
│   ├── radiology/
│   ├── cardiology/
│   └── psychiatry/
│
├── api/
│   ├── openapi.yaml
│   └── examples/
│
├── tools/
│   ├── word-ingest.py
│   ├── abbreviation-extractor.py
│   └── validation.py
│
└── examples/
    ├── dictation-input.txt
    ├── structured-output.json
    └── yaml-example.yaml
