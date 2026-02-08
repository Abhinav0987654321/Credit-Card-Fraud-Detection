# 💳 Credit Card Fraud Detection using Machine Learning

This project implements a **Credit Card Fraud Detection system** using Logistic Regression to classify transactions as fraudulent or legitimate.

The dataset used is highly imbalanced, so undersampling techniques were applied to create a balanced training dataset.

## 📌 Project Description

Credit card fraud detection is an important problem in the financial industry. This project uses supervised machine learning to identify fraudulent transactions based on transaction features.

The model is trained using Logistic Regression and evaluated using accuracy score.

## 🛠️ Technologies & Libraries Used

* Python
* NumPy
* Pandas
* Scikit-learn

## 📂 Dataset Information

* Dataset: `creditcard.csv`
* Contains legitimate (0) and fraudulent (1) transactions
* Highly imbalanced dataset
* Fraud transactions: 492 cases

## ⚙️ Project Workflow

### 1️⃣ Data Loading

* Loaded dataset using Pandas
* Explored dataset using `.head()`, `.tail()`, `.info()`

### 2️⃣ Data Analysis

* Checked missing values
* Analyzed distribution of legitimate vs fraud transactions
* Statistical analysis using `.describe()` and `.groupby()`

### 3️⃣ Handling Imbalanced Data

* Separated legitimate and fraud transactions
* Applied **undersampling** to create balanced dataset
* Combined fraud cases with equal number of legitimate transactions

### 4️⃣ Feature & Target Separation

* Features (X): All columns except `Class`
* Target (Y): `Class`

### 5️⃣ Train-Test Split

* 80% training data
* 20% testing data
* Used stratified splitting

### 6️⃣ Model Training

* Algorithm: Logistic Regression
* `max_iter = 1000`

### 7️⃣ Model Evaluation

* Accuracy on Training Data
* Accuracy on Testing Data

---

## 📊 Model Performance

The model was evaluated using:

* Accuracy Score (Training)
* Accuracy Score (Testing)

The project demonstrates effective classification after handling class imbalance through undersampling.

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
```

2. Navigate to the folder:

```bash
cd Credit-Card-Fraud-Detection
```

3. Install required libraries:

```bash
pip install numpy pandas scikit-learn
```

4. Place `creditcard.csv` dataset in the project directory.

5. Run the script:

```bash
python credit_card_fraud_detection.py


## 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── credit_card_fraud_detection.py
├── creditcard.csv
└── README.md
```
---
## 🚀 Future Improvements

* Implement Random Forest and XGBoost models
* Use SMOTE instead of undersampling
* Evaluate using Precision, Recall, F1-score & ROC-AUC
* Deploy using Flask or Streamlit

---

## 👨‍💻 Author

**Abhinav Mishra**
Aspiring Machine Learning Engineer
Python | Data Science | AI Enthusiast

