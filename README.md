🎬 Fandango Rating Bias Analysis

📊 Project Overview

This project explores whether Fandango’s movie ratings are biased toward higher scores compared to other review platforms. The analysis is based on publicly available data and web-scraped Fandango ratings, with comparisons to critics’ and audience ratings from other sources.

The notebook performs data cleaning, visualization, and statistical comparison to assess discrepancies and patterns in rating distributions.

📁 Files Included
File	Description
Fandango_Rating_Bias_Analysis.ipynb	Main Jupyter notebook containing the full analysis, visualizations, and conclusions.
fandango_scrape.csv	Dataset of Fandango movie ratings scraped from the website.
all_sites_scores.csv	Dataset of ratings collected from multiple review platforms (e.g., Rotten Tomatoes, Metacritic, IMDB).
🧠 Key Objectives

Investigate whether Fandango consistently displays inflated ratings.

Compare average ratings across multiple platforms.

Visualize and interpret rating distributions.

Quantify rating bias through statistical measures.

🧰 Technologies Used

Python

Pandas for data manipulation

Matplotlib / Seaborn for visualizations

NumPy for numerical operations

Jupyter Notebook for exploration and documentation

📈 Example Insights

Fandango’s displayed ratings tend to cluster around higher values compared to competitors.

Visualizations show a skew toward inflated scores for the same movies.

Average discrepancies are statistically significant across datasets.


📜 References

Walt Hickey, FiveThirtyEight: “Be Suspicious Of Online Movie Ratings, Especially Fandango’s”

Publicly available datasets from FiveThirtyEight’s repository
