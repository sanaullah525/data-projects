# data-projects
This repository contains end to end data analysis projects from the Google Data Analytics Capstone and independent work. Focused on large dataset handling, memory efficient processing, SQL integration, and extracting actionable business insights using Python, Pandas, SQLite, and Excel.

# Projects Overview

My first end-to-end data analysis project from the Google Data Analytics Capstone: Case Study 1 – How does a bike-share navigate speedy success?. The project focuses on memory-efficient processing of large datasets, SQL integration, and extracting actionable business insights.

# Dataset

Source: Public dataset from Google Data Analytics Certificate

Size: ~1.2 GB, 5.55 million rows, 14 columns

Issues: Null values, missing/extra columns, messy timestamps, incorrect datatypes

Technical Implementation

Memory Efficiency: Chunked CSV loading with pandas, reducing RAM usage from 27 GB to 4.1 GB

Database: SQLite used for aggregation and performance, pandas for wrangling and visualization

Optimizations: Removed loops, optimized dtypes, separated raw vs processed data

# Analysis

Three main questions:

Usage Differences: Members vs casual riders – total rides, avg duration, peak hours, ride type preference

Conversion Potential: Casual riders may save money by switching to annual memberships

Marketing Strategy: Promote cost-saving and weekend-focused campaigns via digital media

Visualizations: Pie charts, bar charts, line charts using matplotlib, seaborn, plotly

# Results & Skills

Insights inform marketing and membership strategy

Demonstrates data cleaning, memory-efficient processing, SQL integration, EDA, visualization, and actionable business insights

# Execution

Environment: Jupyter Notebook, Python 3.x

Libraries: numpy, pandas, matplotlib, seaborn, plotly, sqlite3, os

Structure: Raw data in Kaggle VM, processed data via SQLite, step-by-step analysis in notebook
