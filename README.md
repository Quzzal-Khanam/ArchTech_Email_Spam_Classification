# 📧 Project: Email Spam Classifier

## 📝 Overview

This project is a Machine Learning application designed to automatically classify messages as **Spam** or **Ham (Safe)**. Using Natural Language Processing (NLP) techniques and the Naive Bayes algorithm, the model identifies "spammy" patterns and keywords to protect user inboxes.

## 🚀 Key Features

* **NLP Pipeline:** Implements text cleaning and tokenization.
* **Bigram Analysis:** Uses `ngram_range=(1, 2)` to analyze both individual words and two-word phrases (e.g., "Cash Prize").
* **Probability Scoring:** Provides a confidence percentage for every prediction.
* **Model Persistence:** Saves the trained model using `joblib` so it can be reused without retraining.

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** * `Pandas` (Data Manipulation)
* `Scikit-Learn` (Machine Learning & Vectorization)
* `Seaborn/Matplotlib` (Visualization)
* `Joblib` (Model Export)



## 📊 Dataset

The model is trained on the **UCI SMS Spam Collection** dataset, which contains over 5,500 labeled messages.

## 📉 Performance & Evaluation

The model's performance is evaluated using a Confusion Matrix and an F1-Score to ensure high precision (minimizing false alarms).

| Metric | Score (Approx) |
| --- | --- |
| **Accuracy** | 98% |
| **Precision** | High (Critical for Spam) |
| **Recall** | High |

## 💻 How to Run

1. **Install dependencies:**
```bash
pip install pandas scikit-learn matplotlib seaborn joblib

```


2. **Run the script:**
```bash
python email_spam_project.py

```


3. **Predict:** Use the `check_with_probability()` function to test your own custom emails.

3. Paste the text above into it.

**Since we've finished the code, the evaluation, and the documentation, is your "Email Spam" project ready for submission, or would you like to add a "Task 2" to this project series?**
