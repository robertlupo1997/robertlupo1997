### Robert Lupo

I build data and AI tooling for finance teams, and I care about honest evaluation — calibrated
predictions, stated uncertainty, and documented limits.

Currently at Franklin Street (FP&A) | USF Statistics '24 | MIT Data Science

---

#### Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-green?style=flat)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-7B7B7B?style=flat)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)

---

#### What I do at work

Full-stack financial tooling: a React/TypeScript + FastAPI consolidated P&L dashboard over
three databases that replaced a 132-page printed monthly report, an auditable formula-driven
narrative framework used across seven business lines, and production ETL automation for Oracle
EPM with 114+ tests. I also led our Claude Enterprise rollout from 5 to 15 users — onboarding
curriculum, prompt library, and the licensing business case.

These figures describe internal work. No public repository backs them, so read them as my own
account rather than as something you can check here.

---

#### Projects

| Project | What it does | Status |
|---------|-------------|--------|
| [understudy](https://github.com/robertlupo1997/understudy) | Delegate scoped coding from Claude Code to a local Ollama model. Propose-only loop — nothing auto-merges — with a token-savings contract, sandboxed in a read-only worktree under `bwrap`. | Working, measured on one model, limits documented |
| [kkbox-churn-prediction](https://github.com/robertlupo1997/kkbox-churn-prediction) | Churn prediction built around point-in-time feature engineering: DuckDB SQL that bounds every aggregation window on both sides, with tests asserting exact values at the 89/91-day boundaries. | Reported metrics are tuned-validation, not held-out — clean holdout evaluation in progress |
| [hierarchical-revenue-forecast](https://github.com/robertlupo1997/hierarchical-revenue-forecast) | Polyglot forecasting stack over 1,782 retail **unit-sales** series — Python training, Go + ONNX serving, TypeScript dashboard. | Experimental. Current evaluator is rolling one-step; fixed-origin multi-horizon evaluation and hierarchical reconciliation are not yet wired into the pipeline |
| open-vocabulary-object-detection (private repo) | Text-prompted detection and segmentation with Grounding DINO + SAM 2, evaluated on COCO. | Prototype — single-prompt path is the working one |

The Status column is the honest one. Where a number is not yet reproducible from a clean clone,
it says so rather than quoting it.

---

#### Currently Building

**ferroml** — an AutoML framework in Rust with Python bindings. Currently does seeded
cross-validated comparison of default model configurations; hyperparameter search and
preprocessing integration are in progress, not finished.

---

#### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/robertlupo1997)
