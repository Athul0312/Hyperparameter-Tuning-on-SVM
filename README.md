# Hyperparameter-Tuning-on-SVM
SVM on Iris dataset with manual hyperparameter tuning and visualization

# SVM Hyperparameter Tuning on Iris Dataset

Exploration of SVM performance across different kernel types, regularization strengths, and gamma values using a manual tuning loop on the Iris dataset.

---

## What I Did

- Used `train_test_split` and `StandardScaler` to prepare data
- Tuned:
  - `kernel`: linear, poly, rbf
  - `C`: 10 values between 1 and 5
  - `gamma`: 15 values between 0.1 and 5
- Evaluated test accuracy across all combinations

---

## Results

- **Best kernel:** `'rbf'`
- **Best accuracy:** ~98.3%
- **Robust range:** multiple RBF settings scored ≥98%
- Visualized results with confusion matrix and 3D feature plots

---

## Summary

Tuned SVM hyperparameters manually using nested loops instead of GridSearchCV.  
This showed how kernel choice and regularization affect performance, even on a small dataset.
