# Heart Disease Prediction 🫀

A machine learning project designed to predict the likelihood of heart disease in patients based on clinical parameters. This project explores data preprocessing, exploratory data analysis (EDA), and the implementation of classification algorithms.

## 📌 Project Overview
Heart disease remains one of the leading causes of death globally. Early detection is crucial for preventative healthcare. This project utilizes a dataset of patient medical records to build a predictive model that can classify whether a patient has heart disease or not.



## 📊 Dataset
The model is trained on the **UCI Heart Disease Dataset** (or specify your source). Key features include:
* **Age**: Patient's age in years.
* **Sex**: (1 = male; 0 = female).
* **CP**: Chest pain type.
* **Trestbps**: Resting blood pressure.
* **Chol**: Serum cholesterol in mg/dl.
* **Thalach**: Maximum heart rate achieved.
* **Target**: 1 = Heart Disease, 0 = No Disease.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * Data Manipulation: `Pandas`, `NumPy`
    * Visualization: `Matplotlib`, `Seaborn`
    * Machine Learning: `Scikit-learn`
    * Model Tracking: `Joblib` / `Pickle`

## 🚀 Key Features
* **Exploratory Data Analysis (EDA):** Visualizing correlations between features like age, cholesterol levels, and heart disease.
* **Data Preprocessing:** Handling missing values, feature scaling, and encoding categorical variables.
* **Model Selection:** Comparison of multiple algorithms:
    * Logistic Regression
    * Random Forest Classifier
    * Support Vector Machine (SVM)
* **Evaluation Metrics:** Accuracy, Precision, Recall, and F1-Score.

## 📈 Results
The final model (e.g., Random Forest) achieved the following performance on the test set:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | 89% |
| **Precision** | 87% |
| **Recall** | 90% |

