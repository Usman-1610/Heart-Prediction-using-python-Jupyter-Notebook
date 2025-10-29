# 🩺 Heart Disease Prediction using Machine Learning

## 📘 Project Overview
Cardiovascular disease is one of the leading causes of death worldwide — but **early detection can save lives**.  
This project uses **Machine Learning** to predict the likelihood of heart disease based on clinical features from **303 patient health records**.

The analysis includes:
- Data preprocessing and statistical exploration  
- Feature correlation and importance analysis  
- Predictive modeling using **Logistic Regression**  
- Model evaluation using accuracy, confusion matrix, and ROC curve  

---

## 🧠 Key Insights
- **Chest Pain Type (cp)** and **Maximum Heart Rate (thalach)** are the strongest predictors  
- **ST Depression (oldpeak)** and **Number of Major Vessels (ca)** also show high correlation  
- Logistic Regression achieved **~85% test accuracy**  
- **ROC curve** confirmed reliable model performance  

---

## ⚙️ Tech Stack

| Category | Tools |
|-----------|--------|
| Programming | Python |
| Libraries | NumPy, Pandas, Matplotlib, Seaborn, scikit-learn |
| Environment | Jupyter Notebook |

---

## 📊 Project Workflow
1. **Data Loading & Cleaning**  
   - Handled missing values  
   - Converted categorical data  
   - Standardized numerical features  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions and correlations  
   - Identified key predictors of heart disease  

3. **Modeling**  
   - Logistic Regression implemented using scikit-learn  
   - Trained on 80% of data, tested on 20%  

4. **Evaluation**  
   - Accuracy, precision, recall, F1-score  
   - ROC-AUC curve to validate model performance  

---

## 🚀 Results

| Metric | Value |
|--------|--------|
| Accuracy | 85% |
| ROC-AUC | 0.87 |
| Strongest Predictors | cp, thalach, oldpeak, ca |

---

## 💡 Future Improvements
- Include additional patient datasets for better generalization  
- Compare models (Random Forest, XGBoost, SVM)  
- Build a simple web dashboard for real-time prediction  

---

## 🩸 Key Takeaway
Even basic patient health indicators can help **predict heart disease risk early** — enabling doctors to move from **reactive treatment to proactive prevention**.

---

## 📂 Repository Structure
```
Heart-Prediction-using-python-Jupyter-Notebook/
│
├── Heart Prediction.ipynb       # Jupyter Notebook (main analysis)
├── dataset.csv                  # (if applicable)
└── README.md                    # Project documentation
```

---

## 🔗 Links
- **LinkedIn Post:** [Heart Disease Prediction Project](https://lnkd.in/dBPS4A-f)  
- **Author:** [M. Usman](https://github.com/Usman-1610)

---

## 🏷️ Tags
`#MachineLearning` `#DataScience` `#HealthcareAI` `#LogisticRegression` `#Python` `#PredictiveAnalytics` `#AIinMedicine`
