# DataSage AI  
### AI-Powered Dataset Quality & AutoML Platform

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![ML](https://img.shields.io/badge/MachineLearning-AutoML-green)

---

DataSage AI is an AI-powered dataset analysis and AutoML platform built using **Streamlit, Scikit-learn, and Pandas**. It automatically evaluates dataset quality, detects data issues, suggests cleaning strategies, and discovers the best-performing machine learning models.

This platform helps data scientists, analysts, and ML practitioners quickly understand their data and accelerate the machine learning workflow.

---

## Application Screenshots

### Dataset Overview
![Dataset Overview](screenshots/overview.png)

### Data Quality Analysis
![Data Quality](screenshots/data_quality.png)

### EDA Report
![EDA Report 1](screenshots/eda_report1.png)  
![EDA Report 2](screenshots/eda_report2.png)

### Auto Data Cleaning
![Auto Fix](screenshots/auto_fix_dataset.png)

### ML Model Analysis
![ML Analysis](screenshots/ml_analysis.png)

### Feature Importance
![Feature Importance](screenshots/feature_importance.png)

### AutoML Results
![AutoML](screenshots/auto_ml.png)

---

## Problem Statement

Poor dataset quality is one of the biggest reasons machine learning models fail.

Data scientists spend a significant amount of time handling:
- Missing values  
- Duplicate records  
- Outliers  
- Skewed distributions  
- Data leakage  

Manual data exploration and cleaning can be time-consuming and inefficient.

---

## Solution

DataSage AI automates the entire dataset analysis pipeline by:

- Analyzing dataset quality  
- Detecting data issues  
- Suggesting intelligent cleaning strategies  
- Generating automated reports  
- Recommending ML models  
- Running AutoML to find the best model  
- Providing explainability insights  

All through an interactive Streamlit dashboard.

---

## Key Features

### Dataset Overview
- Upload CSV or Excel datasets  
- Automatic dataset statistics  
- Interactive dataset preview  

---

### Automated EDA Report
- Full EDA using **ydata-profiling**  
- Includes:
  - Variable analysis  
  - Correlations  
  - Missing value visualization  
  - Dataset samples  
- Downloadable interactive HTML report  

---

### Dataset Health Scoring
- Evaluates dataset quality based on:
  - Missing values  
  - Duplicate rows  
  - Completeness  
- Outputs a **health score out of 100**  

---

### Data Quality Issue Detection
- Detects:
  - High missing values  
  - Skewed distributions  
  - Potential outliers  

---

### AI Cleaning Suggestions
- Recommends:
  - Missing value handling  
  - Duplicate removal  
  - Encoding strategies  

---

### Automatic Dataset Cleaning
- One-click cleaning:
  - Fill missing values  
  - Encode categorical variables  
  - Remove duplicates  

---

### ML Model Recommendation
- Trains multiple models:
  - Logistic Regression  
  - Random Forest  
  - Decision Tree  
  - SVM  
  - KNN  
- Compares performance  

---

### AutoML Pipeline
- Automatically selects best model  
- Outputs:
  - Best model  
  - Accuracy  
  - Comparison table  

---

### Feature Importance (Explainability)
- Uses Random Forest  
- Identifies most important features  

---

### Data Leakage Detection
- Detects high correlation with target  
- Prevents model overfitting issues  

---

### AI Dataset Report
- Generates human-readable insights:
  - Dataset size  
  - Missing values  
  - Duplicates  
  - Key characteristics  

---

## System Architecture
```bash
User Upload
↓
Streamlit UI
↓
Data Processing (Pandas)
↓
Data Quality Engine
↓
AI Suggestions Layer
↓
ML & AutoML Pipeline
↓
Visualization Dashboard
```

---

## Tech Stack

### Programming
- Python  

### Libraries
- Streamlit  
- Pandas  
- NumPy  
- Scikit-learn  
- Plotly  
- ydata-profiling  

### ML Models
- Logistic Regression  
- Random Forest  
- Decision Tree  
- SVM  
- KNN  

---

## Project Structure
```bash
datasage-ai/
│
├── app.py
├── requirements.txt
├── README.md
│
├── utils/
│   ├── auto_fix.py
│   ├── automl_pipeline.py
│   ├── cleaning_suggestions.py
│   ├── data_quality.py
│   ├── dataset_report.py
│   ├── dashboard.py
│   ├── error_detection.py
│   ├── leakage_detector.py
│   ├── model_recommender.py
│   └── explainability.py
│
├── screenshots/
```

---

## Installation & Setup

### Clone the repository
```bash
git clone https://github.com/Saumya-eng/datasage-ai.git
cd datasage-ai
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Run the app
```bash
streamlit run app.py
```

---

## How It Works

1. Upload dataset
2. View dataset overview
3. Analyze data quality
4. Detect issues & suggestions
5. Generate EDA report
6. Run ML model recommendation
7. Execute AutoML
8. View feature importance

---

## Example Datasets

**Titanic Dataset**  
https://www.kaggle.com/datasets/yasserh/titanic-dataset

**Target:** Survived

**Student Performance Dataset**
https://raw.githubusercontent.com/selva86/datasets/master/StudentsPerformance.csv

**Target:** math score

---

## Future Improvements

- Real-time data drift detection  
- Bias detection  
- Deep learning integration  
- Chatbot integration  
- Cloud deployment (AWS/GCP)  
- Automated feature engineering  

---

## Author

**Saumya Verma**  
B.Tech CSE (AI/ML)
