# 🧠 Student-Stress-Analysis-and-Prediction

[![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)](https://www.python.org/) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 📌 Project Overview
This project predicts **stress levels of students** based on features related to mental health, lifestyle, and academics.  
It uses **six machine learning classifiers** to find the most effective model for predicting stress levels.

---

## 🗂 Dataset
- **Number of records:** 1100  
- **Number of features:** 20 features + 1 target (`stress_level`)  
- **Features include:**  
  `anxiety_level`, `self_esteem`, `mental_health_history`, `depression`, `headache`, `blood_pressure`,  
  `sleep_quality`, `breathing_problem`, `noise_level`, `living_conditions`, `safety`, `basic_needs`,  
  `academic_performance`, `study_load`, `teacher_student_relationship`, `future_career_concerns`,  
  `social_support`, `peer_pressure`, `extracurricular_activities`, `bullying`  
- **Target variable:** `stress_level`  
  - `0` = Low Stress  
  - `1` = Medium Stress  
  - `2` = High Stress  
- **Source:** [Insert dataset link here]

---

## 🔍 Exploratory Data Analysis (EDA)
- **Distribution of stress levels:** shows how many students fall into low, medium, or high stress.  
- **Key feature distributions:** `anxiety_level`, `self_esteem`, `depression`, `sleep_quality`.  
- **Correlation matrix:** visualizes relationships between all features.  

All plots are included in the notebook.

---

## 🧩 Machine Learning Models
The following classifiers were trained and evaluated:

1. **Logistic Regression**  
2. **Decision Tree Classifier**  
3. **Random Forest Classifier**  
4. **Support Vector Machine (SVM)**  
5. **K-Nearest Neighbors (KNN)**  
6. **Naive Bayes (GaussianNB)**  

---

## 📊 Model Evaluation
- **Classification reports** include precision, recall, and F1-score for each model.  

### Accuracy of each model on the test set:
| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | 88%      |
| Decision Tree          | 89%      |
| Random Forest          | 87%      |
| Support Vector Machine | 90%      |
| K-Nearest Neighbors    | 88%      |
| Naive Bayes            | 90%      |

- **Confusion matrices** are plotted in the notebook for each model.

---

## ✅ Conclusion
- All models performed well with accuracy around **87–91%**.  
- **SVM and Naive Bayes** were slightly better in prediction performance.  
- Tree-based models allow **feature importance analysis**, which can identify influential factors for stress.

---

## 🚀 Future Work
- Hyperparameter tuning for all models to improve accuracy.  
- Cross-validation for robust evaluation.  
- Create an **interactive web app** for real-time stress prediction.  
- Expand the dataset with more students and features.

---

## 🛠 Installation & Usage

1. Clone the repository:  
```bash
git clone https://github.com/your-username/Student-Stress-Analysis-and-Prediction.git
cd Student-Stress-Analysis-and-Prediction
