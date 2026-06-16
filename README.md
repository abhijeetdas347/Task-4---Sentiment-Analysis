# 📊 Task 4 — Sentiment Analysis
### CodTech IT Solutions | Data Analytics Internship


---

## 🏢 Internship Details

| Field | Details |
|---|---|
| **Company** | CODTECH IT Solutions Pvt. Ltd. |
| **Intern Name** | Abhijeet Das |
| **Intern ID** | CITS500 |
| **Domain** | Data Analytics |
| **Task** | Task 4 - Sentiment Analysis |
| **Duration** | 4 Weeks |
| **Mentor** | Neela Santhosh Kumar |

---

## 📌 Objective

Perform **Sentiment Analysis** on textual data (product reviews) using **Natural Language Processing (NLP)** techniques to classify text as **Positive** or **Negative**.

---

## 📁 Project Structure

```
Task-4-Sentiment-Analysis/
│
├── sentiment_analysis.ipynb   # Main Jupyter Notebook (all code here)
├── README.md                  # Project documentation (this file)
└── requirements.txt           # Python dependencies
```

---

## 🛠️ Technologies & Libraries Used

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical plots |
| `nltk` | Tokenization, stopwords, lemmatization |
| `textblob` | Lexicon-based sentiment scoring |
| `scikit-learn` | TF-IDF, ML models, evaluation metrics |
| `wordcloud` | Word cloud visualization |

---

## 🔄 Workflow / Pipeline

```
Raw Text Reviews
      │
      ▼
1. Exploratory Data Analysis (EDA)
      │
      ▼
2. Text Preprocessing
   • Lowercasing
   • Punctuation & number removal
   • Stopword removal
   • Lemmatization (WordNet)
      │
      ▼
3. Feature Engineering
   • TF-IDF Vectorization (unigrams + bigrams)
      │
      ▼
4. Model Training & Evaluation
   • TextBlob (Lexicon-based)
   • Logistic Regression
   • Naive Bayes
      │
      ▼
5. Visualization & Insights
   • Word Clouds
   • Confusion Matrix
   • Polarity Distribution
   • Model Comparison Chart
      │
      ▼
6. Predict on New Custom Reviews
```

---

## 📊 Results Summary

| Model | Approach | Notes |
|-------|----------|-------|
| TextBlob | Lexicon-based | No training needed, uses polarity dictionary |
| Logistic Regression | ML + TF-IDF | Best performing ML model |
| Naive Bayes | ML + TF-IDF | Fast probabilistic classifier |

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Open the notebook
```bash
jupyter notebook sentiment_analysis.ipynb
```

### 4. Run all cells
- Click **Kernel → Restart & Run All**

---

## 💡 Key Insights

- Lexicon-based methods (TextBlob) work well without training data but miss context
- TF-IDF with bigrams captures important two-word phrases like *"not good"*, *"very bad"*
- Logistic Regression outperforms Naive Bayes on this dataset
- Lemmatization + stopword removal significantly improves model quality
- Word Clouds reveal dominant words like *amazing, love* (positive) vs *waste, terrible* (negative)

---

## 🚀 Future Scope

- Use large real-world datasets (IMDb, Amazon, Twitter)
- Implement Deep Learning models (LSTM, BERT, RoBERTa)
- Add Neutral sentiment class (3-class classification)
- Deploy as interactive web app using Streamlit or Flask

---

## 📜 License

This project was created as part of the **CodTech IT Solutions Data Analytics Internship**.
