# 🧠 Alzheimer's Disease Classification Using Patient Demographics

This project focuses on predicting the likelihood of **Alzheimer’s Disease (AD)** using **patient demographic data**.  
It applies classical **machine learning techniques** implemented with **Scikit-learn** to classify patients based on relevant features, helping identify potential AD cases early.

---

## 📘 Overview

Alzheimer’s Disease is a neurodegenerative condition that affects memory and cognitive abilities.  
This project uses demographic attributes such as **age, gender, education, and clinical test scores** to train machine learning models that classify whether a patient is likely to have Alzheimer’s Disease.

---

## 🧩 Features

- Data preprocessing and feature selection  
- Handling of missing or imbalanced data  
- Feature scaling and dimensionality reduction using **PCA**  
- Model training and evaluation using **SVM** and **Random Forest**  
- Comparison of model performance metrics (accuracy, precision, recall, F1-score)

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries:** Scikit-learn, NumPy, Pandas, Matplotlib, Seaborn  
- **Notebook:** Jupyter / Google Colab  

---

## 🚀 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/BilalAsifB/alzheimers_disease_classification.git
   cd alzheimers_disease_classification
2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate      # For Linux/Mac
    venv\Scripts\activate         # For Windows

---

## 📊 Usage

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook ml_proj.ipynb
2. Run the notebook cells step-by-step to:
    * Load and preprocess the dataset
    * Perform feature selection and scaling
    * Train and evaluate models
    * Visualize results

---

## 🧠 Model Summary
| Model                            | Description                              | Purpose                          |
| -------------------------------- | ---------------------------------------- | -------------------------------- |
| **Support Vector Machine (SVM)** | Finds optimal decision boundaries        | High accuracy on structured data |
| **Random Forest**                | Ensemble method combining multiple trees | Robust to overfitting and noise  |

---

## 📈 Results

* The Random Forest model showed better generalization performance compared to SVM.
* Dimensionality reduction using PCA improved model efficiency without compromising accuracy.
* The project demonstrated the potential of demographic features in early AD prediction.

---

👨‍💻 Author

Bilal Asif Burney \
📧 bilalburney14@gmail.com \
🔗 [LinkedIn](www.linkedin.com/in/bilal-asif-burney-94a194218) | [GitHub](https://github.com/BilalAsifB)