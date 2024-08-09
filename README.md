IMDb Movie Analysis
This project is an in-depth analysis of the top 1000 movies on IMDb. It aims to explore trends in ratings, runtime, votes, and earnings using various data analysis and visualization techniques. By examining these factors, we aim to uncover insights into what contributes to a movie's success.

Project Overview
The IMDb Movie Analysis project utilizes a comprehensive dataset of 1000 movies from IMDb, covering various attributes such as movie titles, release years, IMDb ratings, Metascore ratings, runtime, number of votes, and box office earnings. The analysis focuses on identifying patterns, correlations, and trends within this dataset to gain insights into the movie industry.

Key Activities
1. Data Collection and Preparation
Dataset Acquisition: We started by acquiring a dataset containing detailed information about the top 1000 IMDb movies.

Data Cleaning: We removed unnecessary columns, handled missing values, and performed data normalization to ensure consistent formatting, such as normalizing movie titles to identify duplicates and standardizing numeric data.

Data Enrichment: Using the TMDb API, we supplemented the dataset with additional movie details, such as genres and other relevant metadata. This step was crucial for providing context to the analysis.

2. Exploratory Data Analysis (EDA)
Descriptive Statistics: We explored basic statistics, such as mean, median, and distribution of key variables like IMDb ratings, Metascore, runtime, and gross earnings.

Duplicate Detection: We identified duplicate movies based on normalized titles and release years to maintain dataset integrity.

Missing Values Analysis: We examined columns for missing data, identified patterns, and applied strategies to handle missing values, such as filling missing Metascore and Gross values with the mean and median, respectively.

3. Data Visualization
Histograms and KDE Plots: Visualized the distribution of IMDb ratings, Metascore, runtime, and gross earnings to understand the overall data trends.

Scatter Plots: Explored relationships between IMDb ratings and number of votes, runtime vs. Metascore, and other key variables to uncover potential correlations.

Bar Charts: Highlighted the top-rated movies, movies with the highest earnings, and the most popular genres.

Box Plots: Used to identify outliers in ratings and earnings data.

Heatmaps: Displayed correlation matrices to illustrate the relationships between numerical variables.

4. Trend Analysis
Yearly Trends: Analyzed trends over the years in IMDb ratings, Metascore, and box office earnings to identify patterns and shifts in audience preferences and industry trends.

Decade Analysis: Created a 'decade' column to study trends and patterns within specific decades.

5. Hidden Gems Identification
Underrated Movies: Identified "hidden gems" by sorting movies with high ratings but low popularity (fewer votes), offering insights into films that deserve more attention.
