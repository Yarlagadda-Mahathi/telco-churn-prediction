📉 Telco Customer Churn Prediction

📌 Overview

Customer churn is a major challenge for telecom companies. This project uses Machine Learning to predict whether a customer will leave the service, helping businesses take proactive retention measures.

📂 Dataset

Source:Kaggle (Telco Customer Churn)
Rows:7043
Target:`Churn` (Yes/No)

⚙️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

🔄 Workflow

1. **Data Preprocessing**

   * Converted `TotalCharges` to numeric
   * Handled missing values
   * Dropped `customerID`
   * Encoded categorical features

2. **EDA**

   * Churn distribution
   * Contract type vs churn
   * Tenure & charges analysis

3. **Modeling**

   * Train-test split (80:20)
   * Feature scaling
   * Models used:

     * Logistic Regression
     * Random Forest
     * Decision Tree

4. **Evaluation**

   * Accuracy, Confusion Matrix
   * Classification Report
   * ROC-AUC Score

📊 Results

* **Logistic Regression:** ~80% accuracy
* **Random Forest:** ~79%
* **Decision Tree:** ~72%
* **ROC-AUC:** ~0.85

✅ Conclusion

Logistic Regression performed best and effectively identifies high-risk customers, enabling proactive retention strategies.

