## Movie Review Sentiment Analysis App

A machine learning-powered web application that classifies movie reviews as **Positive** or **Negative**. Built with **Python**, **Scikit-Learn**, and **Streamlit**, this project demonstrates a complete ML pipeline—from handling messy real-world data to local deployment.

---

##  Features
- **Text Preprocessing:** Cleans and tokenizes raw text data using Regular Expressions to remove noise.
- **TF-IDF Vectorization:** Converts text into numerical features while accounting for word importance.
- **Logistic Regression:** A high-accuracy classification model trained on the IMDB Movie Reviews dataset.
- **Interactive UI:** A real-time web interface built with Streamlit for instant sentiment prediction.

---

##  Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, Pickle, Streamlit, Regex
- **Model:** Logistic Regression
- **Vectorization:** TfidfVectorizer

---

##  Project Structure
```text
sentiment_analysis/
│
├── app.py                
├── model.pkl             
├── vectorizer.pkl        
├── requirements.txt      
└── README.md             
```

---

## Learning Outcomes
- Data Wrangling: Resolved complex CSV ParserError and EOF issues using Python-based parsing engines.
- Model Persistence: Implemented Pickle for saving and loading models across different environments (Google Colab to local).
- Deployment: Created a functional UI that bridges the gap between a Python script and a user-facing application.

---

