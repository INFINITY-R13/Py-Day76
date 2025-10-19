# Py-Day76: Google Play Store App Analytics

A comprehensive data analysis project exploring the Android app market using Python, pandas, and Plotly for beautiful visualizations.

## Project Overview

This project analyzes thousands of apps from the Google Play Store to uncover insights about:
- App ratings and user reviews
- Category distribution and popularity
- Pricing strategies (Free vs Paid apps)
- App sizes and installation counts
- Content ratings and target audiences

## Dataset

The analysis uses the Google Play Store Apps dataset containing:
- **10,841 apps** with **12 attributes** each
- Data scraped by Lavanya Gupta in 2018
- Original source: [Kaggle - Google Play Store Apps](https://www.kaggle.com/lava18/google-play-store-apps)

### Dataset Columns:
- `App` - Application name
- `Category` - App category (e.g., SOCIAL, FAMILY, GAMES)
- `Rating` - User rating (1-5 stars)
- `Reviews` - Number of user reviews
- `Size_MBs` - App size in megabytes
- `Installs` - Number of installations
- `Type` - Free or Paid
- `Price` - App price (for paid apps)
- `Content_Rating` - Age rating (Everyone, Teen, etc.)
- `Genres` - Detailed genre classification
- `Last_Updated` - Last update date
- `Android_Ver` - Minimum Android version required

## Key Features

- **Data Cleaning**: Handles NaN values and duplicate entries
- **Exploratory Data Analysis**: Statistical summaries and data exploration
- **Interactive Visualizations**: Beautiful Plotly charts and graphs
- **Market Insights**: Analysis of app trends and patterns
- **Category Analysis**: Breakdown by app categories and genres

## Project Files

- `Google_Play_Store_App_Analytics.ipynb` - Main Jupyter notebook with complete analysis
- `Google_Play_Store_App_Analytics.py` - Converted Python script version
- `apps.csv` - Dataset containing 10,841 Google Play Store apps
- `README.md` - Project documentation

## Requirements

- Python 3.7+
- pandas
- plotly.express
- Jupyter Notebook

## Installation

Install required dependencies:

```bash
pip install pandas plotly jupyter
```

## Usage

### Method 1: Jupyter Notebook (Recommended)

1. **Start Jupyter Notebook:**
   ```bash
   python -m notebook
   ```

2. **Open the analysis:**
   - Navigate to `Google_Play_Store_App_Analytics.ipynb` in the Jupyter interface
   - Run all cells: Cell → Run All
   - Or run cells individually with Shift + Enter

### Method 2: Python Script

Run the converted Python script directly:

```bash
python Google_Play_Store_App_Analytics.py
```

### Method 3: JupyterLab

Alternative interface with more features:

```bash
python -m jupyterlab
```

## Data Quality Notes

The analysis includes data cleaning steps to handle:
- **1,474 apps** with missing ratings (NaN values)
- **476 duplicate entries** in the dataset
- Data type conversions and formatting issues

After cleaning, the analysis works with **9,367 clean app records**.

## Expected Output

When you run the analysis, you'll see:
- Dataset exploration and statistics
- Data cleaning process and results
- Interactive Plotly visualizations showing:
  - App category distributions
  - Rating patterns and trends
  - Free vs Paid app analysis
  - Installation count patterns
  - Content rating breakdowns
  - Size and performance metrics

## Learning Objectives

This project demonstrates:
- Data cleaning and preprocessing techniques
- Exploratory data analysis (EDA) best practices
- Creating interactive visualizations with Plotly
- Statistical analysis of real-world datasets
- Market research and business intelligence insights
