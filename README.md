# Titanic Survival Prediction --- Machine Learning Project

A supervised machine learning project exploring Titanic passenger data
and comparing classification models to predict passenger survival.

## Project Overview

This notebook covers exploratory data analysis, data preprocessing,
model training, and classification evaluation. It was developed in
Google Colab as an academic machine learning project.

## Objectives

-   Explore passenger features and their relationship with survival.
-   Inspect missing values, distributions, and categorical variables.
-   Prepare features for classification.
-   Compare several machine learning approaches.
-   Evaluate model performance using classification metrics and
    visualizations.

## Methods and Models

The notebook includes:

-   **Exploratory Data Analysis:** Pandas, Matplotlib, and Seaborn
-   **Preprocessing:** missing-value handling, categorical encoding,
    outlier detection, and feature scaling
-   **Gaussian Naive Bayes**
-   **K-Nearest Neighbors (KNN)**
-   **Support Vector Machine (SVM)** with hyperparameter-search
    experiments
-   **Artificial Neural Network (ANN):** TensorFlow/Keras
-   **Evaluation:** accuracy, classification reports, confusion
    matrices, and training/validation curves

## Technology Stack

-   Python
-   Pandas and NumPy
-   Matplotlib and Seaborn
-   scikit-learn
-   TensorFlow / Keras
-   Google Colab / Jupyter Notebook

## Repository Contents

-   `ML_Final_Project.ipynb` --- the original analysis and modeling
    notebook
-   `README.md` --- project overview and instructions

## Dataset

The notebook currently expects two CSV files:

-   `titanic.csv`
-   `test.csv`

These files are not included in this repository by default. Add the
dataset source and usage instructions before expecting others to run the
notebook. If the data comes from Kaggle or another source, link to that
source and follow its terms. Do not upload data that you do not have
permission to redistribute.

The current notebook uses local CSV filenames. You may need to update
the loading cells to match the folder structure you choose, for example:

``` python
df = pd.read_csv("data/titanic.csv")
test_df = pd.read_csv("data/test.csv")
```

Only use those paths after placing the corresponding files in a `data/`
folder.

## How to Run

1.  Download or clone this repository.
2.  Obtain the dataset from the original source and place the required
    CSV files in the expected location.
3.  Open `ML_Final_Project.ipynb` in Google Colab or Jupyter Notebook.
4.  Install any missing dependencies if prompted.
5.  Run the notebook from top to bottom.

**Reproducibility note:** The notebook has not yet been fully refactored
or independently rerun from a clean environment. Some preprocessing and
model-selection steps should be revised before the reported metrics are
treated as reliable final performance.

## Results

The original notebook contains a comparison summary with accuracy values
of approximately **75.7%**, **79.8%**, and **82%**, and describes the
third report as the strongest. The summary does not clearly map every
value to a specific model and evaluation protocol, so these figures are
recorded here as results reported in the original notebook, not as
independently verified benchmark results.


## Project Context

This is an academic machine learning project focused on learning and
comparing classification techniques. The notebook should be updated and
rerun before presenting its performance as a final, production-ready
model.
