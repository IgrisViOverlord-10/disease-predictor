# 🧬 Disease Prediction Web Application using Machine Learning

A web-based application that predicts potential diseases based on user-entered symptoms. Integrates a trained machine learning model with a Django interface for real-time predictions.

---

## 📌 Project Overview

This project demonstrates how machine learning can be applied to healthcare prediction tasks. Users enter symptoms via a web interface, and the system returns a predicted disease based on a trained model.

**Workflow Summary:**  
- Data preprocessing & EDA  
- Model training & comparison  
- Deployment in a Django web app

---

## ⚙️ Workflow

**Phase 1 – Model Development**  
- Load, clean, and preprocess `Training.csv` & `Testing.csv`  
- Conduct exploratory data analysis (EDA) with graphs & heatmaps  
- Train multiple models (Logistic Regression, KNN, Naïve Bayes, Decision Tree, Random Forest, Gradient Boosting)  
- Evaluate performance on test data and select the final model  

**Phase 2 – Web Application Integration**  
- Serialize the trained model (`.pkl`)  
- Integrate into Django backend  
- Create a web form for symptom input  
- Process input, predict disease, and display results in real-time

---

## 🚀 Key Highlights

- End-to-end pipeline from data preprocessing to web deployment  
- Comparison of multiple models before final selection  
- Real-time predictions via an interactive web interface  
- Visualizations of symptom patterns, correlations, and model performance

---

## 🧠 Machine Learning Results

| Model                  | Accuracy (%) |
|------------------------|-------------|
| Logistic Regression    | 100         |
| K-Nearest Neighbors (KNN) | 100      |
| Naïve Bayes            | 100         |
| Decision Tree          | 97.619      |
| Random Forest          | 97.619      |
| Gradient Boosting      | 97.619      |

**Why Logistic Regression was chosen:**  
Although three models achieved 100% accuracy, Logistic Regression was selected for its **simplicity, interpretability, and lower risk of overfitting**, making it suitable for practical use in healthcare predictions.

---

## 🛠️ Tech Stack

- Python, Jupyter Notebook, Django  
- Pandas, NumPy, Scikit-learn  
- Pickle (model serialization)  
- HTML / CSS  

---

## 💡 What Makes This Project Unique

- End-to-end implementation from notebook experimentation to web deployment  
- Comparison of multiple models to select the best-performing one  
- Real-time interactive predictions  
- Practical dataset handling and deployment workflow

---

## 🔮 Opportunities for Extension

- Evaluate additional metrics (Precision, Recall) for deeper analysis  
- Expand dataset to cover more symptoms and diseases  
- Optimize web interface for mobile users  
- Explore cloud deployment for scalable real-time usage

---

## 📂 Repository Contents

- `dataset/Training.csv` – Training dataset  
- `dataset/Testing.csv` – Testing dataset  
- Project screenshots (Snapshots - 3.pdf)  
- README documentation  

> 🔒 Note: Source code is not included in this repository as it was part of an internship project. This repository showcases the workflow, dataset usage, and results.

---

## 📸 Project Snapshots

- Django-based symptom input interface  
- Predicted disease output screen  
- Prognosis column distribution graph  
- Correlation heatmap between symptoms  
- Model accuracy comparison outputs

---

## ⚠️ Disclaimer

For educational and research purposes only. Predictions may not always be accurate and should **not** be used for real medical diagnosis or treatment.
