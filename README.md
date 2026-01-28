# Level 1 – Task 2: Exploratory Data Analysis (EDA)
Perform an exploratory analysis on a
given dataset to identify patterns, trends, and
summary statistics.

## Objective
Calculate summary statistics (mean, median, mode,
standard deviation).
Visualize data distributions using histograms, boxplots,
and scatter plots.
Find correlations between numerical features.

## Tools Used
- Python
- pandas
- matplotlib
- seaborn

## Tasks Performed

### 1. Summary Statistics
Calculated key descriptive statistics for all numerical features:

| Feature | Mean | Median | Mode | Std Dev |
|--------|------|--------|------|--------|
| Open | 86.35 | 64.97 | 70.0 | ~101 |
| High | 87.13 | 65.56 | 72.0 | ~102 |
| Low | 85.55 | 64.35 | 77.0 | ~100 |
| Close | 86.37 | 64.98 | 34.5 | ~101 |
| Volume | 4,253,611 | 2,084,896 | 1,241,019 | ~8.23M |

### 2. Visualizations
To understand distributions and relationships, the following plots were created:

- **Histogram (Closing Prices)** → shows price clustering and skewness
- **Boxplot (Prices)** → reveals volatility and outliers
- **Scatter Plot (Open vs Close)** → shows price movement patterns

### 3. Correlation Analysis
A correlation matrix was generated to understand relationships between numerical features.

Key findings:
- Open, High, Low, and Close prices are **highly correlated (~0.999)**
- Trading Volume has **weak correlation with prices (~ -0.15)**

## Key Insights
- Stock prices are **highly volatile** with extreme outliers.
- Median values better reflect typical trading levels.
- Price features move together consistently.
- Trading volume does not strongly influence price changes.

## Files Included
- `Task2_Level1_EDA_StockAnalysis.ipynb` – contains full code, outputs, and visualizations.
