# Experiment-Tracking

### Make ML reproducible: track parameters, metrics, data versions, and artifacts so any result can be recreated months later.

![Chain P](https://img.shields.io/badge/Chain%20P-0284C7?style=for-the-badge) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge)](LICENSE-GPL) [![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue?style=for-the-badge)](LICENSE-AGPL)

[📖 Lesson Plan](docs/LESSON_PLAN.md) · [🎮 Interactive Tour](docs/interactive/index.html)

<!-- SCREENSHOT PLACEHOLDER: docs/screenshots/overview.png -->

> ⬜ **Scaffold pending.** Directory created to portfolio standard; full content (README, lesson plan, tour + quiz, skeleton code) still to be built. Part of **Chain P — MLOps & Applied ML**.

## Why This Was Built

"Which run was that?" is the question that exposes an undisciplined ML workflow. Without tracking, you end
up with a model file, a vague memory of the hyperparameters, and no way to reproduce the number you reported.

Tracking fixes that by recording the full context of every run — parameters, metrics, code version, data
version, and output artifacts — so a result can be reconstructed later. It's the ML equivalent of version
control, and it's the difference between a research process and a pile of notebooks.

## Why This Matters (Industry Application)

Reproducibility is a hard requirement anywhere ML touches regulated or high-stakes decisions, and it's
table stakes for any team with more than one person. Tools like MLflow and Weights & Biases appear
constantly in job descriptions, and the underlying discipline is what makes collaboration possible.

## Topics Covered

| Area | What this project covers |
|------|--------------------------|
| Runs | Parameters, metrics, and tags for every experiment |
| Artifacts | Storing models, plots, and outputs with the run |
| Data versioning | Knowing which dataset produced which result |
| Comparison | Diffing runs to see what actually helped |
| Reproducibility | Recreating a result months later |
| Collaboration | Shared experiment history across a team |

## How This Connects

Chain P (MLOps). Feeds **Model-Registry-And-CICD**; supports the rigor in **Model-Evaluation-And-Experimentation**.

---
Dual licensed — [GPL v3](LICENSE-GPL) and [AGPL v3](LICENSE-AGPL).
