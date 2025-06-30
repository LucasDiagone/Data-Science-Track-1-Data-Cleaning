
# Data Cleaning and Preprocessing Project

Educational project focused on cleaning and treating simulated credit data. The goal is to apply essential data preparation techniques that are typically required before modeling or visualization.

## Objectives

- Correct invalid ages (e.g., negative values or above 100)
- Standardize column names for consistency
- Handle unrealistic salary values by replacing outliers with the mode
- Detect salary outliers using both visual (boxplot, histogram) and statistical (Z-Score) methods
- Standardize inconsistent gender entries (e.g., F, Fem, masc) using .replace()
- Identify and analyze missing values
- Filter rows using .query() and .loc[] with .between() or logical conditions
- Explore categorical variables with .groupby(), .value_counts(), and visual summaries

## Project Structure

```
data/         → Simulated CSV data  
notebooks/    → Jupyter notebook(s) with step-by-step analysis  
README.md     → Project overview and usage guide  
```

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. Install the required dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib
   ```

3. Run the notebook:
   - Open Jupyter Notebook or Jupyter Lab
   - Navigate to the `notebooks/` folder
   - Run `data_cleaning.ipynb` step-by-step

## Notes

- The dataset is simulated and designed to intentionally include common data issues.
- This project serves as a practical introduction to real-world data cleaning.
- It's a foundation step before applying Machine Learning or data visualization techniques.
