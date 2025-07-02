# Credit Card Fraud Detection

This project focuses on detecting fraudulent transactions in credit card data using machine learning techniques. The primary goal is to build a classification model that can distinguish between legitimate and fraudulent transactions with high accuracy, considering the highly imbalanced nature of the dataset.

## 🧠 Project Overview

Credit card fraud detection is a common challenge in the financial sector. Due to the confidential nature of the transaction data and the imbalance (very few fraud cases), it presents a good opportunity to apply anomaly detection and classification techniques.

This notebook covers:

* Data loading and preprocessing
* Exploratory Data Analysis (EDA)
* Addressing class imbalance using SMOTE
* Model training using several ML algorithms
* Performance evaluation with confusion matrix and ROC curve

---

## 📂 Dataset

* **Source:** [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
* **Records:** 284,807 transactions
* **Fraud Cases:** 492 (0.172% of all transactions)
* **Features:**

  * Time, Amount, V1 to V28 (PCA transformed)
  * Target: `Class` (0 = Non-Fraud, 1 = Fraud)

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

## 🔍 Exploratory Data Analysis

* Data distribution inspection
* Correlation matrix to understand feature relationships
* Class imbalance analysis (extremely skewed)
* Visualizations of amount distributions in fraud and non-fraud cases

---

## ⚙️ Model Building

* **Resampling:** Used SMOTE to address class imbalance.
* **Models Tested:**

  * Logistic Regression
  * Decision Tree
  * Random Forest
  * XGBoost (if used)
* **Evaluation Metrics:**

  * Accuracy
  * Precision, Recall, F1-score
  * ROC-AUC
  * Confusion Matrix

---

## 📈 Results

* **Best performing model:** (Replace with actual model if known, e.g., Random Forest)
* **AUC Score:** XX.XX
* **Recall on fraud class:** XX%

The resampling technique (SMOTE) significantly improved the model's ability to detect fraudulent cases.

---

## 📌 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/CREDIT_CARD_FRAUD_DETECTION.git
   cd CREDIT_CARD_FRAUD_DETECTION
   ```

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook CREDIT_CARD_FRAUD_DETECTION.ipynb
   ```

---

## 📑 Author

**Trisha Jaiswal**
📧 Email: [tjaiswal644@gmail.com](mailto:tjaiswal644@gmail.com)
🌍 Location: Rourkela, India
🔗 [GitHub](https://github.com/trishajais)
🔗 [LinkedIn](https://linkedin.com/in/trisha-jaiswal)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
