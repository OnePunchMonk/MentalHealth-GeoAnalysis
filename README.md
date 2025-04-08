# 🧠 MentalHealth-GeoAnalysis

**MentalHealth-GeoAnalysis** is a Python-based project that fetches and analyzes top Reddit posts from selected mental health-related subreddits. It aims to uncover geographic trends in mental health discussions through data cleaning, analysis, and interactive visualizations.

---

## 📌 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Setup](#setup)
- [Usage & Results](#usage--results)
- [Notebooks Included](#notebooks-included)

---

## 🚀 Features

- **🔍 Reddit Scraper:**  
  Uses **PRAW (Python Reddit API Wrapper)** to fetch top posts from specified mental health-focused subreddits.

- **🔐 Secure API Access:**  
  Authenticates using environment variables to protect your Reddit API credentials.

- **🧹 Data Cleaning & Analysis:**  
  Cleans and processes Reddit data for accurate analysis, removing noise and irrelevant content.

- **🗺️ Geo Visualization:**  
  Generates an **interactive HTML map** (`reddit_crisis_map_final.html`) highlighting posts with geographical context to visualize mental health crisis trends.

- **🕵️ PII Removal:**  
  Utilizes **Microsoft Presidio** in a Jupyter notebook (`PII_Removal.ipynb`) to anonymize personal information.

- **📊 Reproducible Analysis:**  
  A Jupyter notebook (`CodeFile.ipynb`) for exploratory analysis and visual storytelling.

---

## 🛠️ Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/OnePunchMonk/MentalHealth-GeoAnalysis.git
cd MentalHealth-GeoAnalysis
pip install praw pandas geopandas jupyter
```
## 🧰 Technologies Used

| Tool / Library      | Purpose                                 |
|---------------------|------------------------------------------|
| Python              | Core programming language                |
| PRAW                | Reddit API integration                   |
| Pandas              | Data manipulation and analysis           |
| GeoPandas           | Geospatial data processing               |
| Jupyter Notebook    | Interactive analysis and documentation   |
| Microsoft Presidio  | PII detection and anonymization          |
| HTML/Leaflet.js     | Interactive geographic visualization     |
---

## ⚙️ Setup

1. **Reddit API Authentication:**

   - Create a `.env` file in the project root directory.
   - Add your Reddit API credentials:
     ```env
     CLIENT_ID=your_client_id
     CLIENT_SECRET=your_client_secret
     USER_AGENT=your_user_agent
     ```

2. **Run the data collection and analysis scripts as needed (see notebooks).**

---

## 📈 Usage & Results

- Processed datasets are saved as:
  - `cleaned_reddit_posts_final.csv`
  - `cleaned_reddit_posts_final.json`

- To explore the **interactive map**, open:
  ```
  reddit_crisis_map_final.html
  ```
  in your browser to see a geographical visualization of Reddit posts related to mental health topics.

---

## 📒 Notebooks Included

- `CodeFile.ipynb`: Core data exploration and visualization workflow.
- `PII_Removal.ipynb`: Uses Microsoft Presidio for identifying and removing personally identifiable information (PII).

