# Investigating Bias in Online Movie Ratings

This project explores potential **biases and inflation** in online movie rating systems, focusing on patterns that may influence consumer trust and decision-making. 

Inspired by data journalist [**Walt Hickey's in-depth analysis**](https://fivethirtyeight.com/features/fandango-movies-ratings/) on rating manipulation published in 2015, the analysis examines historical and recent movie ratings to uncover trends to assess the prevalence of systemic rounding practices and inflated scores. Key concerns include the near absence of low ratings, a disproportionate concentration of scores above four stars, and the potential for commercial platforms to benefit from higher perceived movie quality. 

Given the film industry’s substantial economic impact and the influence online ratings wield over audience choices, evaluating the integrity of these systems is essential. The analysis aims to shed light on how these biases may persist or have evolved over time, ultimately contributing to a more transparent and trustworthy ratings ecosystem.


### Why should we care?
Understanding the integrity of online movie ratings is crucial for several reasons:

- The film industry is a significant economic force, generating billions annually at the U.S. box office. Consequently, the influence of **online ratings aggregators** on consumer decisions is substantial.
- Fandango, as a prominent player in the movie ticketing market, has a **vested interest** in shaping consumer perceptions through its ratings. Their influence extends to direct ticket sales.
- Regulatory bodies such as the **Federal Trade Commission** are vigilant in safeguarding consumers against deceptive and anti-competitive practices. Monitoring the online rating ecosystem for transparency and accountability is essential in ensuring **fair and transparent marketplace practices**.

Building upon Hickey's findings, this project seeks to assess whether Fandango has implemented measures to address these biases as previously indicated, or if the observed patterns continue to persist within their rating system. The goal is to contribute to a more transparent and accountable rating ecosystem, empowering consumers and regulatory bodies to make informed decisions.


### Finding Suitable Datasets
The analysis two distinct datasets for our investigation. This approach allows for the comparison of Fandango's ratings both before and after Walt Hickey's influential 2015 analysis:

- **The 2015 Dataset**: We'll begin by examining the dataset originally collected by Walt Hickey as part of his comprehensive analysis. The dataset, fandango_score_comparison.csv, provides a snapshot of Fandango's rating practices before potential adjustments made in response to Hickey's findings.

- **The 2016-2017 Dataset**: In addition to Hickey's dataset, we'll also incorporate a dataset spanning the years 2016 to 2017. This dataset provides a more recent perspective on Fandango's ratings landscape, allowing us to assess whether any changes or adjustments have occurred following Hickey's analysis.



# Investigating Bias in Online Movie Ratings

This project explores potential **biases and inflation** in online movie rating systems, with a focus on identifying patterns that may affect **consumer trust and decision-making**.

Inspired by [**Walt Hickey's**](https://fivethirtyeight.com/features/fandango-movies-ratings/) 2015 data journalism exposé on **rating manipulation**, this analysis compares Fandango’s movie ratings **before and after** the article’s publication to assess whether meaningful changes have occurred. By exploring trends such as **rating inflation**, **score rounding**, and **lack of low ratings**, the project aims to evaluate whether online platforms fairly reflect audience sentiment or promote inflated perceptions of movie quality.


## Objectives

* Investigate signs of systemic **rounding or score inflation** in movie ratings
* Compare historical (pre-2015) and recent (post-2015) ratings from Fandango
* Assess whether changes were made following **public scrutiny**
* Contribute to a more **transparent and trustworthy rating ecosystem**


## Why It Matters

* The **film industry** is a significant economic force, generating billions in revenue annually, and online ratings significantly impact audience decisions.
* Platforms like **Fandango**, which both rate and sell tickets, have a **vested interest** to promote higher scores.
* Ensuring **transparency** in rating systems protects consumers, aligns with the goals of **regulatory bodies** like the FTC, and ensures **fair and transparent marketplace practices**.

By shining light on these dynamics, this project empowers viewers to make informed choices and holds platforms accountable for fair practices.


## Datasets Used

To assess changes over time, the project uses two distinct datasets:

| Dataset                         | Description                                                                                               |
| ------------------------------- | --------------------------------------------------------------------------------------------------------- |
| `fandango_score_comparison.csv` | Collected by Walt Hickey for his 2015 analysis; reflects ratings before public exposure of potential bias |
| `movie_ratings_2016_17.csv`     | Contains Fandango ratings from 2016–2017; used to assess any shifts post-analysis                         |


## Key Findings

* **Ratings in 2016** were **slightly lower** than those in 2015 on average.
* The **minimum rating** dropped from **3.0 (2015)** to **2.5 (2016)** — a sign of improved variability.
* The **proportion of movies rated above 4.5** decreased significantly after 2015.
* Although not drastic, the shift suggests Fandango made **moderate corrections** following public scrutiny.


## Files in This Repository

| File                               | Description                                                        |
| ---------------------------------- | ------------------------------------------------------------------ |
| `Fandango_Ratings_Analysis_Report.ipynb` | Jupyter Notebook with the full EDA, comparison, and visualizations |
| `fandango_score_comparison.csv`    | Historical data from 2015                                          |
| `movie_ratings_2016_17.csv`        | More recent data from 2016–2017                                    |
| `README.md`                        | Project summary and context                         |


## Tools & Libraries

* Python (Pandas, Matplotlib)
* Jupyter Notebook

