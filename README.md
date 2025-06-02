# Titanic Dataset - Exploratory Data Analysis (EDA)

## Overview
This project explores the Titanic dataset to uncover patterns and insights about passenger survival using Python's Pandas, Matplotlib, and Seaborn. The analysis includes data cleaning, visualization, and statistical summaries.

## Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data?select=train.csv&utm_source=chatgpt.com) (provided in the repository as `titanic.csv`)
- **Rows**: 891 passengers  
- **Columns**: 12 features including:
  - `Survived`: Target variable (0 = No, 1 = Yes)
  - `Pclass`: Ticket class (1st, 2nd, 3rd)
  - `Age`, `Sex`, `Fare`, etc.

## Key Steps
1. **Data Cleaning**:
   - Handled missing values in `Age` (median imputation) and `Embarked` (mode imputation).
   - Dropped the `Cabin` column (77% missing values).
2. **Visualizations**:
   - Survival rates by gender, class, and family size.
   - Age distributions and fare correlations.
   - Heatmaps for feature correlations.
3. **Statistical Analysis**:
   - Used `.describe()` and `.value_counts()` for summaries.

## Key Findings
- **Gender Impact**: 74% of females survived vs. 19% of males.
- **Class Mattered**: 63% of 1st-class passengers survived vs. 24% of 3rd-class.
- **Age Trends**: Children (<10) had a 59% survival rate (highest among age groups).
- **Fare Correlation**: Higher fares linked to higher survival rates (median fare for survivors: £26 vs. £10 for non-survivors).

## Files
- `Titanic_EDA.ipynb`: Jupyter Notebook with full analysis code.
- `titanic.csv`: dataset.
- `task5report.pdf`: Documented observations in report.
- `README.md`: Summary.

## Tools Used
- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn
- Environment: Google Colab
