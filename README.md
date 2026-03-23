# Netflix_case_study-using-Python

Project Overview

This project analyzes Netflix’s content dataset to understand patterns in movies and TV shows available on the platform. The analysis focuses on identifying trends related to content types, release patterns, ratings, genres, and geographic distribution.
The goal of this case study is to perform data cleaning, exploratory data analysis (EDA), and derive business insights that could help Netflix make informed decisions about content production and global expansion.
The entire analysis was conducted using Python with libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

Business Problem:

Netflix wants to leverage its content data to identify trends that can guide future content production and market expansion strategies.
The key objective is to answer:
How can Netflix use its existing content data to identify patterns and determine what type of shows or movies should be produced in different markets?

Dataset Information:

The dataset contains information about Netflix titles including:

Title,
Type (Movie / TV Show),
Director,
Cast,
Country,
Date Added,
Release Year,
Rating,
Duration,
Genre (Listed In),
Description

Project Workflow:
1. Data Cleaning & Preprocessing

The first step involved preparing the dataset for analysis.
Key steps included:
Checking dataset structure and column types,
Handling missing values,
Converting date columns into proper datetime format,
Splitting multi-value columns such as:
Cast,
Director,
Country,
Genres,
Removing duplicates and inconsistent records

2. Exploratory Data Analysis (EDA)

Both non-graphical and visual analysis techniques were used to understand the dataset.

Non-Graphical Analysis,
Summary statistics,
Unique value analysis,
Frequency counts,
Visual Analysis,
Univariate Analysis,

Distribution analysis of individual variables using:
Histograms,
Count plots,
Box plots,
Bivariate Analysis,

Relationships between variables were explored, including:
Content type vs release year,
Country vs number of titles,
Ratings distribution by content type,
Genre popularity trends

Project Outcome:

This project demonstrates how exploratory data analysis can be used to derive meaningful insights from real-world datasets. The findings highlight content trends that can support strategic decisions for streaming platforms like Netflix.
Several columns such as director, cast, and country contain multiple values, which required preprocessing and restructuring before performing analysis.
