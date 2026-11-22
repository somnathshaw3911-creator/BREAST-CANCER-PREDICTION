# BREAST-CANCER-PREDICTION
Binary classification using Random Forest, Gradient Boosting, SVM, and Neural Network combined into an Ensemble Model (99.12% accuracy).
# Ensemble Machine Learning Classification Project

## Overview
This project implements and compares four machine learning models for binary classification—**Random Forest**, **Gradient Boosting**, **Support Vector Machine (SVM)**, and a **Neural Network**—and combines them into a high-performing **Ensemble Model** with threshold optimization.

## Dataset
- **Source:** Loaded directly via URL inside the notebook.
- **Dataset URL:** 'https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data'
- **Test Set Size:** 114 samples (72 instances of Class `0`, 42 instances of Class `1`)

## Models Used
1. **Random Forest**
2. **Gradient Boosting**
3. **Support Vector Machine (SVM)**
4. **Neural Network**
5. **Ensemble Model** (Optimized classification threshold: `0.420`)

## Results & Performance Comparison

| Model | Accuracy | Precision (Macro) | Recall (Macro) | F1-Score (Macro) |
| :--- | :---: | :---: | :---: | :---: |
| **Random Forest** | 97.37% | 0.98 | 0.96 | 0.97 |
| **Gradient Boosting** | 97.37% | 0.98 | 0.96 | 0.97 |
| **SVM** | 96.49% | 0.96 | 0.96 | 0.96 |
| **Neural Network** | 97.37% | 0.97 | 0.97 | 0.97 |
| **Ensemble Model** | **99.12%** | **0.99** | **0.99** | **0.99** |

### Best Model: Ensemble Classification Report
- **Accuracy:** 99.12% (114 test samples)
- **Class 0:** Precision `0.99` | Recall `1.00` | F1-Score `0.99`
- **Class 1:** Precision `1.00` | Recall `0.98` | F1-Score `0.99`

## Repository Structure
- `mlproject (1).ipynb` — Main Google Colab / Jupyter Notebook containing data loading, model training, evaluation metrics, and visualizations.
- `requirements.txt` — Python dependencies required to run the project.
- `README.md` — Project documentation.

## How to Run
1. **Using Google Colab (Recommended):**
   - Upload the `.ipynb` file to [Google Colab](https://colab.research.google.com/) and click **Runtime → Run all**.
2. **Locally with Jupyter Notebook:**
   ```bash
   git clone [https://github.com/somnathshaw3911-creator/YOUR-REPO-NAME.git](https://github.com/somnathshaw3911-creator/YOUR-REPO-NAME.git)
   cd YOUR-REPO-NAME
   pip install -r requirements.txt
   jupyter notebook
