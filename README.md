# Titanic Survival Prediction with Bagging and Random Forests

This project demonstrates how to apply ensemble learning techniques—Bagging and Random Forests—on the Titanic dataset. The tutorial covers data exploration, preprocessing, model training, evaluation, and feature importance visualization.

## Files Included

- final_titanic_rf_bagging_notebook.ipynb: Complete Jupyter Notebook with EDA, modeling, and evaluation
- README.md: Overview and setup instructions
- requirements.txt: List of Python dependencies required to run the notebook

## Dataset

The Titanic dataset is sourced via the `seaborn` library. It contains demographic and travel information about passengers, with a target variable indicating whether a passenger survived.

## Learning Objectives

- Explore class imbalance and survival correlations via EDA
- Clean and preprocess tabular data
- Train and evaluate a Decision Tree, Bagging Classifier, and Random Forest Classifier
- Visualize feature importances to interpret the model

## Setup Instructions

1. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Open the notebook:
   ```
   jupyter notebook final_titanic_rf_bagging_notebook.ipynb
   ```

## References

- Breiman, L. (2001). Random Forests. https://doi.org/10.1023/A:1010933404324
- Scikit-learn Documentation: https://scikit-learn.org/stable/modules/ensemble.html
- Seaborn Titanic Dataset: https://github.com/mwaskom/seaborn-data

## License

MIT License
