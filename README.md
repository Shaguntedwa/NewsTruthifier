# NewsTruthifier
# 🧠 News Truthifier – Fake News Detection with Machine Learning

This project is a lightweight but powerful **text classification** tool that detects fake news using a **Logistic Regression model**.

## 📰 What It Does
- Classifies news as **Real** or **Fake**
- Uses `TfidfVectorizer` for feature extraction
- Trained and evaluated on labeled news articles

## 📊 Model Used
- **Logistic Regression** (accuracy: ~95%)
- Text preprocessing with `TfidfVectorizer`
- Evaluation via Confusion Matrix & Classification Report

## 💡 Example Use

```python
predict_news("NASA confirms water on the moon!") 
# Output: 📰 Real News
