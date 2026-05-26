# 🌍 World Happiness Index Analysis & Insights

An end-to-end data science project analyzing global happiness scores using the **World Happiness Report**. This project explores how various socio-economic factors—such as GDP, social support, life expectancy, and freedom—impact a nation's overall happiness ranking.

---

## 🚀 Project Overview & Workflow

In this project, I handled the entire data lifecycle, from raw data ingestion to deeper exploration:

1. **Data Ingestion:** Loaded and inspected the global dataset containing information for 130 countries across 10 distinct socio-economic columns.
2. **Data Cleaning & Preprocessing:** Formatted features, checked for missing values, and prepared the structural data for analytical pipelines.
3. **Exploratory Data Analysis (EDA):** Analyzed why top-tier nations (like Finland and Iceland) score incredibly high, while identifying patterns among lower-ranked nations.
4. **Feature Analysis:** Investigated the strong correlations between a country's happiness score and its economy (`gdp_per_capita`), healthcare (`healthy_life_expectancy`), and community (`social_support`).

---

## 📊 Key Insights from the Data

Based on the dataset, the metrics highlight a clear division in global happiness drivers:

* **The Leaders:** Western European countries like **Finland (Rank 1)** and **Iceland (Rank 2)** lead the world, showing maximum scores in `social_support` (>1.5) and `healthy_life_expectancy` (>0.95).
* **The Core Drivers:** Money and health matter! Happiness scores are highly sensitive to changes in `gdp_per_capita` and `social_support`.
* **The Struggle:** Regions like Sub-Saharan Africa and South Asia encounter low happiness rankings due to systemic deficits in economic stability and health infrastructure.

---

## 🛠️ Tech Stack & Tools Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Environment:** Jupyter Notebook / Google Colab

---

## 📂 Dataset Features Explained

The project analyzes 130 rows and 10 critical columns:
* `rank` / `country` / `region`: Geographic and positional identifiers.
* `score`: The overall happiness score (0 to 10 scale).
* `gdp_per_capita`: Economic output per person.
* `social_support`: Having someone to count on in times of trouble.
* `healthy_life_expectancy`: Physical health and longevity metrics.
* `freedom`: Personal freedom to make life choices.
* `generosity`: National charitable tendencies.
* `corruption`: Public perception of institutional trustworthiness.

---

## 💻 How to Run This Project

1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/World-Happiness-Analysis.git](https://github.com/YOUR_USERNAME/World-Happiness-Analysis.git)