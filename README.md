# Marketing ROI Analysis Using Simple Linear Regression

## Project Overview

This project analyzes the relationship between marketing expenditure and sales performance using Simple Linear Regression. The objective is to identify the marketing channel that has the strongest impact on sales and provide data-driven recommendations for marketing budget allocation.

The analysis includes:

* Data loading and exploration
* Missing value assessment and data cleaning
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Simple Linear Regression using Ordinary Least Squares (OLS)
* Regression diagnostics
* Interpretation of model results
* Marketing ROI recommendations


## Dataset

The dataset contains four variables:

| Variable     | Description                          |
| ------------ | ------------------------------------ |
| TV           | TV advertising expenditure           |
| Radio        | Radio advertising expenditure        |
| Social_Media | Social media advertising expenditure |
| Sales        | Sales generated                      |


## Project Objectives

* Explore and clean the dataset
* Identify the marketing channel most correlated with Sales
* Build a Simple Linear Regression model
* Evaluate model assumptions
* Interpret regression outputs
* Recommend the most effective marketing channel for budget allocation


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Statsmodels
* Jupyter Notebook


## Installation

Install the required packages:

```bash
pip install pandas numpy matplotlib statsmodels
```

If Seaborn is available in your environment, you may also install:

```bash
pip install seaborn
```


## Running the Project

1. Clone the repository:

```bash
git clone https://github.com/yourusername/marketing-roi-analysis.git
```

2. Navigate to the project directory:

```bash
cd marketing-roi-analysis
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:

```text
regression_analysis.ipynb
```

and run all cells.


## Regression Model

The project uses an Ordinary Least Squares (OLS) Simple Linear Regression model:

Sales = β₀ + β₁(TV)

Where:

* Sales is the dependent variable
* TV advertising expenditure is the independent variable


## Key Findings

* TV advertising showed the strongest correlation with Sales.
* The regression model achieved an R-squared value of approximately 0.999.
* TV advertising was a statistically significant predictor of Sales.
* Regression assumptions of linearity, homoscedasticity, and normality were satisfied.


## Recommendation

Based on the analysis, TV advertising should receive the highest priority in future marketing budget allocations because it demonstrated the strongest relationship with Sales and the highest predictive power among all marketing channels.


## Author

Anthony Bioseh
