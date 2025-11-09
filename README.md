# 📧 SMS Spam Detection Web App

A simple yet powerful **Machine Learning Web App** built using **Streamlit** that detects whether a message is **Spam** or **Not Spam**.  
This project uses **Natural Language Processing (NLP)** and **Scikit-learn** to classify text messages based on a trained model.

🔗 **Live Demo:** [View the deployed app on Render](https://sms-spam-detection1-1yy5.onrender.com) 

---

## 🚀 Features
✅ Clean and interactive **Streamlit UI**  
✅ Real-time spam prediction from user input  
✅ **NLTK preprocessing** (stopword removal, stemming, tokenization)  
✅ Trained on a labeled **SMS spam dataset**  
✅ Deployable on **Render**, **Streamlit Cloud**, or any cloud platform  

---

## 🧠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Frontend** | Streamlit |
| **Backend / ML** | Python, Scikit-learn, NLTK |
| **Modeling** | Multinomial Naive Bayes (or your chosen model) |
| **Deployment** | Render (Free Tier) |
| **Data Handling** | pandas, numpy |

---

## ⚙️ How It Works

1. The input message is cleaned using:
   - Lowercasing  
   - Tokenization  
   - Stopword removal  
   - Stemming (using NLTK’s PorterStemmer)
2. The cleaned text is vectorized using a **TF-IDF Vectorizer**.
3. The trained ML model predicts whether the text is **Spam** or **Not Spam**.

---

## 📂 Project Structure

Spam_Detection/
│
├── app.py # Streamlit app script

├── model.pkl # Trained ML model

├── vectorizer.pkl # TF-IDF vectorizer

├── spam.csv # Dataset used for training

├── requirements.txt # Dependencies

└── README.md # Project documentation


🧑‍💻 Author

Sahil Kumar

📧 Feel free to contribute, suggest improvements, or report issues!
