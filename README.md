🎬 Netflix Shows Analysis Using Pandas


📊 Overview
This project uses Pandas to explore and analyze a dataset of Netflix Movies and TV Shows. Through cleaning, filtering, and summarization, 
we uncover trends in content production, preferred genres, and geographical distribution of Netflix content. The analysis is supported by 
optional visualizations using Matplotlib and Seaborn.


🗃️ Dataset
Source: Netflix Movies and TV Shows - Kaggle
File: netflix_titles.csv
Attributes:
type: Movie or TV Show
title, director, cast: Content details
country: Country of origin
date_added: Date the content was added to Netflix
release_year: Year of original release
rating: Age suitability rating
duration: Duration (in minutes or seasons)
listed_in: Genre(s)
description: Brief summary of the content


🎯 Objectives
Clean and preprocess the dataset
Explore missing values and remove or impute them
Analyze content distribution by type, country, and release year
Extract and rank most common genres and directors
Visualize the trend of content addition over the years


🛠️ Tools & Libraries
Python 3.x
Pandas (main library for data analysis)
Matplotlib and Seaborn (for optional visualizations)


📈 Key Insights
Netflix has more Movies than TV Shows
Most content comes from United States, India, and United Kingdom
A significant increase in content was seen post-2016
Genres like Dramas, Comedies, and Documentaries dominate
Directors with the highest content count include Raúl Campos and Jan Suter


🔧 Features Demonstrated
Data cleaning: handling null values and formatting dates
Filtering and grouping using groupby(), value_counts(), isin()
Working with text columns using .str operations
Time-based analysis using pd.to_datetime()
Data aggregation and summary statistics
Exploratory Data Analysis (EDA) approach using Pandas


🚀 Getting Started
Clone the repository or download the .ipynb file
Install dependencies:
pip install pandas matplotlib seaborn
Run the notebook using Jupyter or Google Colab


📁 Folder Structure
netflix-pandas-analysis/
├── netflix_titles.csv
├── netflix_eda.ipynb
├── README.md


📝 License
This project is released under the MIT License and is free to use.
