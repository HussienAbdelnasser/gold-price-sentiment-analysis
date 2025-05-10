# 📈 Gold Price & News Sentiment Analysis 🪙📰

This project explores how **gold prices** fluctuate over time and how **news headlines** might influence market sentiment using **data from 2000 onwards**. It combines **data visualization**, **correlation analysis**, and **text sentiment analysis** to uncover trends and patterns.

---

## 📂 Dataset

The dataset includes:
- Daily gold price data (open, high, low, close, volume)
- Timestamped news headlines

📥 Source: [Kaggle Dataset](https://www.kaggle.com/datasets/romanfonel/precious-metals-history-since-2000-with-news)

---

## 🧠 What I Did

### 🧹 Data Cleaning & Preparation
- Converted timestamp to datetime format
- Removed duplicates
- Set timestamp as index

### 📊 Exploratory Data Analysis (EDA)
- Line charts for price & volume trends
- Histograms of price distribution
- Correlation heatmap for price features

### 🧪 Sentiment Analysis
- Used `TextBlob` to analyze sentiment polarity of headlines
- Categorized headlines into **Positive**, **Negative**, and **Neutral**
- Created a boxplot to compare closing prices across sentiment labels

---

## 📌 Key Insights

- **Price Trend**: Gold prices have experienced notable fluctuations, with certain peaks aligning with news sentiment.
- **Volume**: Volume spikes during specific periods, possibly tied to major economic events.
- **Sentiment vs Price**: Positive headlines generally align with slightly higher closing prices, but outliers exist in all categories.
- **Correlation**: Strong correlation between `open`, `close`, `high`, and `low` prices, as expected.

---

## 🛠️ Tools Used

- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **TextBlob** (for sentiment analysis)
- **Jupyter Notebook**

---

## 💡 How to Use

1. Clone the repo or download the files
2. Run the Jupyter notebook
3. Explore the analysis and feel free to extend it with your own ideas!

---

## 🔗 Connect With Me

If you liked this project or have feedback, feel free to connect!

- 🌐 [LinkedIn](https:/www.linkedin.com/in/hussein-abdelnasser7/)
- 📬 Email: itshussein.ahmed@email.com

---

## 📁 Project Files

- `final_gold_data.csv` – Cleaned gold price + headlines data
- `gold_sentiment_analysis.ipynb` – Main Jupyter notebook with all the analysis
