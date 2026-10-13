# Titanic Dataset — Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on Exploratory Data Analysis (EDA) of the Titanic passenger dataset. The objective is to identify patterns, trends, and relationships in passenger survival using Python and data visualization techniques.

## Objectives
- Understand the dataset structure and identify missing values.
- Perform statistical analysis using Pandas.
- Explore passenger survival patterns based on gender, passenger class, and age.
- Visualize data distributions and potential outliers.
- Identify relationships between numerical variables using correlation analysis.
- Summarize key findings from the analysis.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Analysis Performed
1. Dataset inspection using `shape`, `info()`, and `describe()`.
2. Frequency analysis using `value_counts()`.
3. Survival analysis by gender and passenger class.
4. Age and fare distribution analysis using histograms and boxplots.
5. Correlation analysis using a heatmap.
6. Pairwise relationship analysis using a pairplot.
7. Age-group survival analysis.
8. Data quality checks, including missing values and duplicate rows.

## Key Findings
- Out of 891 passengers, 342 survived and 549 did not survive.
- The overall survival rate was approximately 38.4%.
- Female passengers had a substantially higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Children had a higher observed survival rate than seniors in the age-group analysis.
- The fare distribution was right-skewed, with a small number of high-fare observations.
- Missing values and relationships between numerical variables were examined as part of the analysis.

## Dataset Information
The dataset contains 891 rows and 12 columns, including passenger survival status, passenger class, gender, age, fare, and embarkation details.

## Repository Contents
- `Task_5_Titanic_EDA.ipynb` — Jupyter Notebook containing the analysis, visualizations, and observations.
- `Task_5_Titanic_EDA_Report.pdf` — PDF report summarizing the findings.

## Conclusion
The analysis highlights differences in survival outcomes across gender, passenger class, and age groups. Visualizations and summary statistics helped identify important patterns in the data. These findings are descriptive and show associations rather than proving cause and effect.

