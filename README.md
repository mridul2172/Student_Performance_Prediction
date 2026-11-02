# Fake Job & Internship Detection Using Machine Learning

A Machine Learning project that classifies job postings as potentially fraudulent or non-fraudulent using four classification algorithms. The project compares model performance to understand which approach works best for identifying suspicious job postings.

## Project Overview

Fake job postings can mislead job seekers and expose them to potential scams. This project uses historical job-posting data to learn patterns associated with fraudulent listings and predict whether an unseen posting is likely to be fraudulent.

**Project type:** Predictive Analytics / Machine Learning  
**Task:** Binary Classification  
**Language:** Python

## Objectives

- Analyze and preprocess job-posting data.
- Explore patterns in fraudulent and genuine job listings.
- Train four machine learning classification models.
- Compare model performance using standard evaluation metrics.
- Identify the strengths and limitations of each classifier.

## Dataset

**Dataset:** [Real or Fake? Fake Jobposting Prediction](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)

The dataset contains approximately 17,880 job postings and 18 columns.

| Dataset information | Details |
|---|---|
| Total job postings | 17,880 |
| Genuine postings | 17,014 |
| Fraudulent postings | 866 |
| Target column | `fraudulent` |
| Classification type | Binary classification |

Target labels:

- `0` — Non-fraudulent posting
- `1` — Fraudulent posting

The dataset is imbalanced, with fraudulent postings representing a small proportion of the records. Therefore, model evaluation considers precision, recall and F1-score in addition to accuracy.

## Machine Learning Models

Four classification algorithms are implemented:

1. **Logistic Regression** — A classification algorithm that estimates class probabilities.
2. **Decision Tree Classifier** — Learns decision rules from job-posting features.
3. **Random Forest Classifier** — Combines multiple decision trees to make predictions.
4. **Linear Support Vector Classifier (LinearSVC)** — Learns a decision boundary to separate the classes.

All four models use the same stratified 80:20 train-test split, with `random_state=42`, and a consistent preprocessing pipeline.

## Project Workflow

### 1. Data Understanding
- Inspect dataset dimensions, data types and columns.
- Examine missing values and duplicate records.
- Analyze the distribution of the target classes.

### 2. Exploratory Data Analysis
- Compare genuine and fraudulent postings.
- Investigate missing values.
- Explore employment types and remote-work patterns.
- Visualize relevant trends using charts.

### 3. Data Preprocessing
- Handle missing values.
- Process categorical and numerical features.
- Convert relevant text fields into numerical features where applicable.
- Apply preprocessing consistently to avoid data leakage.

### 4. Model Training
Train the four classifiers using the prepared training data.

### 5. Model Evaluation
Compare the models using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

### 6. Model Comparison
Present the evaluation results in a comparison table and visualizations to identify the most suitable model.

## Technology Stack

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Getting Started

### Prerequisites

Install Python 3 and Git. Download the dataset from the Kaggle link above.

### 1. Clone the repository

```bash
git clone https://github.com/mridul2172/fake-job-detection.git
cd fake-job-detection
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Prepare the dataset

Download the dataset from Kaggle and place the CSV file in the location expected by the notebook or training script. Verify the filename and dataset path before running the code.

### 5. Run the project

Open the Jupyter Notebook included in the repository and execute the cells in order.

If your repository uses a Python script instead of a notebook, run the appropriate script for your project structure.

## Results and Evaluation

The four classifiers are evaluated on the same test set using consistent metrics.

The final comparison should report the actual results produced by the code. No model is assumed to be the best before evaluation.

| Model | Accuracy | Precision | Recall | F1-score |
|---|---|---|---|---|
| Logistic Regression | Run evaluation | Run evaluation | Run evaluation | Run evaluation |
| Decision Tree | Run evaluation | Run evaluation | Run evaluation | Run evaluation |
| Random Forest | Run evaluation | Run evaluation | Run evaluation | Run evaluation |
| LinearSVC | Run evaluation | Run evaluation | Run evaluation | Run evaluation |

Replace these placeholders with the actual evaluation results after running the project.

## Limitations

- Model predictions depend on the quality and representativeness of the training data.
- The dataset contains substantially more genuine postings than fraudulent postings.
- New fraud patterns may differ from those in historical data.
- A predicted fraudulent label is not proof that a job is fraudulent.
- The model is intended for educational and research purposes, not as a definitive job-verification service.

## Future Improvements

- Improve text feature extraction.
- Evaluate class-imbalance handling techniques.
- Add explainability for model predictions.
- Test performance on newer job-posting data.
- Improve the model comparison and reporting process.

## Academic Purpose

This project demonstrates the application of Predictive Analytics concepts, including data preprocessing, exploratory data analysis, classification algorithms and model performance evaluation.

**Author:** Mridul Tiwari  
**GitHub:** [mridul2172](https://github.com/mridul2172)

---

*Disclaimer: This project is for educational purposes only. Predictions should not be treated as definitive evidence that a job posting is genuine or fraudulent.*
