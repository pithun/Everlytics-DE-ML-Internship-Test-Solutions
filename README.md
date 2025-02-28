# Overview 

This repository gathers the tests I completed as part of the Everlytics internship application. It includes:

- **Python Test** 🐍
- **SQL Test** 🗃️
- **Machine Learning Test: Phishing Website Detection** 🤖

---

## Machine Learning Test: Phishing Website Detection 🔍

### Overview
Phishing websites are deceptive domains crafted to mimic legitimate ones and trick users. With the growing sophistication of these schemes, detecting phishing sites has become increasingly important. This project leverages machine learning techniques combined with website feature analysis to identify potential phishing sites.

### Dataset Details 📊
- **Task:** Classification
- **Data Type:** Categorical
- **Dataset:** Contains up to 30 features with 1372 training records.

### Tools & Technologies ⚙️
- Python 🐍
- Pandas 🐼
- Numpy 🔢
- Matplotlib 📈
- Scikit-learn 🤖

### Approach 🛠️
1. **Data Cleaning:**  
   - Checked for missing values and removed duplicates.  
   - Ensured consistency across feature values.
2. **Exploratory Data Analysis (EDA):**  
   - Analyzed the distribution of classes, revealing a 52% to 48% split between non-phishing and phishing sites.
3. **Data Splitting:**  
   - Performed an 80/20 train-test split.
4. **Model Training & Evaluation:**  
   - Implemented three models: Random Forest, XGBoost, and CatBoost.  
   - Conducted four-fold cross-validation to select the best-performing model.
5. **Model Tuning:**  
   - Fine-tuned the Random Forest model, achieving improved accuracy.

### Model Performance 🏆
- **Random Forest Classifier:**  
  - 96.22% accuracy before tuning  
  - 97.67% accuracy after tuning
- **XGBoost Classifier:** 97.09% accuracy
- **CatBoost Classifier:** 96.80% accuracy

---

This repository showcases my skills in data processing, analysis, and machine learning as part of my Everlytics internship application.
