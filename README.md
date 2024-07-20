# Statistical Analysis of Walmart Sales Data

## Project Overview

This project involves the analysis and prediction of weekly sales data from 45 Walmart stores across the United States. The dataset spans from February 5, 2010, to November 1, 2012, and includes key features such as store identifiers, sales figures, holiday flags, temperature, fuel prices, Consumer Price Index (CPI), and unemployment rates. The primary goal is to identify significant factors affecting sales and develop predictive models to forecast future sales, especially during critical holiday weeks.

## Dataset

The dataset used for this analysis can be found on Kaggle: [Walmart Store Sales Dataset](https://www.kaggle.com/datasets/yasserh/walmart-dataset)

### Features:

- **Store**: Unique identifier for each of the 45 stores.
- **Date**: Week of sales.
- **Weekly_Sales**: Total sales for the store in a given week.
- **Holiday_Flag**: Binary indicator (1 if the week includes a holiday, 0 otherwise).
- **Temperature**: Local temperature on the day of sales.
- **Fuel_Price**: Price of fuel in the region.
- **CPI**: Consumer Price Index.
- **Unemployment**: Unemployment rate in the region.

### Holiday Events:

- Super Bowl: February 12, 2010, February 11, 2011, February 10, 2012
- Labor Day: September 10, 2010, September 9, 2011, September 7, 2012
- Thanksgiving: November 26, 2010, November 25, 2011, November 23, 2012
- Christmas: December 31, 2010, December 30, 2011, December 28, 2012

## Project Steps

1. **Data Cleaning and Preprocessing**:
    - Handled missing values, duplicates, and outliers.
    - Converted date formats and categorical variables.
    - Normalized numerical features.

2. **Exploratory Data Analysis (EDA)**:
    - Visualized sales trends and patterns using ggplot2.
    - Analyzed the impact of holidays and economic factors on sales.

3. **Statistical Analysis**:
    - Hypothesis Testing: Determined the significance of sales differences during holiday weeks.
    - Confidence Intervals: Estimated sales during major holidays.
    - F-Test and ANOVA: Assessed sales variability and differences across stores.

4. **Feature Engineering**:
    - One-hot encoding for categorical variables.
    - Feature scaling to standardize numerical features.

5. **Model Development**:
    - Built and validated multiple linear regression models.
    - Performed feature selection to optimize model performance.

6. **Model Evaluation**:
    - Calculated Mean Squared Prediction Error (MSPE) on test data.
    - Achieved an R-squared value of 0.93 in the final model.

## Key Findings

- Identified significant factors affecting weekly sales, such as holidays, store location, and economic indicators.
- Provided actionable insights for sales trends, aiding strategic planning for inventory and staffing during holidays.

## Tools and Libraries

- R Programming
- tidyverse
- ggplot2
- lubridate
- gridExtra
- corrplot
- leaps
- MASS
- car

## Repository Structure

- `data/`: Contains the dataset (if permissible to include).
- `scripts/`: R scripts for data cleaning, EDA, statistical analysis, and model development.
- `README.md`: Project overview and instructions.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/Jagadeesh-N/Walmart-Store-Sales-Prediction-Analysis.git
    cd walmart-sales-prediction
    ```

2. Install necessary packages:
    ```r
    install.packages(c("tidyverse", "ggplot2", "lubridate", "gridExtra", "corrplot", "leaps", "MASS", "car"))
    ```

3. Run the analysis scripts:
   which is in ipynb file 
