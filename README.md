# YouTube Comments Sentiment Analysis

Welcome to the YouTube Comments Sentiment Analysis repository, where we delve into the world of sentiment analysis by extracting and analyzing comments from YouTube videos. This project focuses on using the YouTube API to collect video statistics and comments, followed by thorough data cleaning utilizing Regular Expressions. The sentiment of the comments is then assessed using Vader Sentiment Analysis.

## Overview

This project centers around analyzing the sentiment expressed in YouTube comments related to various movies. By leveraging the YouTube API, we pull video statistics and comments, clean the extracted data, and apply sentiment analysis techniques to gain insights into viewers' sentiments.

## Data Collection and Cleaning

1. **Data Extraction**: The YouTube API is utilized to gather video statistics and comments from different movies.
2. **Data Cleaning**: Data-cleaning techniques, including Regular Expressions, are employed to clean and preprocess the comments for accurate sentiment analysis.

## Sentiment Analysis

Vader Sentiment Analysis, a powerful tool for sentiment analysis, is utilized to understand the sentiment polarity of the extracted comments. This analysis helps identify the prevailing sentiment among viewers for each movie.

## Usage

1. Install the required libraries using `pip install nltk pandas youtube-api`.
2. Acquire YouTube API credentials and set up access to retrieve video statistics and comments.
3. Execute the data extraction script to gather relevant video data.
4. Run the data-cleaning script to preprocess comments using Regular Expressions.
5. Apply the Vader Sentiment Analysis script to assess sentiment polarity.

## Libraries Used

- `nltk`: For natural language processing and sentiment analysis.
- `pandas`: For data manipulation and analysis.
- `youtube-api`: For interacting with the YouTube API.

## Contribution

Feel free to contribute to this repository by enhancing sentiment analysis techniques, optimizing data cleaning processes, or extending the analysis to different platforms or types of content. Submit pull requests to collaborate on improvements.

## Disclaimer

Keep in mind that sentiment analysis provides insights based on the data available and might not capture the full complexity of human sentiment. Interpret results with caution and explore further as needed.

Dive into the realm of sentiment analysis with YouTube comments and gain valuable insights into viewer sentiments for various movies!
