# 🩺 Breast Cancer Prediction using Machine Learning

> A supervised Machine Learning project that predicts whether a breast tumor is **Malignant** or **Benign** using the Wisconsin Breast Cancer Dataset.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

# 📖 Project Overview

Breast cancer is one of the leading causes of cancer-related deaths among women worldwide. Early detection significantly increases the chances of successful treatment.

In this project, I built and evaluated Machine Learning models capable of classifying breast tumors as either **Malignant (Cancerous)** or **Benign (Non-Cancerous)** using diagnostic measurements extracted from breast cell nuclei.

The project demonstrates the complete Machine Learning workflow, including data exploration, preprocessing, model training, evaluation, and interpretation of results.

---

# 🎯 Objectives

The main objectives of this project are to:

- Understand the Breast Cancer Wisconsin dataset.
- Perform Exploratory Data Analysis (EDA).
- Prepare the dataset for Machine Learning.
- Train and compare multiple classification models.
- Evaluate model performance using standard classification metrics.
- Identify the best-performing model.

---

# ❤️ Why This Project Matters

Machine Learning has the potential to support healthcare professionals by assisting in disease prediction and diagnosis.

Although this project is developed for educational purposes, it demonstrates how predictive models can contribute to medical decision support when used alongside professional clinical expertise.

---

# 📂 Dataset Information

**Dataset:** Breast Cancer Wisconsin Dataset

**Source:**
- UCI Machine Learning Repository
- Scikit-learn Built-in Dataset

### Dataset Summary

| Item | Value |
|------|------|
| Samples | 569 |
| Features | 30 Numerical Features |
| Target | Binary Classification |
| Classes | Malignant (0), Benign (1) |

The dataset contains measurements extracted from digitized images of breast cell nuclei, including:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

---

# 🛠️ Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning Models

- Logistic Regression
- Random Forest Classifier

### Development Environment

- Jupyter Notebook

---

# 🔄 Project Workflow

The project follows a standard Machine Learning pipeline:

### 1. Data Loading

- Loaded the Breast Cancer Wisconsin dataset.
- Converted the dataset into a Pandas DataFrame.
- Created readable diagnosis labels.

---

### 2. Exploratory Data Analysis (EDA)

Performed exploratory analysis by:

- Inspecting dataset structure.
- Examining statistical summaries.
- Checking for missing values.
- Checking duplicate records.
- Visualizing diagnosis distribution.
- Exploring feature correlations.

---

### 3. Data Preprocessing

The preprocessing stage included:

- Feature and target separation.
- Train-test split (80% training, 20% testing).
- Feature scaling using **StandardScaler**.
- Stratified sampling to preserve class distribution.

---

### 4. Model Development

Two supervised Machine Learning algorithms were trained.

### Logistic Regression

Chosen as a strong baseline model for binary classification problems due to its simplicity and interpretability.

### Random Forest Classifier

Chosen because ensemble learning methods can capture complex relationships while reducing overfitting.

---

### 5. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# 📈 Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **97.4%** |
| Random Forest | **96.5%** |

### Performance Summary

- Logistic Regression achieved the highest prediction accuracy.
- Random Forest also demonstrated excellent classification performance.
- Both models achieved strong precision and recall scores.
- The results indicate that relatively simple Machine Learning algorithms can achieve high predictive performance on this dataset.

---

# 📊 Visualizations

The project includes several visualizations, including:

- Diagnosis Distribution
- Feature Correlation Heatmap
- Confusion Matrix (Logistic Regression)
- Confusion Matrix (Random Forest)
- Top 10 Most Important Features (Random Forest)

---

# 💡 Key Insights

- The dataset contains highly informative numerical features.
- Feature scaling improved model performance.
- Logistic Regression slightly outperformed Random Forest on the test dataset.
- Random Forest provided valuable feature importance scores.
- Machine Learning models can effectively classify breast tumors using structured clinical data.

---

# 📁 Repository Structure

```
breast-cancer-prediction/
│
├── Breast_cancer_prediction.ipynb
├── breast_cancer_data.csv
├── README.md
├── requirements.txt
└── images/
```

---

# ▶️ How to Run

## Clone the repository

```bash
git clone https://github.com/Kazebakare/breast-cancer-prediction.git
```

## Navigate into the project directory

```bash
cd breast-cancer-prediction
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

# 🚀 Future Improvements

Future enhancements include:

- Hyperparameter tuning using GridSearchCV.
- Cross-validation for more robust model evaluation.
- Testing additional classification algorithms such as Support Vector Machine (SVM), Gradient Boosting, and XGBoost.
- Model deployment using Streamlit.
- Building an interactive web application for prediction.

---

# ⚠️ Disclaimer

This project was developed for educational and portfolio purposes only.

The trained models should **not** be used as a substitute for professional medical diagnosis or clinical decision-making.

---

# 👨‍💻 Author

**Kazeem Bakare**

**Data Scientist | Machine Learning & AI Enthusiast**

🌐 **Portfolio:** https://kazebakare.github.io

💻 **GitHub:** https://github.com/Kazebakare

---

## ⭐ Support

If you found this project helpful or interesting, consider giving it a ⭐ on GitHub.

It helps support my work and encourages me to continue building impactful Data Science and Machine Learning projects.
