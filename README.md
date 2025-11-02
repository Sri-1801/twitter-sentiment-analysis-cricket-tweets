# 🏏 Twitter Sentiment Analysis on Cricket Tweets

### 📘 Overview
This project analyzes public sentiment around **cricket-related tweets** using **Python (TextBlob)** for NLP and **Power BI** for visualization.  
It identifies whether tweets are **Positive**, **Negative**, or **Neutral**, and visualizes patterns, trends, and word usage across time.

---

## 🧠 Objective
To understand audience perception and emotion towards cricket events through real-time Twitter data, using sentiment scoring and interactive dashboards.

---

## 🧩 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Python** | Data cleaning, sentiment scoring |
| **TextBlob** | NLP-based polarity detection |
| **Pandas, Matplotlib** | Data wrangling & exploratory analysis |
| **Power BI** | Interactive dashboard visualization |
| **GitHub** | Project hosting & portfolio sharing |

---

## 🗂️ Dataset Overview
- **Source:** Twitter (collected using `snscrape`)
- **Total Records:** ~60,000 tweets
- **Columns:**
  - `date`
  - `text`
  - `clean_text`
  - `sentiment_score`
  - `sentiment_label`
  - `TweetDate`
- **Sentiment Categories:** Positive, Negative, Neutral

---

## ⚙️ Project Workflow

### 1️⃣ Data Collection
Tweets were scraped using **snscrape** based on cricket hashtags and keywords.

### 2️⃣ Data Cleaning & Sentiment Labeling
- Removed URLs, mentions, emojis, and special characters  
- Converted text to lowercase and removed stopwords  
- Used **TextBlob polarity** to classify:
  - `> 0` → Positive  
  - `= 0` → Neutral  
  - `< 0` → Negative  

### 3️⃣ Visualization in Power BI
Created an interactive dashboard showing:
- **Word Cloud:** Most frequent keywords  
- **Pie Chart:** Sentiment distribution  
- **KPI Cards:** Total, Positive, Negative, Neutral tweet counts  
- **Line Chart:** Sentiment trend over time  
- **Slicer:** Sentiment-based filtering (Positive / Negative / Neutral)

---

## 📊 Dashboard Insights
- Majority of tweets are **Positive**, showing enthusiasm among fans.  
- **Negative sentiment spikes** align with match losses or controversies.  
- **Frequent words:** “team”, “match”, “win”, “run”, “player”, “India”.  
- Consistent positive trend across the analyzed time period.

---

## 🧾 Deliverables
- ✅ Python notebook (`twitter_sentiment_analysis.ipynb`)
- ✅ Cleaned dataset (`cricket_tweets_cleaned.csv`)
- ✅ Power BI file (`.pbix`)
- ✅ Dashboard PDF export

---

## 🏁 Conclusion
The analysis provides a clear picture of how cricket-related discussions evolve on Twitter.  
Most users express **positive sentiment**, reflecting excitement and support during major matches or events.  
This project demonstrates skills in **data cleaning, NLP sentiment scoring, and Power BI storytelling** — key competencies for data analysts.

---

### 👩‍💻 Author
**Dhanujasri Sagadevan**  
_Data Analyst_  
  



