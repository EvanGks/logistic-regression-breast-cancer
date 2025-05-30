# Breast Cancer Classification with Logistic Regression
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24%2B-f7931e?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/)
[![seaborn](https://img.shields.io/badge/seaborn-0.11%2B-4c8cbf?logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue.svg)](https://www.kaggle.com/code/evangelosgakias/logistic-regression)
[![Reproducible Research](https://img.shields.io/badge/Reproducible-Yes-brightgreen.svg)](https://www.kaggle.com/code/evangelosgakias/logistic-regression)

---

## 🚀 Live Results
You can view the notebook with all outputs and results on Kaggle:
[https://www.kaggle.com/code/evangelosgakias/logistic-regression](https://www.kaggle.com/code/evangelosgakias/logistic-regression)

All metrics, plots, and outputs are available in the linked Kaggle notebook for full transparency and reproducibility.

---

## 📑 Table of Contents
- [Live Results](#-live-results)
- [Table of Contents](#-table-of-contents)
- [Overview](#-overview)
- [Project Structure](#-project-structure)
- [Features](#-features)
- [Quickstart](#-quickstart)
- [Usage](#-usage)
- [Results](#-results)
- [Limitations and Future Work](#-limitations-and-future-work)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 📝 Overview
This project presents a comprehensive machine learning workflow for classifying breast cancer tumors as malignant or benign using **logistic regression** on the classic scikit-learn Breast Cancer Wisconsin (Diagnostic) dataset. The notebook demonstrates:
- End-to-end data science best practices (EDA, preprocessing, modeling, evaluation, and interpretation)
- Professional documentation, accessibility, and reproducibility standards

**Goal:** Predict whether a breast tumor is malignant or benign using 30 features derived from medical imaging.

This project is ideal for those seeking a clear, portfolio-ready example of binary classification analysis in healthcare data.

---

## 🏗️ Project Structure
```
Logistic Regression/
├── logistic_regression.ipynb   # Jupyter notebook with the complete implementation
├── README.md                   # Project documentation (this file)
├── requirements.txt            # Python dependencies
├── LICENSE                     # MIT License file
└── .venv/                      # (Optional) Virtual environment directory
```
---

## 🚀 Features
### Data Preparation
- **Dataset Loading:** Uses the scikit-learn breast cancer dataset (30 features, 569 samples)
- **Exploratory Data Analysis (EDA):** Statistical summaries, correlation analysis, and visualizations (histograms, heatmaps)
- **Preprocessing:**
  - Feature scaling (StandardScaler)
  - Train/test split (80%/20%, stratified)

### Modeling
- **Logistic Regression:**
  - scikit-learn implementation
  - Model interpretability via coefficients
  - Pipeline for reproducibility

### Evaluation & Interpretation
- **Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC
- **Visualizations:**
  - Confusion matrix
  - ROC curve
  - PCA-based decision boundary
- **Feature Importance:** Coefficient analysis and bar chart visualization

*All plots include descriptive titles, axis labels, and are designed for accessibility.*

---

## ⚡ Quickstart
1. **Kaggle (Recommended for Reproducibility):**
   - [Run the notebook on Kaggle](https://www.kaggle.com/code/evangelosgakias/logistic-regression)
2. **Local:**
   - Clone the repo and run `logistic_regression.ipynb` in Jupyter after installing requirements.

---

## 💻 Usage
1. **📥 Clone the repository:**
   ```bash
   git clone https://github.com/EvanGks/logistic-regression-breast-cancer.git
   cd logistic-regression-breast-cancer
   ```
2. **🔒 Create and activate a virtual environment:**
   - **Windows:**
     ```bash
     python -m venv .venv
     .venv\Scripts\activate
     ```
   - **macOS/Linux:**
     ```bash
     python3 -m venv .venv
     source .venv/bin/activate
     ```
3. **📦 Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **🚀 Launch Jupyter Notebook:**
   ```bash
   jupyter notebook logistic_regression.ipynb
   ```
5. **▶️ Run all cells** to reproduce the analysis and results.

**🛠️ Troubleshooting:**
- If you encounter missing package errors, ensure your Python environment is activated and up to date.
- For best reproducibility, use the provided Kaggle link.

---

## 📊 Results
### Model Metrics
- **Accuracy:** ~0.97
- **Precision:** ~0.97
- **Recall:** ~0.98
- **F1-Score:** ~0.97
- **ROC-AUC:** ~0.99

### Feature Importance
Top predictors (by absolute coefficient):
- Worst perimeter
- Mean concave points
- Worst concave points
- Worst radius
- Worst area

### Visualizations
- **Histograms:** Distribution of selected features
- **Correlation Heatmap:** Feature relationships
- **Confusion Matrix:** Model performance
- **ROC Curve:** Classification quality
- **PCA Decision Boundary:** 2D visualization of model separation

*All plots include descriptive titles, axis labels, and alt text for accessibility.*

---

## 📝 Limitations and Future Work
- **Linear Assumption:** May not capture complex, non-linear relationships
- **Sensitivity to Outliers:** Real-world data may require robust preprocessing
- **Potential Improvements:**
  - Explore non-linear models (e.g., tree-based, SVM)
  - Hyperparameter tuning (GridSearchCV)
  - Advanced feature engineering
  - Compare with other classifiers
  - Deploy as a web app with accessible UI

---

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

---

## 📝 License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## 📬 Contact
For questions or feedback, please reach out via:
- **GitHub:** [EvanGks](https://github.com/EvanGks)
- **LinkedIn:** [Evangelos Gakias](https://www.linkedin.com/in/evangelos-gakias-346a9072)
- **Email:** [vgakias_@hotmail.com](mailto:vgakias_@hotmail.com)

---

Happy Coding! 🚀