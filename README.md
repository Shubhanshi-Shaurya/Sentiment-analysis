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
├── app.py                # Main Streamlit application code
├── model.pkl             # Trained Logistic Regression model
├── vectorizer.pkl        # Fitted TF-IDF Vectorizer
├── requirements.txt      # List of dependencies
└── README.md             # Project documentation
```

---

## Model Insights
The model was trained on the IMDB dataset, consisting of 50,000 highly polar movie reviews.
- Feature Engineering: Used max_features=5000 to capture the most significant vocabulary.
- Preprocessing: Robust handling of NaN values and unclosed quotation marks in the dataset.
- Performance: Successfully achieved a balanced accuracy score after optimizing the data parsing engine.

---

## Learning Outcomes
- Data Wrangling: Resolved complex CSV ParserError and EOF issues using Python-based parsing engines.
- Model Persistence: Implemented Pickle for saving and loading models across different environments (Google Colab to local).
- Deployment: Created a functional UI that bridges the gap between a Python script and a user-facing application.

---

