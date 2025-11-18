# Travel Dataset — Yelp Latin American Restaurants


**Author:** Daniela Binns


## Overview


This repository contains code and the curated dataset of Latin American restaurants collected via the Yelp Fusion API. The dataset is intended for exploratory data analysis and storytelling about restaurant distribution, ratings, and popularity across multiple U.S. cities.


**Motivation & question of interest:**
I wanted to investigate how restaurant ratings, review counts, and price levels vary across cities and categories — for example, are higher-priced restaurants generally rated higher? Which Latin cuisines are most popular in which cities?


## Repository contents


- `yelp_restaurants.py` — Main script to query the Yelp Fusion API and save results as `latin_american_restaurants.csv`.
- `restaurants_eda.py` — EDA script that loads the CSV, computes summary statistics, and generates plots.
- `latin_american_restaurants.csv` — Final csv of dataset.
- `images/` — generated EDA plots (committed after generation).
- `data_acq_blog.qmd` — Quarto blog post that summarizes the project and links to code and dataset.
- `requirements.txt` — Python package list (see below).


## Requirements


Create a virtual environment and install the dependencies.


```bash
python -m venv venv
source venv/bin/activate # Mac/Linux
venv\Scripts\activate # Windows PowerShell
pip install -r requirements.txt

