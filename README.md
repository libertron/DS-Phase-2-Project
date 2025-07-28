![Icon](Images/Icon.jpg)

# Movie Studio Insights

# Overview

Our company has decided to start a new movie studio to join the growing trend of original video content. However, we don’t have much experience in the film industry. To help guide this new venture, we were asked to research what kinds of movies are currently doing well at the box office.

This project explores recent movie data to find out which film genres, release times, and other factors are most linked to success. We also look at things like budget, cast, and audience ratings to understand what makes a movie perform well.

The goal is to turn this information into simple, clear insights and recommendations that the studio can use to decide what types of films to produce. By using real data, we aim to give the new movie studio a strong and smart starting point.

# Business Understanding
The primary goal of this project is to help our company’s new movie studio make informed decisions about the types of films it should produce. With major studios seeing success through data-driven content strategies, we aim to explore recent box office trends to identify which film genres, themes, and production strategies are currently performing best. Our insights will translate directly into actionable recommendations—enabling the studio to compete effectively in the modern entertainment landscape.

# Data Understanding
To gain a comprehensive view of the market, we collected data from multiple reliable sources such as Box Office Mojo, The Numbers, IMDb, and Rotten Tomatoes. For this analysis we're going to use the IMDb dataset since it provide a bigger population. Our focus will be on columns : movie_basics and movie_ratings which are the most relevant.
This data will help us assess what types of films resonate most with audiences both commercially and critically.

# Data Preparation
Before analysis, the dataset underwent the following preprocessing steps:

Cleaning: Removed duplicate entries, fixed inconsistent genre labeling, and corrected invalid values.
Missing Value Handling: Filled or removed rows with missing, or genre information depending on their importance and availability.
Feature Engineering: Created new features for better filtering
Data Formatting: Ensured date and other fields were standardized.

# Data Analysis
Our exploratory analysis revealed key insights:

Genre Trends: Documentary, Biography, Music, Musical films tend to dominate the box office. However, Adult films often recieve low rating.
Release Timing: Summer and holiday season releases significantly outperform others.
Budget vs. Revenue: While high-budget films usually earn more, several low-budget titles achieved remarkable profitability, particularly in horror and comedy.
Ratings Correlation: Audience scores (especially IMDb) are moderately correlated with box office success, but star power and franchise status tend to have a stronger impact.
Franchise Impact: Sequels and franchise films typically outperform standalone films, suggesting an appetite for continuity and established universes.

# Visualization
We utilized a variety of visual tools to present our findings clearly:

Bar charts to compare genre popularity and average revenue.
Scatter plots to examine the relationship between duration and rating.
Bar plot to show determine most rated and less rated movie genres.
Histogram to see rating and runtime data distribution 
These visuals help transform raw data into understandable insights for stakeholders.

# Conclusion
Based on the data we explored, we discovered several important patterns that can help guide the new movie studio’s decisions:

### 1) Certain Genres Are More Liked
Documentary, Biography, Music, Musical, Sport, Animation, Drama are the top five one.
### 2) Duration Doesn't Matters But There Is A Standard
The success of the film is not really depend on its duration, but movies tend to last around 50 to 150 minutes according to the data.
### 3) I strongly suggest to avoid Adult Movies
Adult movies are more likely to have lower rating which is not great in terms of business marketing

# Next Step ?
That would be to take a deeper look at the best genres (like Documentary or Biography) to understand what makes them successful.
and out more about who watches these movies and what they like by looking at online trends or doing surveys. Afterwards Start a mini project as a test.

# Code Quality
All code was written in Python using industry-standard libraries such as Pandas, Matplotlib, and Seabornn. Key characteristics of the codebase include:

- Modularity: Functions are separated for loading, cleaning, analyzing, and visualizing data to promote reusability.
- Documentation: Inline comments and docstrings are used to clarify purpose and logic.
- Efficiency: Vectorized operations and optimized queries reduce runtime for large datasets.
- Reproducibility: Code is organized in a Jupyter Notebook, allowing anyone to rerun the analysis with minimal setup.
- Version Control: Git was used to track changes and manage collaboration.

## Repo Structure
Data/bom.movie_gross.csv.gz

Data/im.db (use this link to download it instead [https://github.com/learn-co-curriculum/dsc-phase-2-project-v3/blob/main/zippedData/im.db.zip](https://github.com/learn-co-curriculum/dsc-phase-2-project-v3/blob/main/zippedData/im.db.zip))

Data/rt.movie_info.tsv.gz

Data/rt.reviews.tsv.gz

Data/tmdb.movies.csv.gz

Data/tn.movie_budgets.csv.gz

Images/Icon.jpg

Partials/*.py  [some modules]

PDFs/Github.pdf

PDFs/Notebook.pdf

PDFs/Presentation.pdf

.gitignore

LICENSE

Main.ipynb

README.md