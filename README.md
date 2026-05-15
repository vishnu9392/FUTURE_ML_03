# Resume Screening System

## Overview
This project is developed as part of the Future Interns Machine Learning Internship Task 3.

The objective of this project is to build a Machine Learning and NLP based Resume Screening System that automatically classifies resumes into different job categories based on resume content and skills.

The project uses Natural Language Processing (NLP) techniques and Machine Learning algorithms to analyze resume text and predict suitable job roles.

---

## Dataset
The dataset contains resume information including:
- Resume Text
- Resume Category
- Candidate Skills
- Job Role Information

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection
Loaded resume dataset from CSV format.

### 2. Data Preprocessing
- Removed missing values
- Converted resume text into lowercase
- Cleaned text data

### 3. NLP Processing
Used TF-IDF Vectorization to convert resume text into numerical format.

### 4. Model Building
Implemented Multinomial Naive Bayes classification model.

### 5. Resume Classification
Predicted suitable job categories based on resume skills and content.

### 6. Model Evaluation
Evaluated the model using:
- Accuracy Score
- Classification Report

---

## Project Structure

```text
FUTURE_ML_03
│
├── Resume.csv
├──  predictions.csv
├── images
├── Resume_Screening_System.ipynb
├── README.md
└── requirements.txt