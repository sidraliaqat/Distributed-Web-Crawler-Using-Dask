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
 
 **Dashboard Main View**
 
  ![Dashboard Main](images/dashboard_main.png) 

**Top Keywords Analysis**

![Top Keywords](images/top_keywords.png) 

**Performance Comparison**

![Performance](images/performance_chart.png)

**Sentiment Distribution**

![Sentiment](images/sentiment_chart.png)

**Distributed Crawl Output**

![Crawl Output](images/imagescrawl_output01.png)
![Crawl Output](images/imagescrawl_output02.png)

**Word Frequency Results**

![Word Frequency](images/word_frequency_output.png.png) 

**Dashboard Statistics**

![Dashboard Stats](images/dashboard_stats.png.png) 


---


## How to Run

Follow these steps to run the project:

### Google Colab 

1. **Open Google Colab**  
   [https://colab.research.google.com/](https://colab.research.google.com/)

2. **Upload the notebook**  
   - File → Upload Notebook → Select `Web_Crawler_FINAL.ipynb`

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

