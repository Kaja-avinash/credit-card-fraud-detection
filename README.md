# credit-card-fraud-detection
# 📌 Credit Card Fraud Detection

## 🔍 Task Objective

This project focuses on building a machine learning model that detects fraudulent credit card transactions using transaction data. The goal is to:

- ✅ Accurately identify fraudulent transactions  
- ✅ Minimize false positives  
- ✅ Provide insights into model performance and misclassifications  
- ✅ Visualize key metrics and feature importance  

---

## 📁 Dataset Used

- `fraudTrain.csv`  
- `fraudTest.csv`  

> 📂 Dataset Source: Local CSV files provided by the user.

---

## ⚙️ Technologies Used

- Python 3.x  
- Jupyter Notebook (VS Code compatible)  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## ✅ Features Implemented

- 🔄 Data preprocessing: handling missing values, encoding, feature selection  
- ⚖️ Feature scaling with StandardScaler  
- 🌲 Training with Random Forest Classifier (optimized for speed)  
- 📉 Performance metrics: Accuracy, Precision, Recall, F1-score  
- 📊 ROC Curve, AUC Score  
- 📌 Feature importance visualization  
- ❗ Misclassification (False Positives/Negatives) analysis  

---

## 🚀 How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/Kaja-avinash/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

### 2. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook

```bash
jupyter notebook CreditCardFraudDetection.ipynb
```

### 4. Update File Paths

Ensure your dataset paths are correctly set:
```python
train_path = r"C:\Users\avina\Downloads\archive (4)\fraudTrain.csv"
test_path = r"C:\Users\avina\Downloads\archive (4)\fraudTest.csv"
```

---

## 📊 Results

- ✅ High fraud detection accuracy
- ✅ Balanced ROC-AUC score
- ✅ Clearly visualized feature importance
- ✅ Misclassifications analyzed and explained

---

## 🧠 Evaluation Criteria

- ✔️ Clear and well-documented notebook  
- ✔️ Effective visualizations using Matplotlib & Seaborn  
- ✔️ Accurate and explainable model  
- ✔️ Minimal false positives  
- ✔️ Modular, commented, and organized code  

---

## 📁 Project Structure

```
credit-card-fraud-detection/
│
├── CreditCardFraudDetection.ipynb      # Main Jupyter Notebook
├── fraudTrain.csv                      # Training dataset
├── fraudTest.csv                       # Testing dataset
├── requirements.txt                    # Python dependencies
└── README.md                           # Project overview
