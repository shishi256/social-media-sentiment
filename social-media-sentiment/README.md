# Social Media Sentiment Analysis

## Project Overview

This project performs basic sentiment analysis on social media posts. The posts are cleaned and classified into three sentiment categories: positive, neutral, and negative.

The project uses Python and the VADER sentiment analysis tool to calculate the sentiment polarity of the posts.

## Dataset

**Dataset:** Twitter US Airline Sentiment Dataset

**Source:** Kaggle / CrowdFlower

**Dataset Access Date:** 19 September 2026

**Type:** Social media / Twitter-style posts

## Tools and Technologies

* Python
* JupyterLab
* Pandas
* NLTK
* VADER Sentiment Analysis
* Matplotlib
* WordCloud

## Methodology

The project was completed using the following steps:

1. Loaded the social media dataset using Pandas.
2. Checked the dataset and removed missing text values.
3. Preprocessed the text by converting it to lowercase and removing URLs, usernames, symbols, and extra spaces.
4. Used VADER to calculate sentiment scores.
5. Classified each post as positive, neutral, or negative.
6. Calculated the percentage of each sentiment class.
7. Created a sentiment distribution bar chart.
8. Generated separate word clouds for positive, neutral, and negative posts.
9. Prepared a short insight summary based on the results.

## Sentiment Results

| Sentiment | Percentage |
| --------- | ---------: |
| Positive  |     17.79% |
| Neutral   |     68.72% |
| Negative  |     13.50% |

The results show that neutral posts make up the majority of the dataset. Positive posts account for 17.79%, while negative posts account for 13.50%.

## Visualizations

The project includes:

* Sentiment distribution bar chart
* Positive sentiment word cloud
* Neutral sentiment word cloud
* Negative sentiment word cloud

## Repository Structure

```text
social-media-sentiment/
│
├── data/
│   └── tweets.csv
│
├── notebooks/
│   └── sentiment_analysis.ipynb
│
├── visuals/
│   ├── sentiment_distribution.png
│   ├── positive_wordcloud.png
│   ├── neutral_wordcloud.png
│   └── negative_wordcloud.png
│
├── README.md
└── insight_summary.txt
```

## Conclusion

The sentiment analysis provides a simple overview of the tone of the social media posts. The majority of posts are neutral, followed by positive and negative posts. The visualizations and word clouds help in understanding the overall sentiment and commonly used terms in each sentiment category.
