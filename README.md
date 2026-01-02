# Social Media Sentiment Analysis & Visualization

This project analyzes and visualizes sentiment patterns in social media data
to understand public opinion toward specific topics or brands.

## Dataset
A small sample dataset resembling social media posts (e.g., Twitter/X).

### Files
- social_media_sentiment_sample.csv

### Columns
- post_id: Unique post ID
- text: Social media post content
- topic: Brand or topic mentioned
- sentiment: positive / negative / neutral

## Project Structure
```
.
├── data/
│   └── social_media_sentiment_sample.csv
├── sentiment_analysis_visualization.ipynb
└── README.md
```

## Requirements
pip install pandas matplotlib seaborn nltk wordcloud

## Tasks Covered
- Load & explore data
- Sentiment distribution analysis
- Topic-wise sentiment visualization
- Word cloud generation
