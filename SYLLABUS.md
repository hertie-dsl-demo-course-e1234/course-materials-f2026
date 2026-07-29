# Foundations of Machine Learning (Demo) - E1234

**Semester:** Fall 2026 (8 September - 18 December 2026)
**Sessions:** Tuesdays, 10:00-12:00 (materials released Tuesdays 08:00)
**Language of instruction:** English
**Prerequisites:** introductory statistics; comfort with Python (or R) at the level of
writing a function and reading a data frame.

> This is a **demo course**. The content is real and teachable, but the people, students,
> grades and dates are fictional - it exists to demonstrate the Data Science Lab teaching
> pipeline end to end.

## Course description

Machine learning is now a routine part of policy analysis, and the difference between a
useful model and a misleading one is usually not the algorithm - it is the modelling
judgement around it. This course builds that judgement from the ground up. We derive a
small number of core methods (linear and logistic regression, regularisation, trees and
ensembles, clustering, a minimal neural network) and, in every session, pair the
derivation with an implementation you write yourself and then a library version you can
defend. By the end you should be able to take a tabular dataset, build a defensible
predictive model, quantify how well it works, and say clearly where it should not be
trusted.

## Learning objectives

By the end of the course, students will be able to:

1. **Frame** a substantive question as a supervised or unsupervised learning problem, and
   state what a good answer would look like before fitting anything.
2. **Implement** ordinary least squares, gradient descent and logistic regression from
   scratch, and explain each line of the update rule.
3. **Diagnose** underfitting and overfitting from learning curves, and control them with
   regularisation and principled model selection.
4. **Apply** trees, ensembles, clustering and dimension reduction with a standard library
   (`scikit-learn` or `tidymodels`) and justify the hyperparameters chosen.
5. **Evaluate** models with metrics that match the decision at hand - not accuracy by
   default - and quantify uncertainty in the estimate.
6. **Assess** a model's distributional impact and documentation, and identify the failure
   modes that a headline metric hides.

## Weekly plan

Each row is one session folder in the materials repo
(`lectures/NN_.../`, `readings/NN_.../`, `labs/NN_.../`).

| # | Date | Session | Lab | Milestone |
|---|------|---------|-----|-----------|
| 1 | 8 Sep | `01_introduction` - what machine learning is (and isn't) | Python/NumPy warm-up (`.ipynb`) | |
| 2 | 15 Sep | `02_linear-regression` - least squares, from geometry to code | Least squares in R (`.Rmd`) | |
| 3 | 22 Sep | `03_gradient-descent` - loss surfaces and learning rates | Writing a descent loop (`.ipynb`) | Assignment 1 released |
| 4 | 29 Sep | `04_classification` - logistic regression and decision thresholds | Thresholds and confusion matrices (`.ipynb`) | |
| 5 | 6 Oct | `05_regularisation-and-model-selection` - bias, variance, ridge, lasso | Ridge, lasso, cross-validation (`.ipynb`) | Assignment 2 released |
| 6 | 13 Oct | `06_trees-and-ensembles` - CART, bagging, random forests, boosting | Trees and forests (`.ipynb`) | Assignment 1 due 13 Oct |
| 7 | 20 Oct | `07_unsupervised-learning` - k-means and PCA | k-means and PCA in R (`.Rmd`) | Project released |
| 8 | 27 Oct | **Midterm exam 10:00-11:00**, then `08_neural-networks` - a network as composed regressions | A two-layer network in NumPy (`.ipynb`) | Midterm 27 Oct |
| 9 | 3 Nov | `09_feature-engineering-and-pipelines` - leakage and the pipeline discipline | Building a leak-free pipeline (`.ipynb`) | Assignment 2 due 3 Nov |
| 10 | 10 Nov | `10_evaluation-and-ethics` - metrics that match the decision, and who bears the error | Subgroup evaluation and a model card (`.ipynb`) | |

Session 8 is shortened: the midterm is written in the first hour, the lecture runs
11:15-12:00, and its lab is the take-home extension.

**After teaching ends:** project clinics (17 Nov), project due 27 Nov, revision sessions
1 and 8 Dec, final exam 15 December 14:00.

## Assessment

| Component | Weight | Form | Due |
|-----------|--------|------|-----|
| Assignment 1 - linear regression from scratch | 15% | individual, Python | 13 Oct, 23:59 |
| Assignment 2 - classification and evaluation | 20% | individual, notebook | 3 Nov, 23:59 |
| Group project - end-to-end modelling report | 25% | groups of 2-3 | 27 Nov, 23:59 |
| Midterm exam | 15% | in class, 60 min | 27 Oct, 10:00 |
| Final exam | 25% | in class, 120 min | 15 Dec, 14:00 |

Assignments are submitted by pushing to `main` in your personal assignment repository -
that push *is* the submission. Marks and feedback are returned privately to your
`grades-<handle>` repository and by email.

## Policies

**Late work.** Each assignment carries a 48-hour grace window (72 hours for the project)
applied silently at grading; work arriving after it scores zero unless you have a
documented extension. Ask *before* the deadline, not after.

**Collaboration.** Discussing ideas is encouraged; submitting someone else's code is not.
For individual assignments, everything you push must be written by you. Name anyone you
worked with in your README - that costs you nothing and protects you.

**Generative AI.** You may use AI assistants for explanation and debugging. You may not
submit generated code you cannot explain line by line; the oral spot-check at the project
clinic assumes you can. Declare AI use in a short note in your README.

**Reproducibility.** Every submission must run top-to-bottom from a clean checkout with the
dependencies listed in your README, using a fixed random seed. A result we cannot reproduce
does not count.

**Attendance and auditors.** Auditors receive released materials and readings, but no
assignment repositories, marks or exam entry.

**Accessibility.** If you need an accommodation, contact the lecturer in the first two
weeks so it can be arranged for exams and deadlines rather than retrofitted.
