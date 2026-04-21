# 💉 Vaccine Prediction Project (H1N1)

## 📌 Project Overview

This project aims to predict whether an individual is likely to receive the H1N1 vaccine using machine learning techniques. The model is built using survey data that includes demographic information, health conditions, awareness levels, and behavioral patterns.

---

## 🎯 Objective

To develop a classification model that predicts vaccination status (`h1n1_vaccine`) based on multiple influencing factors.

---

## 📊 Dataset Information

The dataset consists of two files:

* **features.csv** → Contains input features (demographics, behavior, health, opinions)
* **labels.csv** → Contains target variables:

  * `h1n1_vaccine` (0 = No, 1 = Yes)
  * `seasonal_vaccine` (not used in this model)

Each row represents one individual from a public health survey.

---

## 🔍 Key Features Used

* Demographics: Age group, gender, education, income
* Health: Chronic medical conditions, health worker status
* Behavior: Mask usage, hand washing, social distancing
* Awareness: Knowledge and concern about H1N1

---

## ⚙️ Technologies & Tools

* Python (Pandas, NumPy)
* Scikit-learn (Machine Learning)
* Power BI (Data Visualization)
* Jupyter Notebook

---

## 🔧 Data Preprocessing

* Merged `features.csv` and `labels.csv` using `respondent_id`
* Removed unnecessary column (`respondent_id`)
* Handled missing values using:

  * Mode (categorical)
  * Median (numerical)
* Converted categorical variables using one-hot encoding

---

## 🤖 Model Building

* Algorithm Used: **Random Forest Classifier**
* Train-Test Split: 80% training, 20% testing
* Model trained on processed dataset

---

## 📈 Model Evaluation

* Accuracy Score
* Classification Report:

  * Precision
  * Recall
  * F1-score

---

## 📊 Power BI Dashboard

An interactive dashboard was created using the final dataset:

* 📌 Prediction Distribution
* 📌 Actual vs Predicted Comparison
* 📌 Confusion Matrix
* 📌 Probability Distribution

---

## 📁 Project Files

* `Vaccination prediction project.ipynb` → Full ML code
* `features.csv` → Input dataset
* `labels.csv` → Target dataset
* `vaccine_final_data.csv` → Output with predictions

---

## 🚀 Conclusion

The model successfully predicts vaccination behavior using various influencing factors such as awareness, health conditions, and demographic information. This can help public health organizations understand vaccination trends and improve decision-making.

---

## 👨‍💻 Author

Srilakshmi kolla

---

⭐ If you found this project useful, feel free to star the repository!
