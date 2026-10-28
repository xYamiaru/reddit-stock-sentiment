# Reddit Stock Sentiment Analyzer

A private, non-commercial Python application for analyzing stock market discussions and investment sentiment on Reddit.

## Project Overview

This project aims to analyze publicly available posts and comments from r/wallstreetbetsGER using the official Reddit Data API.

The primary goal is to identify frequently discussed publicly traded companies, evaluate community sentiment, and detect emerging investment trends.

The application is intended exclusively for personal investment research and educational purposes.

**Project status:** Planning phase. Reddit API access has not yet been granted.

## Planned Features

### 1. Reddit Data Collection

* Retrieve publicly available posts and comments from r/wallstreetbetsGER.
* Monitor selected discussion threads for new comments.
* Periodically collect new discussions using the official Reddit API.
* Respect Reddit API rate limits.

### 2. Stock Mention Detection

* Identify company names and stock ticker symbols.
* Count how frequently individual companies are mentioned.
* Detect unusual increases in stock discussion activity.

### 3. Sentiment Analysis

* Classify discussions as positive, negative, or neutral.
* Identify bullish and bearish sentiment toward individual stocks.
* Analyze changes in sentiment over time.
* Account for potential sarcasm and misleading statements where possible.

### 4. Investment Trend Analysis

* Generate rankings of frequently mentioned stocks.
* Highlight companies experiencing increasing positive attention.
* Compare discussion trends across different time periods.
* Provide insights for further independent investment research.

### 5. Local Dashboard

* Display stock mention statistics.
* Visualize community sentiment.
* Show historical discussion trends.
* Present summarized findings in a private dashboard.

## Technical Architecture

Planned technologies:

* **Python:** Main application language.
* **Reddit Data API:** Authorized access to Reddit discussions.
* **PRAW:** Python Reddit API Wrapper.
* **SQLite:** Local storage of permitted analytical data.
* **Sentiment Analysis:** Local text processing using existing models or rule-based methods.
* **Dashboard:** Local web interface for visualization.

No Reddit data will be used to train machine learning models.

## Reddit API Usage

The application will operate exclusively in read-only mode.

It will not:

* Publish posts or comments.
* Send private messages.
* Vote on Reddit content.
* Interact with Reddit users.
* Redistribute collected Reddit content.
* Provide a public or commercial API service.

API requests will be limited to the data necessary for personal analysis.

The application will comply with Reddit's API usage policies, rate limits, data deletion requirements, and applicable privacy regulations.

## Why the Reddit Data API Instead of Devvit?

The application is designed as an independent Python-based analysis tool running locally.

It requires access to publicly available Reddit discussions for external statistical processing, sentiment analysis, and local visualization.

The project does not require integration with Reddit's user interface or community moderation functionality.

## Intended Use

This project is strictly personal and non-commercial.

The generated insights are intended to support independent investment research and do not constitute financial advice.

The application will not execute trades automatically.

## Development Status

The project is currently in its initial planning stage.

Implementation will begin after obtaining the necessary Reddit API authorization.
