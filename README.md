# Grievance Classification Using ML and NLP (42 Lakh+ Records)

This project involves building a robust machine learning model to classify consumer financial complaints into relevant categories using Natural Language Processing techniques.

## 📦 Dataset
[Download grievance.csv from Google Drive](https://drive.google.com/file/d/1f0EG1G4lrWgHnjoh0XSUZdZDLCkqeG3o/view?usp=drive_link)

---

## 📊 Dataset Overview

- **Source**: Consumer Financial Protection Bureau (CFPB)
- **Records**: 42,80,531 entries
- **Target Variable**: `Product` (multiclass)
- **Text Columns Used**: `Issue`, `Sub-issue`, `Consumer complaint narrative`

---

## 🧠 Objective

- Classify complaints based on text narratives.
- Improve prediction accuracy using Bag-of-Words & machine learning techniques.
- Evaluate multiple models and select the best performer.

---

## 🔍 Key Steps

1. **Data Cleaning**:
   - Removed missing/empty complaint narratives.
   - Cleaned text: lowercased, removed punctuation, stopwords.

2. **Feature Engineering**:
   - Combined text columns into one.
   - Used CountVectorizer for BoW representation.

3. **Modeling**:
   - Logistic Regression (~92% accuracy)
   - Naive Bayes (~65% accuracy)
   - Decision Tree Classifier (**~94% accuracy**)

4. **Evaluation**:
   - Used classification report, confusion matrix, precision, recall.
   - Handled class imbalance using support metrics.

---



