# MachineLearningHealthRiskClassification
# Health Risk Classification

This project is about predicting whether a patient has diabetes or not using machine learning.

For this project, I used the **Pima Indians Diabetes Dataset** and applied two classification models:

- Support Vector Machine (SVM)
- Decision Tree

## Dataset

The dataset contains different health-related features of patients:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

The target column is `Outcome`:

- `0` = No Diabetes
- `1` = Diabetes

## What I Did

The following steps were performed in the project:

1. Loaded and inspected the dataset.
2. Checked missing values and duplicate records.
3. Treated some zero values as missing values where zero is not a valid medical measurement.
4. Filled missing values using median imputation.
5. Split the data into training and testing sets.
6. Applied feature scaling for SVM.
7. Trained an SVM model.
8. Trained a Decision Tree model.
9. Evaluated both models using different metrics.
10. Compared the results of both models.
11. Checked training and testing accuracy to discuss overfitting.

## Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

The notebook also contains a comparison of the SVM and Decision Tree results.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Files

```text
Health-Risk-Classification/
│
├── Health_Risk_Classification.ipynb
├── diabetes.csv
└── README.md
```

## How to Run

The project was developed in Google Colab.

Open the `.ipynb` file in Google Colab, make sure `diabetes.csv` is available, and run the cells in order.

## Author

**Huzaifa Bin Anas**

B.S. Artificial Intelligence  
Dawood University of Engineering & Technology
