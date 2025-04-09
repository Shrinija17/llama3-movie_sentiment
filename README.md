
# 🦄 Unicorn Vibes: AI-Powered Tweet Sentiment Analysis

**Analyzing real-time public sentiment around the movie _Death of a Unicorn_ using X (Twitter) API + Groq's LLaMA 3 model.**

---

## 🚀 Project Summary

This project pulls live tweets related to the upcoming movie **Death of a Unicorn**, uses **Groq's AI model (LLaMA 3)** for summarization and sentiment analysis, and visualizes public opinion.

🔍 NLP + 📊 Data Viz + 🐍 Python = 💥 Real-time movie sentiment tracker.

---

## 🛠️ Tools Used

- **X (Twitter) API v2** – fetches real-time tweets
- **Groq API (LLaMA 3)** – analyzes tweet sentiment & opinions
- **Python** – core scripting
- **Pandas** – data handling
- **Matplotlib** – visualizations
- **WordCloud** – highlights trending keywords
- *(Optional)* Streamlit – interactive dashboard (coming soon!)

---

## 📈 Features

- Fetches 50 live tweets using keyword `"Death of a Unicorn"`
- Uses LLM to:
  - Summarize public opinion
  - Detect sentiment (positive, neutral, negative)
  - Identify hype or sarcasm
- Classifies and visualizes sentiment breakdown
- Saves results to `.csv` for reuse or reporting

---

## 📊 Sample Visualization

![Sentiment Chart](sentiment_chart.png)  
*Live breakdown of public sentiment around the film.*

---

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/shrinijakummari/unicorn-vibes.git
   cd unicorn-vibes
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set your API keys in the Python file or `.env`:
   - `X_BEARER_TOKEN`
   - `GROQ_API_KEY`

4. Run the notebook:
   ```bash
   jupyter notebook unicorn_sentiment_analysis.ipynb
   ```

---

## 📦 Output

- `death_of_a_unicorn_analysis.csv` – full tweet-level sentiment dataset
- `sentiment_chart.png` – sentiment bar chart
- `wordcloud.png` – optional keyword word cloud

---

## 📌 Author

**Shrinija Kummari**  
🔗 [LinkedIn](https://www.linkedin.com/in/shrinija-kummari)  
📬 shrinija.kummari@baruchmail.cuny.edu

---

## ✨ Future Plans

- Streamlit Web App UI
- Auto-post Groq-generated summary to X
- Compare multiple movies' sentiments side by side

