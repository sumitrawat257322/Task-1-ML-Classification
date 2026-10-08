# InternSpark Task 1 - ML Classification

## Objective

Build and evaluate machine learning classification models using preprocessing,
train-test split, cross-validation, and multiple evaluation metrics.

## Dataset

Breast Cancer Wisconsin Dataset from Scikit-learn.

- Samples: 569
- Features: 30
- Target Classes: 2
- Missing Values: 0

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Machine Learning Models

1. Logistic Regression
2. Random Forest Classifier

## Preprocessing

The dataset was divided into training and testing sets using an 80/20 split.
StandardScaler was used for feature scaling.

## Cross-Validation

5-Fold Cross-Validation was performed on the training data.

Mean Cross-Validation Accuracy:

**98.02%**

## Model Evaluation

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 98.25% | 98.61% | 98.61% | 98.61% | 99.54% |
| Random Forest | 95.61% | 95.89% | 97.22% | 96.55% | 99.39% |

## Best Model

Logistic Regression achieved the best overall performance on the test dataset,
with an accuracy of **98.25%** and ROC-AUC of **99.54%**.

## Visualizations

The project includes:

- Confusion Matrix
- ROC Curve
- Model Comparison Table

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. The dataset is loaded directly using Scikit-learn.
4. No external dataset download is required.

## Project Structure

```text
Task-1-ML-Classification/
│
├── InternSpark_Task_1_ML_Classification.ipynb
├── README.md
└── report.pdf