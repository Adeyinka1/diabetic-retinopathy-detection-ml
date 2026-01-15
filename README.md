# Diabetic Retinopathy Detection using Machine Learning (Binary Classification)

## Overview
Diabetic Retinopathy (DR) is a diabetes-related eye disease and a leading cause of preventable blindness worldwide. Early detection is critical, yet manual diagnosis is time-consuming and requires specialist expertise.  
This project applies machine learning techniques to perform **binary classification** for diabetic retinopathy detection, demonstrating how data-driven models can support clinical decision-making.

The project is designed for **both academic demonstration and industry-level machine learning practice**, with a clear, reproducible pipeline and interpretable results.

---

## Problem Statement
The goal is to build a binary classification model that predicts whether a patient shows signs of diabetic retinopathy based on extracted features.  
The task is framed as:
- **0** → No Diabetic Retinopathy  
- **1** → Presence of Diabetic Retinopathy  

---

## Dataset
The dataset contains preprocessed features derived from retinal images, commonly used in diabetic retinopathy research.  
Due to size and licensing constraints, the raw dataset is not included in this repository. Instructions on data sourcing are provided within the notebook.

**Note:** This project does not include identifiable patient information and is safe for public release.

---

## Methodology
The machine learning workflow follows these steps:

1. Data loading and inspection  
2. Data preprocessing and feature scaling  
3. Train–test split  
4. Binary classification model training  
5. Model evaluation using standard performance metrics  

The notebook is structured to run **top-to-bottom without errors**, ensuring full reproducibility.

---

## Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics provide insight into both predictive performance and class-level behaviour, which is especially important in medical classification tasks where false negatives can be costly.

---

## Results
The trained model demonstrates meaningful predictive capability for diabetic retinopathy detection.  
Results indicate that machine learning can effectively support early screening workflows when combined with appropriate clinical oversight.

Detailed outputs and interpretations are available directly in the notebook.

---

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

## How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/Adeyinka1/diabetic-retinopathy-detection-ml.git
