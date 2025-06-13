# Investigating Bias in Online Movie Ratings

This project explores potential biases and inflation in online movie rating systems, focusing on patterns that may influence consumer trust and decision-making. Inspired by prior data journalism investigating rating manipulation, we analyze historical and recent movie ratings to assess the prevalence of systemic rounding practices and inflated scores. Key concerns include the near absence of low ratings, a disproportionate concentration of scores above four stars, and the potential for commercial platforms to benefit from higher perceived movie quality. Given the film industry’s substantial economic impact and the influence online ratings wield over audience choices, evaluating the integrity of these systems is essential. Our analysis aims to shed light on how these biases may persist or have evolved over time, ultimately contributing to a more transparent and trustworthy ratings ecosystem.

In this study, we explore the presence of biases and potential dishonesty in online movie rating aggregators, with a specific focus on Fandango. Inspired by data journalist Walt Hickey's in-depth analysis published in 2015, our aim is to scrutinize Fandango's rating data for any persistent patterns indicative of bias.

Hickey's investigation uncovered significant irregularities within Fandango's rating system, including:

- Consistent rounding up of ratings to the nearest half-star, without any instances of rounding down.
- An overwhelming prevalence of high ratings; nearly no movies received ratings below three stars (98% of the time), with 75% of ratings falling within the four-star range or higher.

Building upon Hickey's findings, our project seeks to assess whether Fandango has implemented measures to address these biases as previously indicated, or if the observed patterns continue to persist within their rating system. We aim to contribute to a more transparent and accountable rating ecosystem, empowering consumers and regulatory bodies to make informed decisions.

### Finding Suitable Datasets
We've chosen to utilize two distinct datasets for our investigation. This approach allows us to compare and analyze Fandango's ratings both before and after Walt Hickey's influential 2015 analysis:

- The 2015 Dataset: We'll begin by examining the dataset originally collected by Walt Hickey as part of his comprehensive analysis. The dataset, fandango_score_comparison.csv, provides a snapshot of Fandango's rating practices before potential adjustments made in response to Hickey's findings.

- The 2016-2017 Dataset: In addition to Hickey's dataset, we'll also incorporate a dataset spanning the years 2016 to 2017. This dataset, movie_ratings_16_17.csv, provides a more recent perspective on Fandango's ratings landscape, allowing us to assess whether any changes or adjustments have occurred following Hickey's analysis.
