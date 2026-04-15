# 🧠 Hidden Pattern Mining in Blood Tests (Unsupervised ML)

## 🚀 Overview
This project presents an **unsupervised machine learning framework** to identify hidden health risk patterns from routine blood test data.

Unlike traditional approaches that analyze parameters independently, this model captures **interactions between biomarkers** to detect early risk signals.

---

## 🔍 Problem Statement
Traditional medical analysis evaluates blood test values independently, which can miss subtle but critical multivariate relationships.

👉 This project addresses that gap using **interaction-based feature engineering + anomaly detection**.

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Missing value handling
- Feature normalization
- Dataset: UCI Hepatitis Dataset (155 patients)

### 2. Feature Engineering (KEY INNOVATION)
- Created interaction features:
  - Ratios (SGOT / Albumin)
  - Products (Bilirubin × SGOT)

### 3. Unsupervised Learning
- Isolation Forest (anomaly detection)
- PCA (dimensionality reduction)

### 4. Risk Scoring
- Generated normalized risk score (0 → 1)
- Higher score → higher abnormality

### 5. Explainability
- Feature perturbation analysis
- Correlation heatmaps

---

## 📊 Results

### 🔥 Blood Test Interaction Heatmap
![Heatmap](outputs/heatmap.png)

### 📈 Risk Score Distribution
![Risk](outputs/risk_distribution.png)

👉 Model successfully identified a subset of high-risk patients through interaction patterns.

---

## 🛠 Tech Stack
- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 🎯 Key Contributions
- Interaction-based feature engineering
- Unsupervised anomaly detection in healthcare
- Explainable AI integration

---

## 🚀 Applications
- Early disease risk detection
- Preventive healthcare systems
- Clinical decision support tools

---


## 📂 Project Structure
'''

project/
│
├── notebook/
│ └── hepatitis_hidden_pattern_mining.ipynb
│
├── data/
│ ├── hepatitis.data
│ └── hepatitis.names
│
├── outputs/
│ ├── heatmap.png
│ └── risk_distribution.png
│
├── README.md
└── requirements.txt

'''


## 🔗 Author
Mahesh Dattatreya
