# Titanic Survival — Exploratory Data Analysis

## Project Overview

This project presents an Exploratory Data Analysis (EDA) of the Titanic passenger dataset using Python, Pandas, and Matplotlib.

The objective is to assess data quality, explore passenger demographics, and identify patterns associated with survival outcomes.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

The analysis uses the Titanic training dataset, containing 891 passenger records and 12 variables.

Key variables include passenger survival status, gender, age, passenger class, ticket fare, and family relationships.

## Methodology

1. **Data Loading and Inspection:** Imported the dataset and examined its structure, data types, and descriptive statistics.
2. **Data Quality Assessment:** Identified missing values, checked duplicate records and passenger identifiers, and validated categorical and numerical values.
3. **Exploratory Data Analysis:** Examined passenger demographics, survival rates, age distributions, and ticket fares.
4. **Data Visualization:** Created histograms, bar charts, line charts, and box plots to communicate key patterns.
5. **Segment Analysis:** Compared survival outcomes across gender, passenger class, and age groups.

## Key Findings

### Overall Survival

- 342 of 891 passengers survived.
- The overall survival rate was approximately **38.38%**.

### Survival by Gender

- Female passengers: **74.20%** survival rate.
- Male passengers: **18.89%** survival rate.

### Survival by Passenger Class

- First class: **62.96%** survival rate.
- Second class: **47.28%** survival rate.
- Third class: **24.24%** survival rate.

### Age Analysis

- The median recorded passenger age was approximately 28 years.
- Children aged 0–9 had a survival rate of **61.29%**.
- Survival rates varied across age groups, with smaller sample sizes in older groups.

### Ticket Fare Analysis

- Survivors had a higher median ticket fare (26.00) than non-survivors (10.50).
- Ticket fare distributions were right-skewed and contained substantial outliers.
- Differences in fares should be interpreted alongside passenger class.

## Data Quality Findings

- No fully duplicated records were identified.
- No duplicated passenger identifiers were detected.
- Missing values were identified in Age (177), Cabin (687), and Embarked (2).
- Fifteen passengers had zero recorded ticket fares.
- No negative ages or ticket fares were detected.
- The original dataset was preserved during the initial assessment.

## Limitations

- The dataset contains missing values, particularly in Cabin and Age.
- Some passenger segments have relatively small sample sizes.
- Observed relationships are descriptive and do not establish causation.
- Findings apply to the available 891 passenger records rather than the complete Titanic passenger population.

## Project Files

- `Titanic_Survival_EDA.ipynb` — Jupyter Notebook containing the analysis and visualizations.
- `train.csv` — Source dataset.
- `README.md` — Project documentation.

## Conclusion

The analysis identifies substantial differences in Titanic survival outcomes across gender, passenger class, and age groups.

It demonstrates the application of data validation, descriptive statistics, segmentation, and visualization techniques to transform raw data into interpretable findings.