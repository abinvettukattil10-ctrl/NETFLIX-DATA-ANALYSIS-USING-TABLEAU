# Netflix Data Analysis Dashboard 📺

## Overview
This project presents an interactive **Netflix Data Analysis Dashboard** built using **Tableau**. The dashboard provides insights into Netflix's content library, including movies and TV shows, helping users explore trends in content distribution, genres, ratings, countries, and release years.

## Project Objectives
- Analyze Netflix's catalog of Movies and TV Shows.
- Identify trends in content addition over time.
- Explore content distribution by country.
- Examine genre popularity and content ratings.
- Visualize key metrics through interactive dashboards.

## Dataset
The dataset contains information about Netflix titles, including:

| Column Name | Description |
|------------|-------------|
| show_id | Unique identifier for each title |
| type | Movie or TV Show |
| title | Name of the content |
| director | Director of the title |
| cast | Main cast members |
| country | Country of production |
| date_added | Date added to Netflix |
| release_year | Original release year |
| rating | Content rating |
| duration | Duration of movie or number of seasons |
| listed_in | Genre/category |
| description | Brief summary |

### Dataset Source
Netflix Titles Dataset (commonly available from Kaggle and other public data repositories).

---

## Tools & Technologies
- **Tableau Desktop**
- Microsoft Excel / CSV
- Data Cleaning & Transformation
- Interactive Dashboard Design

---

## Data Preparation
Before creating visualizations:

1. Imported the dataset into Tableau.
2. Cleaned null and missing values.
3. Converted `date_added` to Date format.
4. Created calculated fields for:
   - Content Age
   - Year Added
   - Month Added
5. Split and analyzed multi-value genre fields.

---

## Dashboard Features

### 1. Content Distribution
- Total Movies vs TV Shows
- Percentage share of each content type

### 2. Content by Country
- World map visualization
- Top contributing countries

### 3. Content Growth Over Time
- Titles added by year
- Trend analysis of Netflix expansion

### 4. Ratings Analysis
- Distribution of content ratings
- Most common audience categories

### 5. Genre Analysis
- Popular genres
- Genre-wise content count

### 6. Release Year Analysis
- Content released across different decades
- Peak production years

---

## Key Insights
- Movies make up the majority of Netflix's content library.
- The United States contributes the highest number of titles.
- Significant growth in content additions occurred after 2015.
- Drama and International Movies are among the most popular genres.
- TV-MA is one of the most frequently occurring content ratings.

---

## Dashboard Preview

<img width="900" alt="Netflix Tableau Dashboard" src="dashboard_screenshot.png">

> Replace the image above with an actual screenshot of your Tableau dashboard.

---

## Project Structure
