# QM7073 — Foundations of Analytics

Course repository for **QM7073: Foundations of Analytics** at The University of Tulsa.

This in-person course uses a workshop model: concise instruction, individual no-AI Learning Practices, and collaborative Decision Labs in which approved AI use may be required, disclosed, and independently verified.

## Decision Labs

| Lab | Module connection | Focus | Status |
|---|---|---|---|
| [Decision Lab 1](mini-projects/mini-project-01-github-data-audit/README.md) | Modules 1–2 | GitHub, data-quality auditing, decision framing, and responsible AI | Available |
| Decision Lab 2 | Data visualization | AI-assisted dashboard challenge | Coming later |
| Decision Lab 3 | Regression and predictive analytics | Data mining, validation, and model comparison | Coming later |
| Decision Lab 4 | Forecasting and prescriptive analytics | Forecasting and/or optimization for a business decision | Coming later |

## Repository structure

Each Decision Lab is self-contained in one numbered folder so materials, data, templates, and future instructor resources remain separated.

```text
QM7073/
├── README.md
└── mini-projects/
    ├── mini-project-01-github-data-audit/
    │   ├── ASSIGNMENT.md
    │   ├── README.md
    │   ├── data/
    │   │   └── raw/
    │   ├── analysis/
    │   ├── ai-use/
    │   └── report/
    ├── decision-lab-02-dashboard-challenge/
    ├── decision-lab-03-data-mining/
    └── decision-lab-04-forecasting-optimization/
```

The first folder keeps its original path so existing links do not break. New labs should use the convention `decision-lab-XX-short-name`.

Each lab folder should contain:

- a student-facing `README.md`;
- complete instructions in `ASSIGNMENT.md`;
- a `data/` folder with raw and, when appropriate, cleaned data kept separate;
- an `analysis/` folder for reproducible work;
- an `ai-use/` folder for disclosure and verification records; and
- a `report/` folder for templates and final deliverables.

This design allows the course to add, revise, or reorder Decision Labs without mixing files or breaking unrelated assignments.

## Course workflow

- **Learning Practices:** Individual work completed without generative AI unless explicitly stated otherwise.
- **Decision Labs:** Collaborative work in which approved AI tools may be permitted or required.
- **Verification:** AI output is never accepted as evidence by itself. Students must reproduce and validate calculations, transformations, sources, assumptions, and recommendations.
- **Two-stage work:** When specified, teams submit an in-class first draft and an improved final version.
- **Repository safety:** Never commit API keys, passwords, personal information, restricted data, or unnecessary AI chat transcripts.

## Data statement

All people, transactions, and comments in the Dr. K dataset are fictional and were created solely for educational use.
