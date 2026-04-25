# 🕷️ Distributed Web Crawler using Dask

A high-performance **distributed web crawler** that fetches web pages in parallel using **Dask**, performs **text analysis**, **sentiment detection**, **trend identification**, and generates **interactive dashboards**. Built with **Python, Dask, and BeautifulSoup**, it combines **speed, efficiency, and real-time analytics** in one platform. 🚀📊

---

## Features

- 🔄 **Distributed crawling** using Dask with 4 parallel workers
- 📊 **Word frequency analysis** – Top 15, Top 20, and Last 20 words
- 💖 **Sentiment analysis** – Positive/Neutral/Negative detection using TextBlob
- 📈 **Trend detection** – Keyword velocity calculation (% increase)
- 🏆 **Source authority ranking** – Trust scores for each website
- 🎨 **Interactive HTML dashboard** – Custom dark theme with export to PDF
- 📁 **Multiple input options** – 5 ways to provide URLs
- 💾 **Persistent storage** – All data saved to Google Drive

---

## Tech Stack

| Category | Technology |
|----------|------------|
| **Language** | Python 3.12 |
| **Distributed Computing** | Dask (4 workers) |
| **Web Scraping** | Requests, BeautifulSoup4 |
| **Data Analysis** | Pandas, Collections.Counter |
| **Text Processing** | NLTK (stopwords), Regex |
| **Sentiment Analysis** | TextBlob |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Google Colab |
| **Storage** | Google Drive |

---

## Screenshots

### Dashboard & Results

| Dashboard Main View | Top Keywords Analysis |
|:-------------------:|:---------------------:|
| ![Dashboard Main](images/dashboard_main.png) | ![Top Keywords](images/top_keywords.png) |

| Performance Comparison | Sentiment Distribution |
|:---------------------:|:----------------------:|
| ![Performance](images/performance_chart.png) | ![Sentiment](images/sentiment_chart.png) |

| Trending Keywords | Source Authority Ranking |
|:-----------------:|:------------------------:|
| ![Trending](images/trending_words.png) | ![Authority](images/source_authority.png) |

### Crawl Output & Word Frequency

| Distributed Crawl Output | Word Frequency Results |
|:------------------------:|:----------------------:|
| ![Crawl Output](images/crawl_output.png) | ![Word Frequency](images/word_frequency_output.png) |

### Dashboard Stats & Colab Execution

| Dashboard Statistics | Google Colab Execution |
|:--------------------:|:----------------------:|
| ![Dashboard Stats](images/dashboard_stats.png) | ![Colab Cells](images/colab_cells.png) |

---

## Results Summary

### Crawl Performance

| Metric | Value |
|--------|-------|
| URLs Attempted | 9 |
| Successful Crawls | 6 |
| Crawl Time (Dask) | 3.85 seconds |
| Crawl Time (Sequential) | 3.97 seconds |
| Speedup | 1.03x |

### Word Frequency Statistics

| Metric | Value |
|--------|-------|
| Total Unique Words | 2,564 |
| Total Word Occurrences | 4,430 |
| Most Frequent Word | 'ago' (99 times) |

### Top 10 Keywords

| Rank | Word | Frequency |
|------|------|-----------|
| 1 | ago | 99 |
| 2 | days | 52 |
| 3 | hours | 50 |
| 4 | points | 30 |
| 5 | hide | 30 |
| 6 | brief | 23 |
| 7 | anthony | 17 |
| 8 | technology | 16 |
| 9 | day | 14 |
| 10 | best | 14 |

### Sentiment Analysis

| Category | Count | Percentage |
|----------|-------|------------|
| Positive | 4 | 66.7% |
| Neutral | 2 | 33.3% |
| Negative | 0 | 0% |

**Average Sentiment Score:** 0.121 (Slightly Positive)

### Trending Keywords (Velocity)

| Word | Increase |
|------|----------|
| hours | +2450% 🚀 |
| points | +1450% |
| hide | +1450% |
| brief | +1100% |
| anthony | +800% |

### Source Authority Ranking

| Source | Authority Score | Sentiment | Articles |
|--------|-----------------|-----------|----------|
| BBC | 0.95 ⭐⭐⭐⭐⭐ | 0.09 | 1 |
| TechCrunch | 0.90 ⭐⭐⭐⭐⭐ | 0.15 | 1 |
| WIRED | 0.88 ⭐⭐⭐⭐ | 0.10 | 2 |
| The Verge | 0.85 ⭐⭐⭐⭐ | 0.14 | 1 |
| Hacker News | 0.75 ⭐⭐⭐ | 0.15 | 1 |

---

## How to Run Locally

Follow these steps to run the project on your local machine or Google Colab:

### Option 1: Google Colab (Recommended – No Installation)

1. **Open Google Colab**  
   [https://colab.research.google.com/](https://colab.research.google.com/)

2. **Upload the notebook**  
   - File → Upload Notebook → Select `Web_Crawler.ipynb`

3. **Run all cells**  
   - Runtime → Run all

4. **Choose URL input option**  
   - `1` – Enter URLs manually
   - `2` – Paste multiple URLs
   - `3` – Deep crawl a website
   - `4` – Use default news sources
   - `5` – Upload URLs file

5. **View results**  
   - Check output in Colab
   - Open generated HTML dashboard

### Option 2: Local Machine

```bash
# Clone the repository
git clone https://github.com/YourUsername/distributed-web-crawler-dask.git
cd distributed-web-crawler-dask

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Web_Crawler.ipynb
