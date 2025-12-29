# google-play-store-analysis
Feature Engineering and EDA on Google Play Store Dataset - Atıl Samancıoğlu Data Science Course

##  Project Overview
This project is part of Atıl Samancıoğlu's Data Science and Machine Learning course. 
We perform comprehensive Feature Engineering and Exploratory Data Analysis (EDA) on the Google Play Store Apps dataset.

##  Objectives
- Data Cleaning and Preprocessing
- Feature Engineering
- Exploratory Data Analysis
- Preparation for Machine Learning Models

##  Dataset
- **Source**: Kaggle - Google Play Store Apps
- **File**: `17-googleplaystore.csv`
- **Rows**: 10,841 (before cleaning)
- **Columns**: 13 (before feature engineering)

##  Technologies Used
- Python 3.9+
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn

##  Key Steps

### 1. Data Loading and Initial Exploration
- Loading dataset with pandas
- Checking basic info, shape, and missing values

### 2. Data Cleaning
- **Reviews Column**: Fixed non-numeric values, converted to int
- **Size Column**: Converted MB/kB to KB, handled 'Varies with device'
- **Installs Column**: Removed '+' and ',', converted to int
- **Price Column**: Removed '$', converted to float
- **Date Processing**: Converted 'Last Updated' to datetime

### 3. Feature Engineering
- Extracted Day, Month, Year from dates
- Identified numeric and categorical features
- Removed duplicate apps

### 4. EDA Highlights
- Missing value analysis
- Statistical summaries
- Data type conversions
- Dataset shape after cleaning: 9,659 × 16

##  How to Run

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/google-playstore-eda.git
cd google-playstore-eda
