# Glassdoor Tech Jobs — Salary Analysis & Prediction

## Project Overview
This project analyzes approximately 956 tech job postings scraped from Glassdoor (2017-2018) to understand the factors driving salary differences in the tech industry. The analysis explores variables such as job titles, company size, location, and industry sector.

Beyond exploratory data analysis (EDA), the project implements machine learning models (Ridge Regression, Random Forest, and XGBoost) to predict salaries based on job attributes.

## Key Findings
- **Primary Drivers:** Job title and location are the strongest predictors of salary.
- **Seniority Impact:** Senior roles earn nearly double the salary of entry-level analyst positions.
- **Geographic Premium:** Jobs in California offer a $22K median premium over the national median.
- **Company Size:** Follows a U-shaped pattern where small startups and large enterprises tend to pay more than mid-sized companies.
- **Sector Insights:** Biotech & Pharma emerged as the highest-paying sector, surpassing traditional IT.
- **Model Performance:** The tuned XGBoost model achieved the best results with an R² of approximately 0.62.

## Project Structure
- `Glassdoor_Final_Submission (2).ipynb`: The main Jupyter Notebook containing data cleaning, EDA, feature engineering, and model building.
- `glassdoor_jobs.csv`: The raw dataset used for the analysis.

## Dataset Features
The dataset includes the following columns:
- `Job Title`
- `Salary Estimate`
- `Job Description`
- `Rating`
- `Company Name`
- `Location`
- `Headquarters`
- `Size`
- `Founded`
- `Type of ownership`
- `Industry`
- `Sector`
- `Revenue`
- `Competitors`

## Dependencies
To run the notebook, you will need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `scikit-learn`
- `xgboost`
- `joblib`

You can install them using pip:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn xgboost joblib
```

## How to Run
1. Ensure you have the dependencies installed.
2. Open `Glassdoor_Final_Submission (2).ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells sequentially to reproduce the analysis and model results.

## Author
**Varanasi Rohit**
- GitHub: [varanasirohit2006](https://github.com/varanasirohit2006)
- Project Repository: [Glassdoor-Tech-Jobs-Salary-Analysis-Prediction_ML](https://github.com/varanasirohit2006/Glassdoor-Tech-Jobs-Salary-Analysis-Prediction_ML.git)
