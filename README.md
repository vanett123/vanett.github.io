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
```

Sample Output:
```
Sentiment Score: {'neg': 0.147, 'neu': 0.711, 'pos': 0.142, 'compound': -0.0516}
```

This reflects a slightly negative tone, highlighting recurring concerns in the insurance claims process.

---

## 📊 Sample Output

![wordcloud]([https://drive.google.com/file/d/1NfRwb87KsBXVK2KeZYHFY0_oBlV184AR/view?usp=sharing])



---

## ⚙️ How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/repo-name.git
cd repo-name
```

2. **Install required packages:**

```bash
pip install nltk wordcloud matplotlib
```

3. **Launch the notebook:**

```bash
jupyter notebook
```

4. **Open the notebook and run all cells to:**
   - Clean and tokenize the text
   - Visualize word frequency
   - Analyze sentiment

---

## 🔎 Key Findings

- 🚫 Lack of fraud detection tools and analytics systems
- 📄 Incomplete documentation from policyholders
- 💬 Miscommunication during claims processing
- 🌪️ Difficulty handling complex or catastrophic events

These findings support the need for better automation, transparency, and data-driven tools in claims handling.

---

## 📬 Contact

Feel free to connect or reach out:

- 🔗 [LinkedIn]([https://www.linkedin.com/in/vanett-lamptey]) 
- 📧 Email: vanettlamptey@gmail.com 

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🌐 Portfolio

You can also explore more of my work at:  
**[vanett.github.io](https://vanett.github.io)** 
```

---

