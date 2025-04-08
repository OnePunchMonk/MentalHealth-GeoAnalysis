# MentalHealth-GeoAnalysis

**MentalHealth-GeoAnalysis** is a Python-based project that fetches top posts from selected subreddits using PRAW (Python Reddit API Wrapper) and analyzes the data to explore mental health trends with a geographic perspective. The project includes tools for data cleaning, analysis, and visualization, culminating in an interactive map (HTML) that highlights crisis posts.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Setup](#setup)

- [Results](#View-Results)

## Features

- **Reddit Scraper:** Uses PRAW to fetch top posts from specified mental health-related subreddits.
- **API Authentication:** Leverages environment variables for secure API key management.
- **Data Cleaning & Analysis:** Processes Reddit posts to prepare data for analysis.
- **Geo Visualization:** Generates an interactive map (`reddit_crisis_map_final.html`) to visualize geographic trends in mental health-related posts.
- **PII Removal:** Includes a notebook (`PII_Removal.ipynb`) for user anonymization using Microsoft Presidio.
- **Jupyter Notebook:** Includes a notebook (`CodeFile.ipynb`) for exploratory analysis and reproducibility.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/OnePunchMonk/MentalHealth-GeoAnalysis.git
   cd MentalHealth-GeoAnalysis
   pip install praw pandas geopandas jupyter
## Setup

Add your Reddit API credentials in .env file.


## View Results:

The processed data is saved as cleaned_reddit_posts_final.csv and cleaned_reddit_posts_final.json.

Open reddit_crisis_map_final.html in a web browser to explore the interactive map visualizing mental health-related posts geographically.
   

