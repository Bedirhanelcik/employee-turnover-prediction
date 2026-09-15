# Employee Turnover Prediction

A Machine Learning project focused on predicting employee turnover using classification algorithms. This project analyzes employee-related factors and compares different machine learning models to identify the most effective approach for predicting whether an employee is likely to leave a company.

---

## Project Overview

Employee turnover is a major challenge for organizations. High turnover increases recruitment costs, reduces productivity, and impacts team performance.

This project aims to predict employee attrition by analyzing employee information such as experience, engagement score, salary, promotion history, work-life balance, and other HR-related features.

---

## Dataset

The dataset contains **6,500 employee records** with **30 different features**.

Some of the most important features include:

- Employee Age
- Years of Experience
- Monthly Income
- Bonus Percentage
- Engagement Score
- Work-Life Balance
- Performance Rating
- Promotion History
- Training Hours
- Department
- Job Role
- Attrition Status (Target Variable)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Models

The following classification algorithms were implemented and evaluated:

- Logistic Regression
- Random Forest Classifier

---

## Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **70.69%** |
| Random Forest | **70.77%** |

The Random Forest model achieved slightly better overall performance than Logistic Regression.

---

## How to Run

1. Clone this repository

```bash
git clone https://github.com/Bedirhanelcik/employee-turnover-prediction.git
```

2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```
employee_attrition_prediction.ipynb
```

4. Run all cells.

---

## Project Structure

```
employee-turnover-prediction/
│
├── employee_attrition_prediction.ipynb
├── employee_turnover_dataset.csv
└── README.md
```

---

## Future Improvements

- Hyperparameter Optimization
- Feature Engineering
- Cross Validation
- XGBoost Implementation
- LightGBM Implementation
- Model Deployment with Flask or FastAPI

---

## Author

**Bedirhan Elçik**

Management Information Systems Student

GitHub: https://github.com/Bedirhanelcik
