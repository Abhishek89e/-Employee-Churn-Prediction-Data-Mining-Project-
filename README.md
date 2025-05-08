# 👥 Employee Churn Prediction – Data Mining Project

Why do employees leave? And more importantly—can we see it coming?

This project, completed during my MSc in Data Analytics at Dublin Business School, tackles a critical HR challenge: employee churn. Using real-world inspired HR data from MedView Pharmaceuticals, the goal was to build predictive models that help organizations identify at-risk employees early enough to intervene.

## 🔍 Objective
- Analyze employee data to predict future attrition risk.
- Identify key features contributing to churn.
- Build classification models to achieve 75%+ accuracy, precision, and recall.

## 📊 Dataset
- 1,470 employee records
- 28 features including demographics, job role, salary, overtime, satisfaction levels
- Target variable: `PastEmployee (Yes/No)`

## 🧠 Techniques Used
- Logistic Regression
- Decision Trees
- Random Forest (Best accuracy: **96%**)
- XGBoost (Best F1 score in cross-validation)
- Stratified train-test split (80/20)
- Handling class imbalance using oversampling

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Feature Importance

## 🔑 Key Insights
- **Overtime**, **Job level**, and **Stock options** were top churn indicators.
- Random Forest was most accurate, but XGBoost performed better in generalizability.
- Results were validated through simulated HR feedback and pilot testing.

## 🛠 Tools & Libraries
- Python (Scikit-learn, XGBoost, Pandas, Matplotlib)
- Jupyter/Colab Notebooks
- RapidMiner (Auto Model benchmarking)

## 📌 Final Thought
The true power of this project lies in how data can empower HR to retain top talent through data-backed decisions.

