# 🧠 AI Fact Checker

A real-time news headline checker powered by machine learning and Streamlit.  
It predicts whether a news headline is likely **REAL** or **FAKE**, based on trained patterns from fake news datasets.

---

## 📸 Demo Screenshot


---

## 🚀 Features

- ✅ Real-time input for checking any headline
- 🤖 ML model trained on labeled fake/real news data
- 📊 Confidence score for each prediction
- 🌐 Streamlit-powered web app UI
- 🐳 Fully Dockerized for portability

---

## 🛠 Tech Stack

| Layer            | Tool                        |
|------------------|-----------------------------|
| Language         | Python 3.9                  |
| ML/NLP           | scikit-learn, TfidfVectorizer |
| Web UI           | Streamlit                   |
| Packaging        | Docker, Docker Compose      |
| Dev Environment  | VS Code                     |

---

## 📂 Project Structure

ai-fact-checker/ ├── app/ │ └── main.py # Streamlit app ├── model/ │ ├── train_model.py # Model training script │ 
├── predictor.py # Predict function (loads model) │ ├── news_model.pkl # Trained model (generated) │ 
└── vectorizer.pkl # TF-IDF vectorizer (generated) ├── data/ │ 
└── fake_and_real_news.csv # Sample training data ├── requirements.txt ├── Dockerfile └── docker-compose.yml
