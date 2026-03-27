# Credit Card Fraud Detection

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)
![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-f7931e.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg)

A machine learning project to detect fraudulent credit card transactions using historical transaction data.  
This repository contains a full notebook-driven workflow for preprocessing, model training, evaluation, and interpretation.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Core Features](#core-features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling & Evaluation](#modeling--evaluation)
- [Results](#results)
- [Limitations](#limitations)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## Project Overview

Credit card fraud detection is a highly imbalanced classification problem where fraudulent transactions represent only a small fraction of total activity.  
This project implements a supervised ML pipeline (Random Forest-based) to identify suspicious transactions while balancing precision and recall.

---

## Objectives

- Accurately detect fraudulent transactions
- Minimize false positives
- Provide clear model performance insights
- Analyze misclassifications (false positives/false negatives)
- Visualize model behavior and feature importance

---

## Dataset

This project uses:

- `fraudTrain.csv`
- `fraudTest.csv`

**Dataset source:** Local CSV files provided by the user.

> Ensure file paths are correctly configured in the notebook before execution.

---

## Tech Stack

- **Language:** Python 3.x
- **Environment:** Jupyter Notebook (VS Code compatible)
- **Libraries:**
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn

---

## Core Features

- Data preprocessing (missing values, encoding, feature selection)
- Feature scaling using `StandardScaler`
- Model training with `RandomForestClassifier`
- Performance evaluation via:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC curve and AUC
- Feature importance analysis
- Misclassification analysis (FP/FN)

---

## Project Structure

```text
credit-card-fraud-detection/
│
├── CreditCardFraudDetection.ipynb      # Main notebook with end-to-end workflow
├── fraudTrain.csv                      # Training dataset
├── fraudTest.csv                       # Testing dataset
├── requirements.txt                    # Python dependencies (if present)
├── LICENSE                             # All Rights Reserved / view-only terms
└── README.md                           # Project documentation
```

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Kaja-avinash/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the notebook:

```bash
jupyter notebook CreditCardFraudDetection.ipynb
```

If needed, update local dataset paths inside the notebook, for example:

```python
train_path = r"C:\Users\avina\Downloads\archive (4)\fraudTrain.csv"
test_path = r"C:\Users\avina\Downloads\archive (4)\fraudTest.csv"
```

---

## Modeling & Evaluation

The notebook includes:

1. Data loading and preprocessing
2. Feature engineering and scaling
3. Random Forest model training
4. Prediction and scoring
5. Evaluation report and visualization:
   - Classification metrics
   - ROC-AUC
   - Feature importance plots
   - Misclassification review

---

## Results

Current documented outcomes include:

- High fraud detection accuracy
- Balanced ROC-AUC behavior
- Interpretable feature importance visualizations
- Clear analysis of misclassified transactions

---

## Limitations

- Dataset paths are currently local/manual
- Notebook-first structure (no packaged training/inference pipeline yet)
- Metrics are presented descriptively; reproducibility can improve with pinned versions/seeds

---

## Future Improvements

- Add a reproducible `requirements.txt` with pinned versions
- Add configuration-based path handling
- Add model persistence (`joblib`/`pickle`) for deployment
- Add experiment tracking and cross-validation
- Add CI checks for notebook quality and linting

---

## License

This repository is distributed under **All Rights Reserved** terms with view-only permission.  
See the [LICENSE](./LICENSE) file for full legal terms.

---
