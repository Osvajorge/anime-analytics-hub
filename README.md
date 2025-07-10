# Anime Analytics Hub 🎌📊

A comprehensive data analysis project exploring trends, ratings, and patterns in anime production using a dataset of 2,500+ anime titles.

## 📋 Project Overview

This project analyzes various aspects of anime including viewer ratings, production trends, studio performance, and genre popularity to uncover insights about what makes anime successful.

## 🗂️ Project Structure

anime-analytics-hub/
│
├── data/
│   ├── raw/
│   │   └── New_Anime_list.csv          # Original dataset
│   └── processed/
│       ├── anime_clean.csv             # Cleaned dataset
│       ├── anime_movies.csv            # Movies subset
│       └── anime_series.csv            # Series subset
│
├── notebooks/
│   ├── 01_data_exploration.ipynb      # Initial data exploration
│   ├── 02_data_cleaning.ipynb         # Data cleaning process
│   └── 03_eda.ipynb                   # Exploratory data analysis (WIP)
│
├── src/                                # Python scripts (future)
├── reports/                            # Analysis reports (future)
├── requirements.txt                    # Project dependencies
└── README.md                           # Project documentation

## 📊 Dataset Information

- **Source**: New_Anime_list.csv
- **Size**: 2,500 anime titles
- **Features**: 
  - `title`: Anime name
  - `genre`: Categories (can be multiple)
  - `studio`: Production studio
  - `number_of_episodes`: Episode count
  - `release_date`: Release date
  - `content_type`: Type (TV, Movie, OVA, etc.)
  - `viewer_reviews`: Rating score
  - `source`: Data source

## 🔍 Key Findings (So Far)

### Data Quality
- **33 anime with 0 episodes** (mostly unreleased future anime)
- **17 missing dates** 
- **34 anime with 0 reviews**
- Successfully cleaned and categorized into movies (448) and series (2,009)

### Initial Observations
- Average rating: 71.93/100
- Rating range: 0-91
- Most common type: TV shows (1,755)
- Episode range: 0-1,000

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries**:
  - pandas & numpy: Data manipulation
  - matplotlib & seaborn: Visualization
  - jupyter: Interactive development
  - plotly: Interactive visualizations (planned)

## 🚀 Getting Started

1. Clone the repository
```bash
git clone https://github.com/yourusername/anime-analytics-hub.git
cd anime-analytics-hub
```

2. Create virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

📈 Analysis Progress

 Data Exploration
 Data Cleaning
 Exploratory Data Analysis (in progress)
 Statistical Analysis
 Machine Learning Models
 Final Report

🎯 Project Goals

Identify factors that correlate with higher anime ratings
Analyze production trends over time
Discover which studios consistently produce quality content
Understand the relationship between episode count and viewer satisfaction
Explore genre combinations and their impact on success

📝 Future Work

Interactive dashboard with Plotly/Dash
Predictive model for anime ratings
Genre recommendation system
Time series analysis of anime trends

## 👤 Author

- Your Name
- GitHub: [@osvaajorge](https://github.com/osvajorge)

