# 🔐 Password Strength Predictor

A Machine Learning-based Password Strength Prediction system that analyzes password characteristics and predicts whether a password is **Weak, Normal, or Strong**.

## 📌 Project Overview

This project uses Natural Language Processing (NLP) techniques and Machine Learning to predict password strength based on character-level features and password patterns.

The system also includes a Tkinter-based graphical user interface (GUI) that allows users to enter passwords and receive real-time strength predictions.

## 🎯 Project Objectives

- Analyze password characteristics.
- Extract character-level features using TF-IDF.
- Calculate password length and character frequencies.
- Train a Machine Learning classification model.
- Predict password strength for new user inputs.
- Develop a user-friendly desktop application.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLP
- TF-IDF Vectorization
- Matplotlib / Seaborn
- Tkinter
- Joblib
- SQLite

## ⚙️ Key Features

- Password length analysis.
- Lowercase and uppercase character analysis.
- Numerical digit analysis.
- Special character analysis.
- Character-level TF-IDF feature extraction.
- Machine Learning-based password classification.
- Saved model and vectorizer for predictions.
- Tkinter desktop interface.

## 📊 Password Strength Categories

| Label | Strength |
|---|---|
| 0 | Weak |
| 1 | Normal |
| 2 | Strong |

## 📂 Project Structure

```text
Password-Strength-Predictor/
│
├── NLP_password_strength.ipynb
├── UI.ipynb
├── password_model.pkl
├── tfidf_vectorizer.pkl
├── README.md
└── requirements.txt
```

## 🚀 Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/TharinduKariyawasam03/Password-Strength-Predictor.git
```

### 2. Navigate to the project folder

```bash
cd Password-Strength-Predictor
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the desktop application

```bash
python password_strength_ui.py
```

Make sure the trained model and TF-IDF vectorizer files are in the project directory.

## 🧠 Machine Learning Workflow

1. Data Loading and Exploration
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. TF-IDF Character-Level Feature Extraction
6. Model Training
7. Model Evaluation
8. Model Saving
9. User Input and Password Strength Prediction
10. Tkinter GUI Development

## 👨‍💻 Developer

**Tharindu Kariyawasam**

Data Science Undergraduate Student

- GitHub: [TharinduKariyawasam03](https://github.com/TharinduKariyawasam03)
- LinkedIn: [Tharindu Kariyawasam](https://www.linkedin.com/in/tharindu-kariyawasam-b63227345/)

---

⭐ If you find this project interesting, consider giving the repository a star!

**Note:** This project is developed for educational purposes. Its predictions are based on a trained Machine Learning model and should not be treated as a guarantee of password security.
