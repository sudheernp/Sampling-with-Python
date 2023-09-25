# Sampling with Python

This repository contains Python notebooks for two projects focused on sampling techniques and making point estimates using Python.

## Project 1: Simulating Random Sampling for Population Mean Estimation

### Introduction
Throughout the following exercises, you will learn to use Python to simulate random sampling and make a point estimate of a population mean based on your sample data. Before starting on this programming exercise, we strongly recommend watching the video lecture and completing the IVQ for the associated topics.

Key Takeaways:
1. As the central limit theorem predicts, the histogram of the sampling distribution is well approximated by the normal distribution. The outline of the histogram closely follows the normal curve.
2. The mean of the sampling distribution, the blue dotted line, overlaps with the population mean, the green solid line. This shows that the two means are essentially equal to each other.
3. The sample mean of your first estimate of 50 districts, the red dashed line, is farther away from the center. This is due to sampling variability.

The central limit theorem shows that as you increase the sample size, your estimate becomes more accurate. For a large enough sample, the sample mean closely follows a normal distribution.

Your first sample of 50 districts estimated the mean district literacy rate as 74.22%, which is relatively close to the population mean of 73.4%.

To ensure your estimate will be useful to the government, you can compare the nation’s literacy rate to other benchmarks, such as the global literacy rate, or the literacy rate of peer nations. If the nation’s literacy rate is below these benchmarks, this may help convince the government to devote more resources to improving literacy across the country.

## Project 2: Effective Sampling for Air Quality Analysis

### Introduction
In this activity, you will engage in effective sampling of a dataset in order to make it easier to analyze. As a data professional, you will often work with extremely large datasets, and utilizing proper sampling techniques helps you improve your efficiency in this work.

For this activity, you are a member of an analytics team for the Environmental Protection Agency. You are assigned to analyze data on air quality with respect to carbon monoxide—a major air pollutant—and report your findings. The data utilized in this activity includes information from over 200 sites, identified by their state name, county name, city name, and local site name. You will use effective sampling within this dataset to analyze carbon monoxide levels.

Considerations:
- Sampling with replacement on a dataset leads to duplicate rows.
- Sample means are different from population means due to sampling variability.
- The central limit theorem helps describe the sampling distribution of the sample mean for many different types of datasets.

Findings to Share:
- The mean AQI in a sample of 50 observations was below 100 in a statistically significant sense (at least 2–3 standard errors away). For reference, AQI values at or below 100 are generally thought of as satisfactory.
- This notebook didn't examine values outside the "satisfactory" range, so analysis should be done to investigate unhealthy AQI values.

What to Convey to External Stakeholders:
- Carbon monoxide levels are generally satisfactory.
- Funding should be allocated to further investigate regions with unhealthy levels of carbon monoxide and improve the conditions in those regions.

---

### Notebooks

1. [Project 1 - Simulating Random Sampling for Population Mean Estimation](project1.ipynb)
2. [Project 2 - Effective Sampling for Air Quality Analysis](project2.ipynb)

Each project has its own notebook for detailed implementation and analysis.

Feel free to explore the notebooks in this repository to learn more about these projects and the techniques used for sampling with Python.

