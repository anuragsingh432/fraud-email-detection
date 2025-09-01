📧 Fraud Email Detection
🚀 Overview

This project detects whether an email is spam or ham (legitimate) using Machine Learning.
It applies text preprocessing, TF-IDF vectorization, and a classification model to predict fraud emails.

🛠️ Tech Stack

Python 3

Pandas, NumPy

Scikit-learn (Logistic Regression, TF-IDF, train/test split, evaluation metrics)

Matplotlib (visualization)

📂 Dataset

CSV dataset containing labeled emails (spam / ham).

Preprocessed with TF-IDF for feature extraction.

⚙️ Workflow

Load dataset (CSV).

Preprocess text (cleaning, tokenization).

Convert emails into features using TF-IDF Vectorizer.

Train Logistic Regression model.

Evaluate with Accuracy, Precision, Recall, F1-score, Confusion Matrix.

Predict on new/unseen emails.

📊 Results

Achieved ~96% accuracy on test data.
