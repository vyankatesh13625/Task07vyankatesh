# Task07vyankatesh
##  Objective
Use SVMs for binary classification using both linear and RBF kernels, visualize decision boundaries, and tune hyperparameters.

##  Dataset
Used the Breast Cancer dataset from Scikit-learn:
- 2D subset of features for visualization.
- Full dataset for accuracy testing.

##  Key Learnings
- Margin maximization
- Kernel trick (Linear vs RBF)
- Hyperparameter tuning (`C`, `gamma`)
- Cross-validation evaluation

## Files
- `svm_classification.ipynb` – Main notebook with full implementation
- `requirements.txt` – Python dependencies

##  Results
- Best accuracy (RBF): ~97%
- Best parameters: `C=10`, `gamma=0.1`

##  Libraries
- scikit-learn
- matplotlib
- numpy
