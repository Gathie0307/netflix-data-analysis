# Netflix Data Analysis

## Project Overview
This project explores Netflix's dataset to generate insights and build a machine learning model. The analysis includes data cleaning, visualization, and predictive modeling using Python libraries such as `Pandas`, `Matplotlib`, `Seaborn`, and `scikit-learn`.

---

## Dataset
The dataset contains information on Netflix movies and TV shows, including title, type, director, cast, country, date added, release year, rating, duration, and genre.
- **Source:** [Kaggle – Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## Analysis Questions
1. How many movies vs TV shows are on Netflix?
2. Which country produces the most content?
3. How has content production changed over the years?
4. Are certain ratings more common for movies than TV shows?
5. Which genres dominate Netflix's catalog?

## Hypotheses
1. The majority of Netflix content is movies.
2. The United States produces the largest amount of Netflix content.
3. Netflix has released more content in recent years compared to earlier years.
---

## Data Cleaning
1. Dropped duplicates to ensure each record is unique.
2. Filled missing values in categorical columns (`director`, `cast`, `country`, `rating`) using the mode.
3. Standardized text columns with stripped whitespace and capitalized titles/countries.
4. Converted rating into numeric codes using .astype('category').cat.codes.
5. Changed date_added into a datetime format.

---

## Data Visualization
- Movies vs TV Shows
- Top 10 countries producing Netflix content
- Netflix content added over the years
- Top 10 genres on Netflix
- Horizontal bar chart showing the most frequent UK TV shows.
- Movies vs TV Shows added in the UK over the years

---

## Result
 - Movies make up the majority of Netflix's catalog.
 - The United States is the largest content producer, followed by India and the UK.
 - Content additions have steadily increased, peaking in recent years.

