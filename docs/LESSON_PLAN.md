# 📖 Lesson Plan — Experiment-Tracking

> **Chain P — MLOps & Applied ML** | Make ML reproducible: track parameters, metrics, data versions, and artifacts so any result can be recreated months later.

## What This Project Is

Instrument an ML workflow so every run records its parameters, metrics, data version, and artifacts — and any result can be reproduced months later.

## Learning Objectives

By the end I can:

1. Log parameters, metrics, and tags for every run.
2. Store model artifacts and plots alongside the run that produced them.
3. Record the **data version** used, not just the code version.
4. Compare runs to see which change actually helped.
5. Reproduce a previous result from its recorded context.
6. Share experiment history across a team.

## Software You Will Use

- MLflow (or Weights & Biases).
- Python, scikit-learn.
- DVC or dataset hashing for data versioning.
- Git for code versioning.

## Build Order

1. Train a model with no tracking; try to reproduce it a day later.
2. Add run tracking for parameters and metrics.
3. Log artifacts: model file, plots, confusion matrix.
4. Record the code commit and a data hash per run.
5. Run a sweep; compare runs to find what mattered.
6. Reproduce an earlier run exactly from its record.

## Common Mistakes to Avoid

- Tracking metrics but not the data version, making reproduction impossible.
- Logging only the final run and losing the failures that taught you more.
- Storing artifacts outside the run so they drift apart.
- Recording accuracy without the parameters that produced it.
- Treating notebooks as a record of what happened.

## Check Your Understanding

The quiz covers what constitutes a reproducible run, why data versioning matters, and comparing runs meaningfully.

## Why This Matters (Industry Application)

Reproducibility is a hard requirement anywhere ML touches regulated or high-stakes decisions, and it's
table stakes for any team with more than one person. Tools like MLflow and Weights & Biases appear
constantly in job descriptions, and the underlying discipline is what makes collaboration possible.

## Reflection Questions

- If asked to justify a model's numbers a year from now, what would you need that you are not currently recording?
- Which failed experiments are worth keeping, and why?
