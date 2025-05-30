# 📊 Solana Meme Coin Analytics Dashboard (Twitter + Reddit + Dex + Google Sheets)

This repository is a unified crypto analytics toolkit to track Solana-based meme coins across multiple platforms—Twitter, Reddit, and decentralized exchanges (DEX). Each module pushes data to Google Sheets for real-time monitoring of sentiment, volume, and trends.

---

## 🔧 Features

- Twitter sentiment & trend tracking (Tweepy and Apify)
- Reddit discussion monitoring with keyword analysis
- DEX Screener integration for live token stats
- Google Sheets sync for shareable dashboards
- Ideal for meme coin discovery, hype tracking, and community analysis

---

## 📁 Included Notebooks

### 1. `Dex Screener dashboard googlesheet.ipynb`
> Fetches real-time token data (price, volume, % change) from Dex Screener API and updates a Google Sheet. Useful for live tracking of trending Solana meme tokens.

### 2. `Reddit Solana Dashboard through googlesheet.ipynb`
> Scrapes Reddit posts and discussions about Solana meme coins. Aggregates metrics like post volume and sentiment, syncing insights to Google Sheets.

### 3. `Twitter Solana Meme coin Apify.ipynb`
> Uses Apify to scrape tweets and hashtags related to Solana meme coins. Tracks volume, keywords, and engagement trends.

### 4. `Twitter solana meme through tweepy.ipynb`
> Leverages the Tweepy API to collect live tweets mentioning Solana meme coins. Gathers metadata such as user, likes, retweets, and timestamps.

---

## 📌 Use Cases

- Detect rising meme coins before they trend
- Monitor community sentiment in real-time
- Build datasets for predictive crypto modeling
- Run scheduled social media and market reports

---

## ⚙️ Tech Stack

- **Python** (Jupyter Notebooks)
- **Google Sheets API**
- **Reddit API (PRAW)**
- **Twitter API (Tweepy)**
- **Apify**
- **Dex Screener API**
- **Pandas, Requests, OAuth2, JSON**

---

## 🚀 Getting Started

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/solana-meme-analytics-dashboard.git
cd solana-meme-analytics-dashboard
