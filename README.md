# 🌍 Web Scraping News from Different Countries Using RSS Feeds

## 📌 Objective

This project extracts and processes news data from various international RSS feeds. It parses headlines, publication dates, summaries, and URLs from over 20 sources, and includes **language detection** as a bonus feature.

---

## 🛠️ Technologies Used

- Python 3
- feedparser
- pandas
- langdetect
- Google Colab (for notebook execution)

---

## 📥 How to Run the Script

1. Clone the repository or open the notebook in Jupyter/Colab.
2. Install dependencies (in Jupyter or terminal):
3. pip install feedparser pandas langdetect

##▶️ How to Run the Script
📁 Files:
1.feedparser.ipynb – Google Colab notebook

2.news_articles.csv – Full CSV file with all scraped news

3.news_<lang>.csv – Language-wise separated files (e.g. news_en.csv, news_pt.csv, etc.)

4.README.md – This file

## ✅ Steps:
1.Open feedparser.ipynb in Jupyter Notebook or Google Colab.

2.Run all cells in order.

3.The script will:

4.Scrape and parse news data from RSS feeds

5.Store the data in news_articles.csv

6.Detect the language of each article

---

##⚠️ Issues Encountered


1.Some RSS feeds did not contain summary or content fields.

2.Language detection (langdetect) struggles with very short or ambiguous text.

3.JupyterLite does not support required Python packages (e.g., feedparser), so the notebook must be run in Google Colab or a full Jupyter environment.

4.Encoding issues with non-English articles were fixed using UTF-8 output.
5.Save grouped files by language: news_en.csv, news_ja.csv, etc.

6.Create a summary table by country 

---

##🧠 Bonus Feature Implemented

1.Language Detection: Uses langdetect to tag articles by language.

2.Saves articles grouped by language into separate CSV files.

