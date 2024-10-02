# Coronavirus Tweet Sentiment Analysis

## Overview
This project conducts sentiment analysis on tweets related to the coronavirus pandemic to gauge public opinion. Using natural language processing (NLP) techniques, the model classifies tweets into positive, negative, or neutral sentiments. The results provide valuable insights into the public's emotional response to COVID-19 throughout different phases of the pandemic.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used
- **Python**: Core programming language.
- **Pandas**: For data manipulation and analysis.
- **NLTK (Natural Language Toolkit)**: For text preprocessing and tokenization.
- **Scikit-learn**: For sentiment classification and model building.
- **Tweepy**: For accessing Twitter’s API to collect tweet data.
- **Matplotlib & Seaborn**: For data visualization of sentiment trends.
  
## Dataset
The dataset is composed of tweets collected via Twitter’s API, containing keywords related to the coronavirus pandemic (e.g., "COVID-19", "coronavirus", "pandemic"). Key fields in the dataset include:
- **Tweet text**: The actual content of the tweet.
- **Timestamp**: When the tweet was posted.
- **Username**: The user who posted the tweet (optional, if applicable).
  
### Data Collection
Tweets were gathered using the Twitter API, filtered by relevant hashtags and keywords during the pandemic period. The dataset was then cleaned and processed for sentiment analysis.

## Methodology
1. **Data Collection**: Collected live tweets related to the coronavirus using Tweepy and Twitter API.
2. **Data Preprocessing**: Applied text cleaning techniques, such as:
    - Removing URLs, mentions, hashtags, and special characters.
    - Lowercasing all text.
    - Tokenization and stop-word removal.
3. **Sentiment Analysis**: 
    - Classified sentiments as **Positive**, **Negative**, or **Neutral**.
    - Used a pre-trained model or Scikit-learn’s classification algorithms (e.g., Logistic Regression, Random Forest).
4. **Data Visualization**: 
    - Visualized sentiment distribution over time.
    - Created heatmaps and line charts to display public sentiment during key moments of the pandemic.

## Results
The sentiment analysis revealed the following:
- **Overall Sentiment**: The majority of tweets expressed negative sentiments, reflecting public anxiety and uncertainty during the pandemic.
- **Sentiment Trends**: Visualized spikes in positive and negative sentiments corresponding to significant events, such as vaccine rollouts or major case surges.

Sample visualizations:
- **Sentiment Distribution**: Showed the proportion of positive, negative, and neutral tweets.
- **Time-series Analysis**: Mapped changes in sentiment over time to notable events during the pandemic.
