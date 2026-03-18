# 🧬 Disease Prediction Web Application using Machine Learning

A web-based application that predicts potential diseases based on symptoms entered by the user. This project integrates a trained machine learning model with a Django-based interface to provide an interactive, user-friendly platform for symptom-based disease prediction.

---

## 📌 Project Overview

This project demonstrates how machine learning can be applied to healthcare prediction tasks. Users can enter their symptoms via a web interface, and the system returns a predicted disease based on a trained model.

The workflow covers:

1. Data preprocessing and analysis  
2. Training and comparing multiple machine learning models  
3. Deploying the final model in a Django web application  

---

## ⚙️ Workflow

**Phase 1 – Model Development**  
- Load and explore the dataset (`dataset/Training.csv` & `dataset/Testing.csv`)  
- Clean and preprocess the data for ML  
- Conduct exploratory data analysis (EDA) using visualizations (graphs, heatmaps)  
- Train multiple models: Logistic Regression, KNN, Naïve Bayes, Decision Tree, Random Forest, Gradient Boosting  
- Evaluate model performance using accuracy on the testing dataset  
- Select Logistic Regression as the final model based on evaluation  

**Phase 2 – Web Application Integration**  
- Serialize the trained model as a `.pkl` file  
- Integrate the model with Django backend  
- Create a web form for user symptom input  
- Process input and predict the disease in real-time  
- Display results in a clean, user-friendly interface  

---

## 🚀 Key Highlights

- End-to-end pipeline from data preprocessing to web deployment  
- Comparison of multiple ML models before final selection  
- Real-time prediction through a Django web interface  
- Visualization of symptom patterns, correlation heatmaps, and model comparison outputs  

---

## 🧠 Machine Learning Results

- **Final Model:** Logistic Regression  
- **Accuracy:** Refer to project snapshots for detailed model performance  
- Other models explored for comparison: KNN, Naïve Bayes, Decision Tree, Random Forest, Gradient Boosting  

**Why Logistic Regression was chosen:**  
Although three models achieved 100% accuracy on the test dataset, Logistic Regression was selected for its simplicity, interpretability, and lower risk of overfitting. This makes it suitable for a practical deployment scenario where explainability and consistent generalization are important, especially in healthcare-related predictions. 

---

## 🛠️ Tech Stack

- Python  
- Jupyter Notebook  
- Django  
- Pandas, NumPy  
- Scikit-learn  
- Pickle (for model serialization)  
- HTML / CSS  

---

## 💡 What Makes This Project Unique

- Complete end-to-end implementation from notebook experimentation to a deployed web app  
- Comparison of multiple models to select the best-performing one  
- Interactive web interface for real-time predictions  
- Focused on practical dataset handling and deployment workflow  

---

## 🔮 Opportunities for Extension

- Evaluating additional metrics such as Precision and Recall to better understand model performance  
- Expanding the dataset to cover more symptoms and diseases for broader applicability  
- Optimizing the web interface for mobile users  
- Exploring cloud deployment for scalable, real-time predictions

---

## 📂 Repository Contents

- `dataset/Training.csv` – Training dataset  
- `dataset/Testing.csv` – Testing dataset  
- Project screenshots (available in Snapshots - 3.pdf)  
- README documentation  

> 🔒 Note: Source code is not included in this repository as it was part of an internship project. This repository showcases the project workflow, dataset usage, and results.  

---

## 📸 Project Snapshots

- Django-based symptom input interface  
- Predicted disease output screen  
- Prognosis column distribution graph  
- Correlation heatmap between symptoms  
- Model accuracy comparison outputs  

---

### ⚠️ Disclaimer

This project is for **educational and research purposes only**. Predictions may not always be accurate and should **not** be used for real medical diagnosis or treatment.
