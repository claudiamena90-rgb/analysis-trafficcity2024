# Urban Mobility & Economic Productivity Analysis – Sprint 5

This repository contains the analysis developed during Sprint 5 of the TripleTen Data Analytics Bootcamp.

The project explores the relationship between **urban mobility** and **economic productivity** in major Latin American cities using real data from the **TomTom Traffic Index** and **OECD Cities**. The analysis includes data cleaning, transformation, integration of multiple datasets, exploratory data analysis (EDA), and visualization to identify patterns between traffic congestion and economic indicators.

## 📂 Repository Contents

- `S5_ladb_mobility_economy_project_student.ipynb`
  → Main notebook containing data loading, cleaning, preprocessing, dataset merging, exploratory analysis, visualizations, and conclusions.

- `ladb_mobility_economy_2024_clean.csv`
  → Final cleaned dataset generated during the analysis.

## ▶ How to Open the Notebook in Google Colab

Click the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](URL_DEL_NOTEBOOK_EN_GITHUB)

Or:

1. Open the `.ipynb` file in GitHub.
2. Click **Open in Colab**.

## 📘 How to Reproduce the Analysis

1. Open `S5_ladb_mobility_economy_project_student.ipynb`.
2. Run the notebook cells from top to bottom.
3. The notebook loads the traffic and economic datasets, cleans and transforms the data, filters records for 2024, merges both datasets, generates visualizations, and exports the final cleaned dataset (`ladb_mobility_economy_2024_clean.csv`).

> **Note:** The notebook was developed using the datasets provided in the TripleTen environment (`/datasets/tomtom_traffic.csv` and `/datasets/oecd_city_economy.csv`). If you run the notebook locally, update the file paths accordingly.

## 🧠 Analysis Objectives

- Explore and understand the structure of two real-world datasets.
- Clean and standardize variables for analysis.
- Merge mobility and economic datasets by city and year.
- Analyze traffic congestion patterns across Latin American cities.
- Explore the relationship between congestion and economic indicators such as GDP per capita and unemployment.
- Produce a clean dataset ready for future analysis.
