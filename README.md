# medical-diabetes-predictor
A machine learning project for diabetes prediction with focus on optimizing recall metrics through ANN &amp; PCA algorithms.
# README for Diabetes Classification Project

## Project Overview

This Jupyter notebook (`reg.ipynb`) contains a machine learning classification project focused on predicting diabetes based on medical data. The project demonstrates the implementation of various classification models with a particular emphasis on improving the Recall metric.

## Dataset

The project utilizes a dataset containing medical predictors for diabetes. The dataset likely includes features such as:
- Glucose levels
- Blood pressure
- BMI (Body Mass Index)
- Age
- Other relevant medical indicators

The target variable is binary, indicating the presence (1) or absence (0) of diabetes.

## Models Implemented

The notebook includes implementation and evaluation of multiple classification models:
- Multi-Layer Perceptron
- Principal Component Analysis


## Key Features

1. **Data Preprocessing**
   - Data cleaning and normalization
   - Feature selection and engineering
   - Handling missing values
   - Train-test splitting

2. **Model Training**
   - Training multiple classification models
   - Hyperparameter tuning
   - Cross-validation

3. **Model Evaluation**
   - Confusion matrix analysis
   - Performance metrics:
     - Accuracy
     - Precision
     - Recall (with special focus)
     - F1-Score
   - ROC curves and AUC

4. **Class Imbalance Handling**
   - Techniques for addressing imbalanced classes
   - Resampling methods (SMOTE, undersampling)
   - Class weighting

5. **Threshold Optimization**
   - Adjusting prediction thresholds to improve Recall
   - Precision-Recall trade-off analysis

## Performance Issues and Solutions

The project addresses common challenges in medical diagnostic classification:
- Improving Recall for better identification of positive cases
- Handling imbalanced datasets
- Optimizing model parameters for medical diagnostics
- Exploring different algorithms to find the best performing model

## Requirements

To run this notebook, you need the following libraries:
```
Python 3.x
Jupyter
NumPy
Pandas
Scikit-learn
Matplotlib
```

## Usage

1. Clone the repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook reg.ipynb
   ```
4. Run the cells in sequence to reproduce the analysis

## Results

The notebook provides detailed analysis of each model's performance with particular attention to:
- Model comparison based on multiple metrics
- Confusion matrices visualization
- Feature importance analysis
- ROC and Precision-Recall curves

## Conclusions

The project demonstrates:
- The effectiveness of various classification algorithms for diabetes prediction
- Techniques to improve Recall in medical diagnostics
- The importance of appropriate model selection and parameter tuning
- The challenges of working with potentially imbalanced medical datasets

## Future Work

Potential improvements and extensions:
- Testing additional advanced algorithms
- Deep learning approaches
- More extensive feature engineering
- Ensemble methods for improved performance

## License

[Creative Commons (CC)](http://creativecommons.org/licenses/by/4.0)

## Contact

[AMpoet](https://github.com/AMPoet)
