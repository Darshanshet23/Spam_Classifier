# 📧 Email Spam Classifier

This project is a simple machine learning application that classifies emails as **spam** or **not spam** using Natural Language Processing (NLP) and a trained machine learning model.

## 🚀 Project Overview

The model is trained on a labeled dataset of emails and can predict whether a given email message is spam. A Flask web app (`app.py`) is included to test predictions interactively via a browser.

---

## 📁 Project Structure

```
Email_Spam_Classifier/
│
├── app.py # Flask application to run the model
├── model.pkl # Trained spam classification model
├── vectorizer.pkl # CountVectorizer or TfidfVectorizer used to transform text
├── spam.csv # Raw dataset used for training
├── Untitled.ipynb # Jupyter notebook for preprocessing and model training
├── .gitignore # Files/folders to ignore in Git
├── README.md # Project documentation

```


---

## 📊 Dataset

The dataset (`spam.csv`) contains labeled email messages with two categories:
- `spam`: unwanted email
- `ham`: legitimate (not spam) email

---

## 🧠 Model Used

- **CountVectorizer** or **TfidfVectorizer** for text transformation
- **Naive Bayes classifier** for classification
- Evaluation metrics include Accuracy, Precision, Recall, and Confusion Matrix

---

## 🧪 How to Run

1. **Install requirements** (if any):
   ```
   pip install flask scikit-learn pandas
   ```

2. **Run the Flask app:**
    ```
    python app.py
    ```

3. **Open browser and go to:**
    ```
    http://localhost:5000
    ```