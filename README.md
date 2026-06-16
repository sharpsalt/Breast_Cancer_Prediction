# Breast Cancer Prediction

A comprehensive Machine Learning project for breast cancer diagnosis prediction using statistical analysis,feature engineering,and multiple classification algorithms.

## Overview

This project performs an end-to-end medical data analysis workflow on a breast cancer dataset. It combines:

* Exploratory Data Analysis (EDA)
* Probability Distribution Analysis
* Hypothesis Testing
* Feature Engineering
* Machine Learning Classification
* Model Evaluation
* Real-world Prediction Simulation

The goal is to classify tumors as:

* **Benign (B)** → Non-cancerous
* **Malignant (M)** → Cancerous

---

##  Features

### Statistical Analysis

* Distribution visualization
* Outlier detection
* T-Test hypothesis testing

### Feature Engineering

* Missing value handling
* Interaction feature creation
* Data normalization

### Machine Learning Models

* Logistic Regression
* Random Forest
* Support Vector Machine (SVM)
* XGBoost

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### Prediction System

Predicts whether a tumor is benign or malignant and provides confidence scores.

---

##  Dataset

The dataset contains various tumor characteristics such as:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Symmetry

Target Variable:

| Diagnosis | Meaning   |
| --------- | --------- |
| B         | Benign    |
| M         | Malignant |

---

# Results

## Dataset Preview

Place image:

```text
images/dataset_preview.png
```

```markdown
<img width="1350" height="231" alt="image" src="https://github.com/user-attachments/assets/fc7a264b-3e2b-446c-84f9-b9cbf08392af" />

```

---

## Exploratory Data Analysis

Shows:

* Radius Mean Distribution
* Texture Mean Boxplot

Place image:

```text
images/eda_visualization.png
```

```markdown
<img width="1244" height="475" alt="image" src="https://github.com/user-attachments/assets/fb539531-fbe6-42a5-948b-8f9951e86733" />

```

---

## Hypothesis Testing

Shows:

* T-statistic
* P-value
* Statistical significance result

Place image:

```text
images/hypothesis_testing.png
```

```markdown
<img width="975" height="61" alt="image" src="https://github.com/user-attachments/assets/44823638-fdc1-4596-a736-e8892e8c7d34" />

```

---

## Model Performance

Create a bar chart showing model accuracies.

Place image:

```text
images/model_accuracy.png
```

```markdown
<img width="921" height="80" alt="image" src="https://github.com/user-attachments/assets/79565b34-14fa-42ec-a113-60168d414941" />

```

---

## Confusion Matrices

Comparison of all classifiers.

Place image:

```text
images/confusion_matrices.png
```

```markdown
<img width="887" height="792" alt="image" src="https://github.com/user-attachments/assets/edcdd52d-bed2-4b1a-8cbc-2671ee94096c" />

```

---

## Sample Prediction

Shows output of:

```python
predict_diagnosis(sample_patient)
```

Place image:

```text
images/prediction_example.png
```

```markdown
<img width="840" height="54" alt="image" src="https://github.com/user-attachments/assets/481ef0ed-c088-4f7c-9245-9478af08c888" />

```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Medical-Disease-Prediction.git

cd Medical-Disease-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Run

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Advanced_Medical_Analysis.ipynb
```

Run all cells sequentially.

---

# 📈 Models Used

| Model               | Purpose                      |
| ------------------- | ---------------------------- |
| Logistic Regression | Linear baseline classifier   |
| Random Forest       | Ensemble decision trees      |
| SVM                 | Margin-based classification  |
| XGBoost             | Gradient boosting classifier |

---

# Statistical Methods

### T-Test

Used to determine whether the mean values of a feature differ significantly between benign and malignant tumors.

Null Hypothesis:

```text
H0: No significant difference exists.
```

Alternative Hypothesis:

```text
H1: Significant difference exists.
```
---

# 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Scikit-Learn
* XGBoost
* Jupyter Notebook

---

# Future Improvements

* Deep Learning Models
* Explainable AI (SHAP/LIME)
* Web Deployment using Streamlit
* Real-time Clinical Dashboard
* Hyperparameter Optimization

---

# Author

-Srijan Verma
-Computer Science Engineering, IIIT Nagpur
