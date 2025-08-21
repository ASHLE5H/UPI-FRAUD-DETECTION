# UPI Fraud Detection

A machine learning project that detects fraudulent UPI (Unified Payments Interface) transactions using data preprocessing, feature engineering, and classification models. The project demonstrates the full ML pipeline from data collection to model deployment.

---

## 📌 Project Overview
Digital payments via UPI are growing rapidly in India, but so are fraudulent transactions. This project applies machine learning techniques to:
- Analyze UPI transaction data
- Engineer relevant features
- Build a fraud detection model
- Save the trained model (`upi_model.pkl`) for future inference

---

## 📂 Repository Structure

├── ML_PROJECT.ipynb # Main Jupyter Notebook with complete workflow

├── Upi.xlsx # Dataset (UPI transactions)

├── upi_model.pkl # Saved ML model

└── .ipynb_checkpoints # Jupyter checkpoints (can be ignored)

---


---

## ⚙️ Workflow
1. **Data Collection**  
   Load UPI transactions dataset (`Upi.xlsx`).

2. **Data Preparation & Cleaning**  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize/scale features  

3. **Exploratory Data Analysis (EDA)**  
   - Fraud vs. Normal transaction distribution  
   - Correlation heatmaps  
   - Transaction pattern analysis  

4. **Feature Engineering**  
   - Create new fraud-indicating features  
   - Balance fraud vs. normal transaction data  

5. **Model Training**  
   - Train ML models (e.g., Logistic Regression, Random Forest, etc.)  
   - Evaluate with metrics like Accuracy, Precision, Recall, F1-score  

6. **Model Saving**  
   -Save the final trained model as `upi_model.pkl`.

---

## 📊 Results
- The model successfully distinguishes fraudulent vs. normal UPI transactions.
- Metrics such as accuracy, precision, and recall indicate strong performance.  
  *(Add actual numbers here from your notebook results.)*

---


---
## Install dependencies:

  pip install -r requirements.txt

Requirements

  -Python 3.8+

  -pandas

  -numpy

  -seaborn

  -matplotlib

  -scikit-learn

  -pyforest

  -openpyxl


## 🔮 Future Work
  Improve fraud detection with deep learning methods
  Integrate with a live UPI transaction dataset for continuous learning


