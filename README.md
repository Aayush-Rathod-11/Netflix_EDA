# Netflix_EDA


## Netflix Movies and TV Shows EDA Project

### Project Overview
This project analyzes the Netflix Movies and TV Shows dataset using Python. The goal is to clean the data, perform exploratory data analysis, create visualizations, and generate useful business insights from Netflix content trends.

This project was completed as part of the AI & Machine Learning Internship — Project 01: Exploratory Data Analysis & Insights Report.

### Dataset
Dataset used: Netflix Movies & TV Shows Dataset
Source: Kaggle
Dataset link: https://www.kaggle.com/datasets/shivamb/netflix-shows

The dataset contains information about Netflix titles including:

* Title
* Type: Movie or TV Show
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

### Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* GitHub

### Project Workflow

1. Loaded and inspected the dataset
2. Checked shape, data types, missing values, and duplicates
3. Cleaned missing values (director, country, rating, duration) and fixed date columns
4. Created new columns such as `year_added` and `month_added`
5. Performed exploratory data analysis
6. Created visualizations
7. Generated final business insights

### EDA Questions Answered

1. What is the distribution of content types (Movies vs TV Shows)?
2. Which countries produce the most Netflix content?
3. Which month sees the most content additions?
4. In which years did Netflix add the most content?
5. Which year has the highest number of releases?

### Visualizations Created

The project includes the following visualizations:

1. Bar chart: Movies vs TV Shows
2. Line chart: Netflix content release trend over years
3. Histogram: Distribution of release years
4. Scatter plot: Release year vs movie duration
5. Pie chart: Percentage distribution of content type
6. Heatmap: Correlation between release year and movie duration
7. Horizontal bar chart: Top 10 countries by content count
8. Bar chart: Content ratings distribution

### Key Insights

1. Netflix's catalog is movie-dominated — Movies make up 69.7% of the library (6,128 titles) versus 30.3% TV Shows (2,666 titles), nearly a 2:1 ratio.
2. The United States and India lead content production by a wide margin — the US contributes 3,681 titles, over 3.5x more than India (1,046), followed by the UK (805) and Canada (445).
3. Netflix's library skews heavily toward recent content — most titles cluster after 2010, with 2018 (1,146 titles), 2019 (1,030), and 2017 (1,031) being the top release years.
4. Movie durations are consistent — the scatter plot of release year vs. duration reveals that most movies fall within a stable duration range (90–120 minutes). This suggests Netflix adheres to industry norms for viewer engagement.
5. Correlations among numeric features — the heatmap shows moderate correlations between release year and other numeric attributes. While not strongly predictive, these relationships can guide further modeling or recommendation systems.

### Business Recommendations

*	Continue investing in movie content.
*	Expand content diversity across countries.
*	Increase focus on popular genres.
*	Maintain content growth strategies.
*	Improve audience engagement through strategic releases.


### Most Surprising Finding

The most surprising finding was that movie durations have remained remarkably consistent across decades, with most titles clustering in the 90–120 minute range regardless of release year. Despite major shifts in content volume and streaming consumption habits, the standard "feature film" runtime has stayed largely unchanged.

### Conclusion

This analysis of the Netflix dataset revealed that Movies dominate the platform's catalog at nearly 70% of all titles, with the United States and India serving as the two largest content-producing countries. The data shows Netflix's library skews heavily toward recent releases, with 2017–2019 representing the peak years for content release. Movie durations have remained consistent over time, with most films falling in the 90–120 minute range, reflecting established industry norms. The heatmap of numeric features showed moderate correlations between release year and duration, indicating these relationships could support further modeling or recommendation system development. Overall, these insights highlight how Netflix's content strategy has evolved over time and could inform decisions around regional content investment, release timing, and catalog composition.

### How to Run

Open the notebook directly in Google Colab:
[Open in Colab](https://colab.research.google.com/drive/1OnZOjU3YaaeAiPQSzJd6mK7smhVRvl-P?usp=sharing)

Or clone this repo and run locally with Jupyter:
```bash
git clone https://github.com/Aayush-Rathod-11/Netflix_EDA.git
```

### Author

Aayush Rathod — Pluto Academy AI & ML Internship 2026
