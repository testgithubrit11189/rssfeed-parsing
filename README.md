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
feedparser.ipynb – Google Colab notebook

news_articles.csv – Full CSV file with all scraped news

news_<lang>.csv – Language-wise separated files (e.g. news_en.csv, news_pt.csv, etc.)

README.md – This file

## ✅ Steps:
Open feedparser.ipynb in Jupyter Notebook or Google Colab.

Run all cells in order.

The script will:

Scrape and parse news data from RSS feeds

Store the data in news_articles.csv

Detect the language of each article

##⚠️ Issues Encountered
Some RSS feeds did not contain summary or content fields.

Language detection (langdetect) struggles with very short or ambiguous text.

JupyterLite does not support required Python packages (e.g., feedparser), so the notebook must be run in Google Colab or a full Jupyter environment.

Encoding issues with non-English articles were fixed using UTF-8 output.
Save grouped files by language: news_en.csv, news_ja.csv, etc.

Create a summary table by country and save it as news_summary.csv

##🧠 Bonus Feature Implemented
Language Detection: Uses langdetect to tag articles by language.

Saves articles grouped by language into separate CSV files.

Ready to be integrated with APIs or dashboards.
