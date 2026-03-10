# 🫁 Lung Cancer Survival Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

A Machine Learning project that predicts **whether a lung cancer patient survives or not** based on medical diagnosis data and patient health information.

This project applies **data analysis and classification algorithms** to identify patterns in patient health records and estimate survival outcomes.

---

# 📊 Project Objective

The objective of this project is to build a **predictive system** that determines the survival probability of a lung cancer patient based on clinical and lifestyle features such as:

* Age
* Smoking history
* Cancer stage
* Treatment type
* Medical conditions

The system uses **Machine Learning models** to analyze the data and predict patient survival.

---

# 📂 Dataset Description

The dataset contains detailed medical and lifestyle information about lung cancer patients.

| Feature            | Description                      |
| ------------------ | -------------------------------- |
| id                 | Unique identifier of patient     |
| age                | Age of the patient               |
| gender             | Male / Female                    |
| country            | Country of residence             |
| diagnosis_date     | Date of lung cancer diagnosis    |
| cancer_stage       | Stage of cancer (I, II, III, IV) |
| family_history     | Family history of cancer         |
| smoking_status     | Smoking habits                   |
| bmi                | Body Mass Index                  |
| cholesterol_level  | Cholesterol level                |
| hypertension       | High blood pressure status       |
| asthma             | Asthma condition                 |
| cirrhosis          | Liver cirrhosis                  |
| other_cancer       | Other cancer history             |
| treatment_type     | Treatment received               |
| end_treatment_date | Treatment completion date        |
| survived           | Target variable (Yes / No)       |

---

# ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

# 🤖 Machine Learning Approach

The project follows the standard **Machine Learning workflow**:

1. Data Loading
2. Data Cleaning
3. Handling Date Features
4. Encoding Categorical Variables
5. Exploratory Data Analysis
6. Feature Selection
7. Model Training
8. Model Evaluation

Model Used:

🏆 **Random Forest Classifier**

---

# 📊 Data Analysis & Visualization

Exploratory Data Analysis includes:

* Correlation Heatmap
* Feature Distribution
* Survival Rate Analysis
* Feature Importance

Key factors affecting survival include:

* Cancer Stage
* Smoking Status
* Age
* Treatment Type
* Pre-existing medical conditions

---

# 📈 Model Performance

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report

The model successfully predicts patient survival with strong performance using the Random Forest algorithm.

---

# 📁 Repository Structure

```
lung-cancer-survival-prediction
│
├── lung_cancer_Detect.ipynb
├── lung_cancer_dataset.csv
├── README.md
├── .gitignore
├── LICENSE
```

---

# 🚀 How to Run the Project

Clone the repository:

```bash
git clone https://github.com/yourusername/lung-cancer-survival-prediction.git
```

Install required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Run the notebook in:

* Google Colab
* Jupyter Notebook

---

# 👨‍💻 Author

**Tarun Kohli**

Artificial Intelligence & Data Science Student
Aspiring **Data Analyst / Data Scientist**

GitHub:
https://github.com/tarunkohli-297

---

# ⭐ Support

If you found this project useful, please consider **starring the repository** ⭐
