# Netflix Content Trends Analysis — EDA

Exploratory Data Analysis on 8,000+ Netflix titles using Python.

## Overview
This project analyses Netflix's content library to uncover trends in Movies vs TV Shows, regional content distribution, and the impact of COVID-19 on global release cycles.

## Dataset
- Source: Kaggle — Netflix Movies and TV Shows
- Size: 8,807 titles, 12 columns
- Fields: Title, Type, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genre

## Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
- Git

## Project Structure
\```
netflix-data-analysis/
├── data/
│   └── netflix_titles.csv
├── netflix_analysis.ipynb
├── .gitignore
└── README.md
\```

## Analysis Sections
1. Data Cleaning & Overview
2. Content Trends Over Time
3. Regional Analysis — India vs USA
4. Genre Deep Dive
5. Business Conclusions & Insights

## Key Insights
- **Content Mix:** Netflix library is 69.7% Movies (6,126 titles) and 30.3% TV Shows (2,664 titles) — primarily a Movie platform, but TV Show share is steadily growing.
- **COVID-19 Impact:** Contrary to expectations, content addition increased ~4.5% during the pandemic (avg 808/year pre-COVID vs 844/year during COVID) — higher home viewership likely pushed Netflix to expand its library.
- **Regional Strategy:** India strongly favors Movies (92% of its 1,008 titles), while USA has a more balanced mix (73.7% Movies out of 3,202 titles).
- **Top Genre:** 'International Movies' dominates with 2,752 titles — reflecting Netflix's strong push toward global content.

## Author
Nikita Gupta  
github.com/nikitagupta05
