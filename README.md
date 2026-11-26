# 📩 SMS Spam Detector (Natural Language Processing)

A Machine Learning & NLP classification project that detects whether an SMS message is **Spam** or **Legitimate (Ham)** with **96.68% accuracy**.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas
* **NLP & Machine Learning:** Scikit-Learn (`TfidfVectorizer`, `MultinomialNB`)

## 🧠 Key Concepts Used
1. **Text Preprocessing & Stop-Words Removal:** Removed common English stop words to focus on meaningful keywords.
2. **TF-IDF Vectorization:** Converted raw text messages into numerical feature vectors based on word frequency and importance.
3. **Naive Bayes Classification:** Trained a `MultinomialNB` model for fast and accurate text classification.
4. **Custom Inference:** Tested the trained model on unseen custom messages in real time.

## 🚀 How to Run
Open `SMS_Spam_Detector.ipynb` in Google Colab using the badge inside the notebook to run and test your own messages.
