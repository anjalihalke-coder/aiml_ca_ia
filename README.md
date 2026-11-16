# Artificial Intelligence & Machine Learning — C.A. and I.A. Work

[![Coursework](https://img.shields.io/badge/collection-academic%20coursework-2563eb)](#repository-contents) [![Status](https://img.shields.io/badge/status-in%20progress-64748b)](#items-requiring-input)

Academic practical reports, assignments, and supporting dataset files completed during the Computer Engineering curriculum. The repository follows the C.A. and I.A. organization of the [AIML CA & IA Labs reference](https://github.com/avinashsingh539/AIML_CA_IA_Labs), adapted to the material available here.

## About

This repository contains six Continuous Assessment practicals, one confirmed Internal Assessment assignment, one document titled as an I.A. theoretical activity, one I.A. report awaiting classification, and one shared spreadsheet dataset. The supplied files are PDF documents and an Excel workbook; no source code, notebooks, or runnable programs were present in the scanned folders.

## Student details

| Field | Details |
|---|---|
| Name | Anjali Halke |
| Roll number | 329 |
| Batch | E1 |
| PRN | 202502040016 |
| Department | Computer Engineering |

## Repository contents

### C.A. — Continuous Assessment

| Practical | Available material | Topic supported by available information |
|---|---|---|
| [Practical 1](C.A/Practical-1/README.md) | Two assignment PDFs | PEAS and expert systems |
| [Practical 2](C.A/Practical-2/README.md) | Practical report PDF | Problem solving through search (PDF metadata) |
| [Practical 3](C.A/Practical-3/README.md) | Practical report PDF | Topic needs confirmation from the report or course brief |
| [Practical 4](C.A/Practical-4/README.md) | Comparative-analysis PDF | Classification models |
| [Practical 5](C.A/Practical-5/README.md) | Comparative-analysis PDF | Classification models |
| [Practical 6](C.A/Practical-6/README.md) | Practical report PDF | Clustering algorithms on a real-world dataset |

The Practical 4 and Practical 5 folders each had a copy of the same Breast Cancer Wisconsin spreadsheet. The copies have identical SHA-256 hashes; the repository keeps one canonical copy in [`C.A/Datasets`](C.A/Datasets/README.md).

### I.A. — Internal Assessment

| Item | Available material | Classification |
|---|---|---|
| [Assignment 2 — Feature Engineering](I.A/Assignment-2/README.md) | Assignment PDF | Assignment, identified by filename |
| [AI Ethics Report](I.A/Unclassified/AI-Ethics-Report/README.md) | Report PDF | Activity/assignment type needs confirmation |
| [Activity 1 — Machine Learning Classification and Regression](I.A/Activity-1/README.md) | PDF document | PDF metadata identifies it as a theoretical activity; confirm this is the intended submitted material |

## Repository structure

```text
aiml_ca_ia/
├── README.md
├── .gitignore
├── C.A/
│   ├── Datasets/
│   │   ├── README.md
│   │   └── breast_cancer_wisconsin_dataset.xlsx
│   ├── Practical-1/
│   │   ├── README.md
│   │   ├── Assignment-1-PEAS/
│   │   └── Assignment-2-Expert-System/
│   ├── Practical-2/
│   ├── Practical-3/
│   ├── Practical-4/
│   ├── Practical-5/
│   └── Practical-6/
└── I.A/
    ├── Assignment-2/
    ├── Activity-1/
    │   ├── README.md
    │   └── Machine Learning Classification and Regression.pdf
    └── Unclassified/
        └── AI-Ethics-Report/
```

Each practical and assignment folder has its own README. Subfolders named after individual assignments within C.A. Practical 1 also include a README.

## Technologies and tools

| Technology or tool | Evidence in the available files |
|---|---|
| PDF | Practical reports and assignment submissions |
| Excel workbook (`.xlsx`) | Breast Cancer Wisconsin dataset |
| Python, Jupyter, libraries | No source file or dependency list was found to confirm use |

No `requirements.txt` is included because no Python source or identifiable software dependencies were supplied.

## How to use this repository

Open the README in the relevant practical or assignment folder for its available materials and notes. PDF submissions can be viewed with a PDF reader, and the dataset workbook can be opened with spreadsheet software that supports `.xlsx`. There are no runnable program instructions until source code is added.

## Dataset information

The only dataset file found is [`breast_cancer_wisconsin_dataset.xlsx`](C.A/Datasets/breast_cancer_wisconsin_dataset.xlsx), associated with C.A. Practical 4 and Practical 5. Its original copies in those folders were byte-identical. Dataset provenance, source link, and license have not been identified in the supplied files.

## Learning outcomes

The filenames identify work involving PEAS, expert systems, classification, feature engineering, AI ethics, regression, and clustering. Specific course outcomes are not documented in the available material and need input from the course brief or student.

## Acknowledgements

Repository organization was informed by the linked public reference repository. Dataset source and course/instructor acknowledgements can be added when their details are available.

## Items requiring input

- The full aim and problem statement for C.A. Practical 2, and the topic, aim, and problem statement for Practical 3.
- The assessment type for the AI Ethics report.
- Whether the C.A. Practical 2 and Practical 3 PDFs are Anjali's work; both contain embedded author metadata naming Prajakta shinde. The Activity 1 PDF names Abhijeet Damal in its embedded author metadata, so confirm whether this is a course handout or Anjali's submitted material.
- Dataset source, attribution, and license.
- Any source code, notebooks, requirements, or companion files stored outside the scanned folders.
- Specific aims, implementation details, results, and learning outcomes where the supplied filenames do not establish them.

## Maintainer

Anjali Halke · Computer Engineering · Batch E1
