# 🎓 Student Performance Prediction

A Machine Learning project that analyzes student-related factors and classifies students into Low, Medium, and High performance levels using multiple classification algorithms.

## 📌 Project Overview

This project uses the **Student Performance Factors** dataset to explore the relationship between students' academic habits, educational support, and learning environment and their exam scores.

It applies data analysis, visualization, and Machine Learning classification techniques to predict student performance categories.

## 🎯 Objectives

- Analyze the distribution of students' exam scores.
- Explore the relationship between study habits and exam performance.
- Examine previous scores and current exam scores.
- Analyze educational support and learning environment factors.
- Train and compare multiple Machine Learning classification models.

## 📂 Project Structure

```text
Student_Performance_Prediction/
│
├── data/
│   └── StudentPerformanceFactors.csv
│
├── notebooks/
│   └── Student_Performance_Prediction.ipynb
│
├── student_performance_prediction.py
├── README.md
├── requirements.txt
└── .gitignore
```

*Note: Update the file names in this structure if your actual repository uses different names.*

## 📊 Dataset

**Dataset:** Student Performance Factors

The dataset includes information about:

- Study hours and attendance
- Sleep hours and physical activity
- Previous scores
- Parental involvement and access to resources
- Teacher quality and tutoring sessions
- Internet access, school type, and family income
- Other student-related factors

**Target variable:** `Performance_Level`

The project defines three performance categories based on exam scores:

| Performance Level | Exam Score |
|---|---|
| Low | 64 or below |
| Medium | 65–69 |
| High | 70 or above |

These are project-defined categories, not official academic grades.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow

1. Load and inspect the dataset.
2. Check missing values and duplicate records.
3. Clean the dataset.
4. Perform exploratory data analysis (EDA).
5. Visualize exam score distributions.
6. Analyze study habits and educational factors.
7. Create performance categories.
8. Encode categorical features.
9. Split the dataset into training and testing sets.
10. Apply feature scaling.
11. Train and evaluate classification models.
12. Compare model accuracy and analyze the confusion matrix.

## 🤖 Machine Learning Models

Four classification algorithms are used:

1. **Logistic Regression** — a classification algorithm that estimates class probabilities.
2. **K-Nearest Neighbors (KNN)** — predicts classes using nearby training examples.
3. **Gaussian Naive Bayes** — uses probability distributions and Bayes' theorem.
4. **Random Forest** — combines multiple decision trees for classification.

## 📈 Model Evaluation

The models are evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

The model with the highest test accuracy is selected as the best-performing model according to that metric.

*Actual model performance metrics should be added after running the notebook.*

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mridul2172/Student_Performance_Prediction.git
```

### 2. Navigate to the project folder

```bash
cd Student_Performance_Prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook inside the `notebooks/` directory and execute the cells in order.

Alternatively, run the Python script:

```bash
python student_performance_prediction.py
```

Ensure the dataset path in the script matches your project folder structure.

## 🔍 Key Learning Outcomes

- Data cleaning and preprocessing
- Exploratory data analysis
- Data visualization
- Categorical feature encoding
- Feature scaling
- Classification model training
- Model comparison and evaluation

## ⚠️ Limitations

- The performance categories are based on manually defined score thresholds.
- The results depend on the dataset and selected features.
- Observed relationships do not establish causation.
- The model predicts performance categories rather than exact exam scores.

## 👨‍💻 Author

**Mridul Tiwari**

- GitHub: [@mridul2172](https://github.com/mridul2172)
- Project Repository: [Student Performance Prediction](https://github.com/mridul2172/Student_Performance_Prediction)

---

⭐ If you find this project useful, consider giving the repository a star!