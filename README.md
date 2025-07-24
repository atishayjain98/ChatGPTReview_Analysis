# Sentiment & Text Analysis on ChatGPT Reviews Dataset

## Overview
This project performs **sentiment analysis** and **text analysis** on a dataset containing customer reviews.  
The workflow includes data preparation, sentiment scoring, keyword extraction, and visualizations for actionable insights.

---

## Project Features
1. **Data Preparation**
   - Load and inspect dataset.
   - Standardize column names and handle missing values.
   - Convert date formats and ensure correct data types.

2. **Sentiment Analysis**
   - Calculate sentiment polarity and subjectivity using **TextBlob**.
   - Classify reviews into **Positive, Neutral, or Negative**.
   - Visualize sentiment distribution and compare it with user ratings.

3. **Text Analysis**
   - Filter positive reviews for keyword extraction.
   - Identify frequently mentioned terms using **word clouds** and **n-gram (bigrams & trigrams) frequency analysis**.

4. **Data Visualization**
   - Use **Matplotlib** and **Seaborn** for:
     - Sentiment trends over time.
     - Subjectivity and polarity distributions.
     - Keyword frequency plots.
     - Word cloud visualization of positive reviews.

---

## Dataset
- **Columns**:
  - `Review Id` (string)
  - `Review` (text)
  - `Ratings` (integer)
  - `Review Date` (date)

- **Size**: ~196,000 records (sample from provided dataset)

---

## Tech Stack
- **Python Libraries**:
  - pandas, numpy – data manipulation
  - matplotlib, seaborn – visualization
  - textblob – sentiment analysis
  - wordcloud – word cloud generation
  - nltk – n-gram analysis
