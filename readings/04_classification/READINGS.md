# Session 4 readings - Classification

## Core

1. **ISLR chapter 4 ("Classification"), sections 4.1-4.3.**
   <https://www.statlearning.com/>
   Logistic regression, the log-odds interpretation, and multi-class. Sections 4.4-4.5 (LDA,
   QDA, naive Bayes) are optional context we will not test.

2. **Saito & Rehmsmeier, "The Precision-Recall Plot Is More Informative than the ROC Plot
   When Evaluating Binary Classifiers on Imbalanced Datasets", _PLOS ONE_, 2015.**
   <https://doi.org/10.1371/journal.pone.0118432>
   Directly relevant to Assignment 2: why AUC can look reassuring on a rare-positive problem
   and what to report instead.

## Optional

3. **Ng et al., CS229 lecture notes (Stanford), the logistic regression and generalised
   linear models sections.** <https://cs229.stanford.edu/main_notes.pdf>
   The derivation at a brisker pace, including where the clean gradient `X'(p - y)` comes
   from as a property of the exponential family.

## Bring to the session

For one binary decision in your field, state the relative cost of a false positive and a
false negative. We will use those numbers to choose thresholds in the lab.
