# Government Volumes Analysis

This R project is focused on analyzing trends in government and insurance volumes, finance and insurance sectors, and various types of leases in the automotive industry. The analysis includes time series visualizations, correlation analysis, and LASSO regression modeling to identify key predictors of government volumes.

## Project Overview

This project aims to:
- Visualize trends in government volumes, insurance volumes, and various types of leases over time.
- Conduct a correlation analysis to understand the relationships between different financial and insurance variables.
- Apply LASSO regression to predict government volumes based on various financial and lease-related predictors.

## Key Components

1. **Data Loading and Preparation**
   - The data is read from an Excel file and prepared for analysis. Unnecessary columns are removed to focus on relevant variables.

2. **Time Series Visualization**
   - Line charts are created to visualize the trends in government volumes, insurance volumes, finance and insurance sectors, and various types of leases over the years.

3. **Correlation Analysis**
   - A correlation matrix is generated to explore the relationships between the financial, insurance, and leasing variables. This helps in identifying strong correlations that could be important for further analysis.

4. **LASSO Regression Modeling**
   - A LASSO regression model is used to predict government volumes based on a set of financial and lease-related predictors. The model selects the most significant variables and calculates the model's accuracy using R-squared and MSE.

## Dependencies

This project requires the following R packages:

- `readr`
- `readxl`
- `dplyr`
- `ggplot2`
- `GGally`
- `car`
- `MASS`
- `glmnet`
- `plotly`
- `corrplot`
- `ggcorrplot`
- `caret`
- `reshape2`
- `knitr`

You can install the necessary packages using the command:

```R
install.packages(c("readr", "readxl", "dplyr", "ggplot2", "GGally", "car", "MASS", "glmnet", "plotly", "corrplot", "ggcorrplot", "caret", "reshape2", "knitr"))
