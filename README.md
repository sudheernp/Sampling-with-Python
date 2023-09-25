# Sampling with Python

Welcome to the Sampling with Python project repository. This repository contains Python notebooks for two projects focusing on sampling techniques and their applications in data analysis.

## Project 1: Estimating Population Mean Literacy Rate

### Overview
In this project, we'll explore the concept of random sampling and making point estimates of a population mean using Python. You'll continue with our previous scenario where you work for the Department of Education in a large nation, analyzing district literacy rate data.

The challenge is to collect data on district literacy rates, but with limited time, you can only survey 50 randomly chosen districts out of the 634 in your dataset. Your goal is to estimate the mean literacy rate for all 634 districts based on your sample of 50 districts.

### Simulate Random Sampling
Python can be a powerful tool to simulate random sampling. You'll use the `pandas.DataFrame.sample()` function to achieve this. Key arguments include `n` for sample size, `replace` for sampling with or without replacement, and `random_state` for setting a random seed.

Key Takeaways:
- The histogram of the sampling distribution closely follows the normal curve, as predicted by the central limit theorem.
- The mean of the sampling distribution overlaps with the population mean, indicating similarity.
- Sampling variability causes the sample mean to differ from the population mean.

Your initial sample of 50 districts estimated the mean district literacy rate as 74.22%, relatively close to the population mean of 73.4%. This estimate can help inform government resource allocation for literacy improvement.

## Project 2: Effective Sampling for Air Quality Analysis

### Introduction
In this activity, you'll engage in effective sampling of a dataset to facilitate analysis. As a data professional, you often encounter large datasets, and proper sampling techniques enhance efficiency. You're part of an analytics team at the Environmental Protection Agency (EPA), tasked with analyzing air quality data related to carbon monoxide—a significant air pollutant.

The dataset comprises information from over 200 sites, categorized by state, county, city, and local site name. Your objective is to utilize effective sampling methods within this dataset to analyze carbon monoxide levels.

### Key Takeaways
- Sampling with replacement on a dataset leads to duplicate rows.
- Sample means differ from population means due to sampling variability.
- The central limit theorem aids in describing the sampling distribution of the sample mean for various datasets.

### Findings and Recommendations
- The mean Air Quality Index (AQI) in a sample of 50 observations was statistically significant, below 100 (at least 2–3 standard errors away). AQI values at or below 100 are generally satisfactory.
- Further analysis is needed to investigate AQI values outside the "satisfactory" range.

### Conveying to External Stakeholders
- Emphasize that carbon monoxide levels are generally satisfactory.
- Recommend allocating funding to investigate regions with unhealthy carbon monoxide levels and improve conditions in those areas.

---

### Notebooks

1. [Project 1 - Estimating Population Mean Literacy Rate](project1.ipynb)
2. [Project 2 - Effective Sampling for Air Quality Analysis](project2.ipynb)

Each project has its own notebook for detailed implementation and analysis.

Feel free to explore the notebooks in this repository to learn more about these projects and the techniques used for sampling and data analysis in Python.
