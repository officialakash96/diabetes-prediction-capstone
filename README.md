# Diabetes Prediction using Classical Machine Learning

## 📌 Project Overview
This project focuses on predicting the likelihood of diabetes in patients based on diagnostic measures such as Glucose, BMI, and Insulin levels. Using the **Pima Indians Diabetes Dataset**, we implemented and compared three classical machine learning algorithms to determine the most effective model for early detection.

**Key Insight:** Contrary to the assumption that complex models work better, **Logistic Regression** outperformed Random Forest in this specific domain, achieving an accuracy of **75.32%**.

## 🛠️ Tech Stack
* **Language:** Python 3.10+
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** VS Code, Google Colab

## 📊 Dataset Details
The dataset consists of 768 female patients with 8 diagnostic features.
* **Source:** [Pima Indians Diabetes Database](https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv)
* **Data Cleaning:** Imputed missing values (recorded as `0` in Glucose/BMI columns) using the **median** to preserve distribution integrity.

## 🧠 Model Performance
We trained three models and evaluated them on a 20% unseen test set.

| Model | Accuracy | Key Observation |
| :--- | :--- | :--- |
| **Logistic Regression** | **75.32%** | Best Performer. High recall for positive cases. |
| **Random Forest** | 74.68% | Good, but slight overfitting observed. |
| **Decision Tree** | 72.08% | Prone to high variance. |

## 📉 Visualizations
The project includes Exploratory Data Analysis (EDA) to identify correlations (e.g., Glucose vs. Outcome) and Confusion Matrices to analyze False Negatives.

## 🚀 How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/officialakash96/diabetes-prediction-capstone.git](https://github.com/officialakash96/diabetes-prediction-capstone.git)