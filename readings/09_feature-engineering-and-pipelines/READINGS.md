# Session 9 readings - Feature engineering, pipelines and leakage

## Core

1. **Kapoor & Narayanan, "Leakage and the Reproducibility Crisis in ML-based Science", 2022.**
   <https://arxiv.org/abs/2207.07048>
   A taxonomy of eight kinds of leakage, with 300+ published papers affected across
   seventeen fields. The single most useful thing you will read this term for the project.

2. **Buitinck et al., "API design for machine learning software: experiences from the
   scikit-learn project", 2013.** <https://arxiv.org/abs/1309.0238>
   Why the `fit` / `transform` / `predict` contract exists and how `Pipeline` uses it. Read
   this and the pipeline discipline stops feeling like boilerplate.

## Optional

3. **Sculley et al., "Hidden Technical Debt in Machine Learning Systems", NeurIPS 2015.**
   <https://proceedings.neurips.cc/paper/2015/hash/86df7dcfd896fcaf2674f757a2463eba-Abstract.html>
   What happens to careless pipelines over years rather than weeks. Nine pages, no equations,
   uncomfortably accurate.

## Bring to the session

The handout checklist (`lectures/09_feature-engineering-and-pipelines/handouts/`), applied to
your own project design. Assignment 2 is due tonight at 23:59.
