# SMS_spam_classifier
SMS Spam Classifier is a machine learning web app built with Streamlit that detects whether a message is spam or not. It uses a trained Multinomial Naive Bayes model with TF-IDF vectorization to make accurate predictions in real time.
# 📩 SMS Spam Classifier (Streamlit App)

## 🚀 Try the App

Paste a message → Click “Check Message” → Instantly see if it’s SPAM or NOT SPAM!

## 🧠 Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- Pickle

## 📁 Files in This Project

├── app.py # Streamlit application
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt # List of Python dependencies
├── Procfile # For Heroku deployment
└── README.md # Project documentation


---

## ✅ How to Run Locally

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/sms-spam-classifier.git
   cd sms-spam-classifier
pip install -r requirements.txt

streamlit run app.py

