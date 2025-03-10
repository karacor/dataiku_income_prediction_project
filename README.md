# Income Prediction Using Census Data
This project predicts whether an individual's income exceeds $50K based on demographic and work-related features.

## Contents
- Jupyter Notebook (`dataiku.ipynb`)
- PowerPoint Presentation (`Census Income Classification Project.pptx`)
- Dataset: Census Income Data (not included here)

## Models Used
- CatBoost
- Random Forest
- Logistic Regression

## Key Findings
- Age and work weeks are key predictors of income.
- CAPGAIN and CAPLOSS combined into a single feature improved performance.

## How to Run
1. Clone this repository: `git clone https://github.com/YOUR-USERNAME/income_prediction_project.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open `income_prediction.ipynb` in Jupyter Notebook.
4. Edit the paths for the input census_income_learn.csv & census_income_test.csv files as well as the paths to save the processed files.
