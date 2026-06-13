# 🎓 Student Performance Prediction System

An End-to-End Machine Learning Project that predicts a student's Mathematics score based on demographic and academic attributes.

The project follows a complete Machine Learning lifecycle including Data Ingestion, Data Transformation, Model Training, Model Evaluation, Prediction Pipeline, Web Application Development, and Cloud Deployment.

---

## 🚀 Project Overview

This application predicts the Mathematics score of a student using:

- Gender
- Race / Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

The trained machine learning model processes these features and generates an estimated Mathematics score.

---

## 📌 Problem Statement

Educational institutions often need insights into student performance.

This project aims to build a machine learning system capable of predicting Mathematics scores using student-related information and academic indicators.

---

## 🏗️ Project Architecture

```text
Dataset
   │
   ▼
Data Ingestion
   │
   ▼
Data Transformation
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Model Saving (.pkl)
   │
   ▼
Prediction Pipeline
   │
   ▼
Flask Web Application
   │
   ▼
AWS Deployment
```

---

## 📂 Project Structure

```text
mlproject/
│
├── artifacts/
│   ├── model.pkl
│   ├── preprocessor.pkl
│   ├── train.csv
│   ├── test.csv
│
├── notebook/
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   ├── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── application.py
├── requirements.txt
├── setup.py
└── README.md
```

---

## ⚙️ Technologies Used

### Programming Language

- Python

### Machine Learning

- Scikit-Learn
- CatBoost
- XGBoost
- Random Forest
- Gradient Boosting

### Data Processing

- NumPy
- Pandas

### Visualization

- Matplotlib
- Seaborn

### Web Development

- Flask
- HTML
- Bootstrap

### Deployment

- AWS Elastic Beanstalk
- AWS EC2 (Planned)
- GitHub

---

## 🔥 Features

### Data Ingestion

- Reads dataset
- Splits training and testing data
- Saves artifacts

### Data Transformation

- Missing value handling
- Standard Scaling
- One Hot Encoding
- Column Transformer Pipeline

### Model Training

Multiple regression algorithms are evaluated:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- CatBoost Regressor
- KNN Regressor

Best-performing model is automatically selected and saved.

### Prediction Pipeline

Loads:

- Trained Model
- Preprocessor

Accepts user inputs and returns predicted Mathematics score.

### Logging System

Custom logging system records:

- Training progress
- Data processing steps
- Model evaluation

### Exception Handling

Custom exception class provides:

- File name
- Line number
- Detailed error message

---

## 🌐 Web Application

The Flask application provides a user-friendly interface where users can:

- Enter student details
- Submit data
- Receive predicted Mathematics score instantly

---

## ☁️ Deployment

This project was successfully deployed on:

✅ AWS Elastic Beanstalk

Deployment configuration files:

```text
.ebextensions/
└── python.config
```

The application was accessible through the generated AWS endpoint during the active AWS Free Tier period.

Future enhancements include:

- EC2 Deployment
- CI/CD Pipeline using GitHub Actions
- Docker Containerization

---

## 📊 Machine Learning Workflow

```text
Raw Data
   │
   ▼
Data Ingestion
   │
   ▼
Preprocessing
   │
   ▼
Feature Engineering
   │
   ▼
Model Training
   │
   ▼
Model Selection
   │
   ▼
Model Serialization
   │
   ▼
Prediction API
   │
   ▼
Flask UI
```

---

## ▶️ Installation
```
### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python application.py
```

---

## 📸 Screenshots

### Home Page

<img width="1358" height="675" alt="Screenshot 2026-06-13 211744" src="https://github.com/user-attachments/assets/805541ee-33a6-4ebf-9f06-b605f3bb969f" />

### Prediction Form

<img width="1361" height="676" alt="Screenshot 2026-06-13 213200" src="https://github.com/user-attachments/assets/3d9e0c9f-6b2e-4b04-b423-0237747d6bee" />


### Prediction Result

<img width="1365" height="680" alt="Screenshot 2026-06-13 213228" src="https://github.com/user-attachments/assets/19c2d30b-a268-494b-8740-dded66998d09" />


---

## 🎯 Future Improvements

- Docker Support
- CI/CD Pipeline
- EC2 Deployment
- Model Monitoring
- Database Integration
- User Authentication
- REST API Development

---

## 👨‍💻 Author

**Gopal Bhargav**

B.Tech CSE Student  
IMS Engineering College, Ghaziabad

GitHub: https://github.com/gopalbhargav

LinkedIn: https://www.linkedin.com/in/gopal-bhargav-7a104a249

---

## ⭐ If you found this project useful, consider giving it a star.
