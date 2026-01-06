# loan_status_prediction


## 📌 Project Overview

This project focuses on predicting **loan approval status** using **Machine Learning classification techniques**.  
Loan status prediction helps financial institutions reduce risk by identifying whether a loan application should be **Approved or Rejected** based on applicant details.

This is a **Supervised Machine Learning – Classification** project.

---

## 🎯 Objectives

- Analyze loan applicant data  
- Clean and preprocess the dataset  
- Train a machine learning model  
- Predict loan approval status  
- Evaluate model performance  

---

## 🧠 Machine Learning Model Used

- Support Vector Machine (SVM – Linear Kernel)

---

## 🛠️ Technologies & Libraries Used

- Python  
- Pandas – data manipulation  
- NumPy – numerical operations  
- Scikit-learn – machine learning & evaluation  
  - SVC  
  - StandardScaler  
  - Train-Test Split  
  - Accuracy Score  

---

## 📂 Dataset Information

- **Dataset Name**: Loan Status Dataset  
- **Source**: Public / Kaggle Dataset  
- **Target Column**: `Loan_Status`  

### Target Values
- `1` → Loan Approved  
- `0` → Loan Not Approved  

---

## 🔄 Project Workflow

1. Import required libraries  
2. Load the dataset  
3. Data cleaning  
4. Handle missing values  
5. Encode categorical features  
6. Feature scaling using `StandardScaler`  
7. Train-test split  
8. Model training using SVM  
9. Model evaluation  
10. Prediction on new data  

---

## 📊 Evaluation Metrics

- Accuracy Score  

---

## 🚧 Challenges Faced

- Handling missing values  
- Encoding categorical variables  
- Feature scaling for SVM  
- Avoiding data leakage during preprocessing  

---

## ✅ Results

- The SVM model successfully predicts loan approval status  
- Feature scaling improved model performance  
- Linear kernel provided stable and interpretable results  

---

## 📌 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/loan-status-prediction.git
