# Amazon Product Reviews: NLP Sentiment & Emotion Analysis

## Project Overview
This project was completed as **Task 4 (Sentiment Analysis)** for the **CodeAlpha Data Analytics Internship**. Using Natural Language Processing (NLP) lexicons (**VADER** and **TextBlob**), this analysis classifies **1,597 Amazon product reviews** into Positive, Neutral, and Negative sentiments, detects underlying customer emotions, and extracts actionable insights for marketing and product development.

## Key Analytical Findings
* **Sentiment Distribution:** **88.35%** (`1,411`) of customer reviews are **Positive**, **8.58%** (`137`) are **Negative**, and **3.07%** (`49`) are **Neutral**.
* **Emotion & Tone Detection:** **1,251 reviews** express *Joy / High Satisfaction*, while **160 reviews** reflect *Mild Approval / Trust*.
* **Star Rating Correlation:** VADER compound scores align strongly with customer ratings—rising steadily from **-0.039** (1-star reviews) to **+0.779** (5-star reviews).
* **Marketing & Product Insights:** Positive feedback highlights **sound quality**, **headphones**, and **Prime** value, whereas negative feedback frequently compares older **versions** against competitors like the **iPad**.

## Repository Contents
* `7817_1.csv` — Raw Amazon product reviews dataset.
* `amazon_reviews_with_sentiment.csv` — Cleaned dataset enriched with VADER compound scores, TextBlob polarity, sentiment labels, and detected emotion tones.
* `amazon_sentiment_analysis.ipynb` — Complete Python NLP notebook with code, statistics, and charts.
* `sentiment_chart1_distribution.png` — Overall Positive, Neutral, and Negative review breakdown.
* `sentiment_chart2_emotions.png` — Customer emotion and tone classification chart.
* `sentiment_chart3_rating_vs_sentiment.png` — Boxplot comparing NLP sentiment scores across 1–5 star ratings.
