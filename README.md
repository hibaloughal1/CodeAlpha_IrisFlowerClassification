# Iris Flower Classification 🌸

## Project Overview

This project focuses on building a machine learning classification system to identify Iris flower species based on their physical measurements.

Using the famous Iris dataset, the objective is to classify flowers into three categories:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

The project follows a complete machine learning workflow, from exploratory data analysis to model optimization and prediction on new observations.

## Dataset

The dataset contains 150 observations, with 50 samples for each species.

Four numerical features are used:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

## Project Workflow

1. **Exploratory Data Analysis (EDA):** Dataset inspection, statistical analysis, distributions and visualizations.
2. **Data Preprocessing:** Feature-target separation, stratified train-test split and feature standardization.
3. **Model Training:** Logistic Regression, K-Nearest Neighbors (KNN) and Random Forest.
4. **Model Evaluation:** Accuracy, Precision, Recall, F1-score, classification reports and confusion matrices.
5. **Hyperparameter Optimization:** GridSearchCV with stratified 5-fold cross-validation and Scikit-learn Pipelines.
6. **Model Saving:** The best optimized model is saved using Joblib.
7. **Prediction:** Testing the saved model on new Iris flower measurements.

## Results

The optimized Logistic Regression model achieved the best performance on the test set.

| Model | Accuracy |
|---|---:|
| Logistic Regression (optimized) | 100% |
| Random Forest (optimized) | 96.67% |
| KNN (optimized) | 93.33% |

*Note: These results are based on a test set of 30 observations. They should not be interpreted as a guarantee of performance on all future data.*

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

## Project Structure

```text
CodeAlpha_IrisFlowerClassification/
├── data/
│   └── Iris.csv
├── models/
│   └── best_iris_model.joblib
├── notebooks/
│   ├── 01_iris_analysis.ipynb
│   └── 02_iris_preprocessing_modeling.ipynb
│
├── .gitignore
├── README.md
└── requirements.txt
```

## Installation and Execution

Clone the repository:

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd CodeAlpha_IrisFlowerClassification
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebooks in the following order:

1. `01_iris_analysis.ipynb`
2. `02_iris_preprocessing_modeling.ipynb`

## Conclusion

This project demonstrates the implementation of a complete machine learning classification workflow, including exploratory analysis, preprocessing, model comparison, hyperparameter optimization and prediction on new observations.

It was completed as part of the CodeAlpha Data Science Internship.

---

**Author:** Hiba Loughzal  
**Project:** CodeAlpha – Iris Flower Classification
