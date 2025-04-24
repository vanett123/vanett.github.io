# 📊 Analysis of Interview Questions on P&C Insurance Claims

This project explores responses to interview questions related to Property & Casualty (P&C) insurance claims, with a focus on uncovering **major process bottlenecks** and **general sentiment** within claims workflows. Using Natural Language Processing (NLP), this project analyzes textual data to generate insights through frequency analysis, visualizations, and sentiment scoring.

---

## 💡 Project Objective

To analyze qualitative insights from industry interviews and internal feedback related to P&C insurance claims. The goal is to:
- Identify recurring challenges (e.g., fraud detection, documentation issues)
- Visualize key pain points using word clouds
- Evaluate the overall sentiment of the content using sentiment analysis

---

## 🔍 Key Features

- 🧼 **Text Preprocessing** using `nltk`:
  - Lowercasing
  - Punctuation removal
  - Tokenization
  - Stopword removal
  - Lemmatization
- ☁️ **Word Cloud Generation** using `WordCloud` to visualize frequently mentioned terms
- 😊 **Sentiment Analysis** using VADER from `nltk.sentiment` to assess tone and polarity
- 📈 **Frequency Distribution** to identify the most common terms and issues

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- `nltk` (Natural Language Toolkit)
- `wordcloud`
- `matplotlib`

---

## 🧪 Sentiment Analysis Example

Using VADER (Valence Aware Dictionary and sEntiment Reasoner), the overall sentiment score was computed:

```python
from nltk.sentiment.vader import SentimentIntensityAnalyzer

nltk.download('vader_lexicon')
sent_analyzer = SentimentIntensityAnalyzer()
sentiment_score = sent_analyzer.polarity_scores(text)
print("Sentiment Score:", sentiment_score)
# vanett.github.io
