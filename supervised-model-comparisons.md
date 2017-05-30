# Supervised Model Comparisons

## Logistic Regression (LR) vs. Linear Discriminant Analysis (LDA)

* LDA assumes that samples from each label come from a normal distribution
* Assuming population is indeed normal, small sample sizes might have high variance; you might get a skewed sample from your (actually reflectively symmetric) distribution. LDA encodes this assumption and will work better than LR here, which adjusts to the skewness.
* Without this assumption, skewness may be indicative of actual population skewness. Here LR will accurately capture this.
* Skewness (no reflective symmetry or bimodality) will mess with LDA regardless of sample size; LR is more robust to this since it is more flexible in the distributions it allows.

## Logistic Regression vs. SVM

TODO
