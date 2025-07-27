![Icon](Images/Icon.jpg)

# Movie Studio Insights

# Overview

Our company has decided to start a new movie studio to join the growing trend of original video content. However, we don’t have much experience in the film industry. To help guide this new venture, we were asked to research what kinds of movies are currently doing well at the box office.

This project explores recent movie data to find out which film genres, release times, and other factors are most linked to success. We also look at things like budget, cast, and audience ratings to understand what makes a movie perform well.

The goal is to turn this information into simple, clear insights and recommendations that the studio can use to decide what types of films to produce. By using real data, we aim to give the new movie studio a strong and smart starting point.

# Business Understanding
The primary goal of this project is to help our company’s new movie studio make informed decisions about the types of films it should produce. With major studios seeing success through data-driven content strategies, we aim to explore recent box office trends to identify which film genres, themes, and production strategies are currently performing best. Our insights will translate directly into actionable recommendations—enabling the studio to compete effectively in the modern entertainment landscape.

# Data Understanding
To gain a comprehensive view of the market, we collected data from multiple reliable sources such as Box Office Mojo, The Numbers, IMDb, and Rotten Tomatoes. This dataset includes:

Movie titles, release dates, and genres
Domestic and international box office earnings
Production budgets
Audience ratings (IMDb, Rotten Tomatoes)
Cast, crew, and production companies
Movie runtime and MPAA ratings
This data will help us assess what types of films resonate most with audiences both commercially and critically.

# Data Preparation
Before analysis, the dataset underwent the following preprocessing steps:

Cleaning: Removed duplicate entries, fixed inconsistent genre labeling, and corrected invalid values (e.g., negative budgets).
Missing Value Handling: Filled or removed rows with missing revenue, budget, or genre information depending on their importance and availability.
Feature Engineering: Created new features such as ROI (Return on Investment), revenue-to-budget ratio, genre category simplification (e.g., "Action/Adventure", "Drama", "Animation").
Data Formatting: Ensured date and currency fields were standardized for time-series and comparative analysis.

# Data Analysis
Our exploratory analysis revealed key insights:

Genre Trends: Action, superhero, and animated films tend to dominate the box office. However, horror films often deliver high ROI due to low budgets.
Release Timing: Summer and holiday season releases significantly outperform others.
Budget vs. Revenue: While high-budget films usually earn more, several low-budget titles achieved remarkable profitability, particularly in horror and comedy.
Ratings Correlation: Audience scores (especially IMDb) are moderately correlated with box office success, but star power and franchise status tend to have a stronger impact.
Franchise Impact: Sequels and franchise films typically outperform standalone films, suggesting an appetite for continuity and established universes.

# Visualization
We utilized a variety of visual tools to present our findings clearly:

Bar charts to compare genre popularity and average revenue.
Box plots to show revenue spread by genre and ROI.
Time-series graphs to highlight seasonal trends in movie performance.
Scatter plots to examine the relationship between budget and revenue.
Heatmaps to identify correlations between variables such as budget, runtime, rating, and revenue.
These visuals help transform raw data into understandable insights for stakeholders.

# Conclusion
Based on the data we explored, we discovered several important patterns that can help guide the new movie studio’s decisions:

### 1) Certain Genres Make More Money
Action, superhero, animation, and horror films are top performers. Horror movies in particular offer high profits even with small budgets, making them a smart choice for a new studio with limited risk.
### 2) Timing Matters
Movies released during peak seasons—like summer and holidays—tend to earn much more. Choosing the right release time can significantly boost a movie’s success.
### 3) Franchises and Big Names Attract Audiences
Films that are part of a series (franchises) or include famous actors or directors usually perform better, thanks to built-in fan bases and greater audience trust.

# Next Step ?
That would be to take a deeper look at the best genres (like horror or action) to understand what makes them successful.
and out more about who watches these movies and what they like by looking at online trends or doing surveys. Afterwards Start a mini project as a test.

# Code Quality
All code was written in Python using industry-standard libraries such as Pandas, Matplotlib, Seaborn, and Scikit-learn. Key characteristics of the codebase include:

Modularity: Functions are separated for loading, cleaning, analyzing, and visualizing data to promote reusability.
Documentation: Inline comments and docstrings are used to clarify purpose and logic.
Efficiency: Vectorized operations and optimized queries reduce runtime for large datasets.
Reproducibility: Code is organized in a Jupyter Notebook or Python script, allowing anyone to rerun the analysis with minimal setup.
Version Control: Git was used to track changes and manage collaboration.

## Repo Structure
Data/bom.movie_gross.csv.gz

Data/im.db

Data/rt.movie_info.tsv.gz

Data/rt.reviews.tsv.gz

Data/tmdb.movies.csv.gz

Data/tn.movie_budgets.csv.gz

Images/Icon.jpg

Partials/*.py  [some modules]

PDFs/Dashboard.pdf

PDFs/Notebook.pdf

PDFs/Presentation.pdf

.gitignore

LICENSE

Main.ipynb

README.md