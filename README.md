# Netflix Content Analysis Dashboard (Power BI)

# Project Overview
This project analyzes Netflix’s Movies & TV Shows dataset to discover trends in content production, genres, and global distribution. The dataset was cleaned using Python and visualized through an interactive Power BI dashboard.

# Dataset
- **Source:** Kaggle – Netflix Movies and TV Shows Dataset
- **Columns:** show_id, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

# Data Cleaning Steps
1. **Handled Missing Values**
   - Director, cast, country, date_added, rating, duration filled using mode/most frequent values or with 'Unknown'.
2. **Removed Duplicates**
   - Based on `title` and `release_year`.
3. **Standardized Formats**
   - Country names, date formats, and rating categories cleaned for consistency.
4. **Kept Duration as Text**
   - Preserved original movie/TV season format for analysis.

# EDA (Exploratory Data Analysis)
- Movies vs TV Shows distribution
- Year-wise release trends
- Top contributing countries
- Genre (listed_in) popularity analysis
- Rating analysis

## 🖥 Dashboard Features
- **KPIs:** Total titles, total movies, total TV shows, top country, top genre
- **Charts:**
  - Release trend over years
  - Top countries by content count
  - Most frequent genres
- **Filters:** Content type, country, genre

## 📈 Insights
- Majority of Netflix content is **movies**.
- The USA and India are the top contributors.
- Peak content additions occurred between **2018–2020**.
- Stand-up comedy and documentaries have grown significantly in recent years.

## 🛠 Tools Used
- **Python** (Pandas, NumPy) – Data cleaning & preprocessing
- **Power BI** – Dashboard creation & visualization
- **Kaggle Dataset** – Data source
