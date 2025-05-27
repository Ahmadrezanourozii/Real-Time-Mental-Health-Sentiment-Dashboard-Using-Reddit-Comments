# Real-Time-Mental-Health-Sentiment-Dashboard-Using-Reddit-Comments ++ Power BI

mental-health-sentiment-powerbi/
│
├── data/
│   └── sentiment_data.csv           # Final dataset to be used in Power BI
│
├── reddit_scraper.py                # Collects comments from Reddit
├── sentiment_analysis.py           # Cleans & analyzes sentiment
├── pipeline.py                      # End-to-end automation
├── README.md                        # Project overview
└── requirements.txt                 # Python dependencies



This project collects Reddit comments from mental health subreddits, analyzes sentiment using Python NLP tools, and visualizes real-time insights in Power BI.

## Features

- Real-time sentiment scraping from Reddit
- Sentiment analysis using VADER
- Power BI dashboard with:
  - Time trends
  - Sentiment distribution
  - Topic-wise analysis

## How to Run

1. Add your Reddit API keys in `reddit_scraper.py`
2. Run the pipeline:

```bash
python pipeline.py
