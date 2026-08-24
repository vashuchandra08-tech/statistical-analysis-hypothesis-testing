# Statistical Analysis and Hypothesis Testing

## Project Overview

This project was completed as part of Week 3 of a Data Science internship.

The project focuses on statistical analysis and hypothesis testing using Python. The main objective was to investigate whether TV advertising expenditure has a statistically significant relationship with product sales.

## Research Question

Is there a statistically significant relationship between TV advertising expenditure and product sales?

## Hypotheses

### Null Hypothesis (H₀)

There is no statistically significant relationship between TV advertising expenditure and product sales.

### Alternative Hypothesis (H₁)

There is a statistically significant relationship between TV advertising expenditure and product sales.

## Dataset

The Advertising dataset contains information about:

- TV advertising expenditure
- Radio advertising expenditure
- Newspaper advertising expenditure
- Product sales

The dataset contains 200 observations.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Google Colab

## Statistical Methods

The following methods were used:

- Descriptive statistics
- Pearson correlation
- Simple linear regression
- P-value analysis
- 95% confidence interval
- Shapiro-Wilk test
- Durbin-Watson statistic

## Key Results

- Pearson correlation between TV and Sales: **0.7822**
- Pearson correlation p-value: **1.467 × 10⁻⁴²**
- R-squared: **0.612**
- TV regression coefficient: **0.0475**
- 95% confidence interval: **0.042–0.053**
- Shapiro-Wilk p-value: **0.2133**
- Durbin-Watson statistic: **1.935**

The results indicate a statistically significant positive association between TV advertising expenditure and sales.

## Visualizations

The project includes:

- Distribution histograms
- TV vs Sales scatter plot
- Regression plot
- Residual histogram
- Residuals vs fitted values
- Correlation heatmap

## Conclusion

The statistical analysis provides strong evidence of a positive and statistically significant relationship between TV advertising expenditure and product sales. However, the analysis demonstrates association rather than causation.

## Project Files

- `Week_3_Statistical_Analysis.ipynb` – Complete Python analysis
- `Advertising.csv` – Dataset
- `Week_3_Statistical_Analysis_Report.docx` – Final project report
- `visualizations/` – Project graphs and charts
