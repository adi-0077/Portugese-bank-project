# Portuguese Bank Telemarketing Campaign Analysis 📊

This project focuses on analyzing and building predictive models using the **Portuguese Bank Marketing Dataset**. The goal is to predict whether a client will subscribe to a term deposit based on various attributes collected during direct marketing campaigns.

---

## 📁 Dataset

The dataset is from a real marketing campaign by a Portuguese banking institution, containing information about client attributes, campaign contacts, and outcomes.

- **Rows**: ~41,000
- **Target Variable**: `y` (whether the client subscribed to a term deposit)
- **Data Source**: UCI Machine Learning Repository

---

## 📌 Objectives

- Perform **data preprocessing** and **exploratory data analysis (EDA)**
- Handle **class imbalance** using SMOTE
- Train classification models to predict the target variable
- Evaluate models using metrics like accuracy, ROC-AUC, and recall

---

## 🛠️ Technologies Used

- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (for SMOTE)

---

## 📊 Machine Learning Models Used

- Logistic Regression
- Support Vector Classifier (SVC)
- Decision Tree Classifier

Models were evaluated using:
- **Accuracy**
- **Recall**
- **Confusion Matrix**
- **ROC-AUC Score**

---

## 🔍 Key Findings

- The dataset was **imbalanced**, with far fewer positive cases (term deposit subscriptions).
- SMOTE helped improve the model's ability to detect the minority class.
- Logistic Regression performed well in terms of interpretability and recall.

---

## 📦 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Portugese-bank-project.git
