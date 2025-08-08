# 📧 Spam vs Ham Classifier

This project implements a **Spam-Ham (SMS Spam Detection)** classifier using **Natural Language Processing (NLP)** and **Machine Learning**.  
It demonstrates text preprocessing, feature extraction using **Bag of Words (BoW)** and **TF-IDF**, and classification using **Naive Bayes** (`MultinomialNB`).

---

## 📂 Project Overview

The goal is to classify SMS messages as:
- **Spam**: Unwanted or unsolicited messages.
- **Ham**: Legitimate, non-spam messages.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **NLTK** – Tokenization, stopwords removal
- **scikit-learn** – Feature extraction (BoW, TF-IDF) and ML models
- **Pandas / NumPy** – Data handling
- **Matplotlib / Seaborn** – Visualization

---

## 🔄 Workflow

### 1️⃣ Data Preprocessing
- Lowercasing text
- Removing punctuation and numbers
- Tokenization
- Stopwords removal
- Lemmatization

### 2️⃣ Feature Extraction
- **Bag of Words (BoW)**: Counts of words in messages.
- **TF-IDF**: Weighted representation of word importance.

### 3️⃣ Model Training
- **Algorithm:** Multinomial Naive Bayes (`MultinomialNB`)
- **Why Naive Bayes?**
  - Works well with text classification
  - Efficient for large datasets
  - Performs exceptionally well with word frequency-based features

### 4️⃣ Model Evaluation
- Metrics: Accuracy, Precision, Recall, F1-score
- Achieved **98% Accuracy** using TF-IDF + MultinomialNB

---

## 📈 Results

| Feature Extraction | Algorithm       | Accuracy |
|--------------------|----------------|----------|
| Bag of Words (BoW) | MultinomialNB  | 96%      |
| TF-IDF             | MultinomialNB  | **98%**  |

---

## 📌 Key Takeaways
- TF-IDF generally performs better than BoW for spam detection.
- Naive Bayes is a strong baseline for text classification problems.
- Proper preprocessing (stopwords removal, lemmatization) boosts performance.

---


