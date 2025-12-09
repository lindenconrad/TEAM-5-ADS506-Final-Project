# ADS506-Final-Project
Forecasting U.S. Sales Across Three Key Retail Categories

**Partner(s)/Contributor(s)**:<br>
Linden Conrad-Marut, Stephanie Smith, Shrey Thaker

### Installation
 To clone the repository:
   ```sh
   git clone https://github.com/lindenconrad/TEAM-5-ADS506-Final-Project.git
   ```

### Project Summary
This project analyzes three major U.S. retail sales categories using monthly time-series data from the U.S. Census Bureau/FRED (1992–2019):
Clothing Stores, Furniture & Home Furnishings, and Electronic Shopping & Mail-Order (E-Commerce).
Our goal was to uncover long-term trends and seasonal patterns, then compare forecasting approaches to determine which model best fits each retail category. We implemented and evaluated three forecasting methods:

ARIMA (AutoRegressive Integrated Moving Average)<br>
ETS (Error-Trend-Seasonality / Exponential Smoothing)<br>
TSLM (Time Series Linear Model)<br>

Results show that no single model performs best across all categories. Instead, each retail sector displays unique behavior requiring a category-specific forecasting strategy.

Clothing → strong seasonality → ETS performs best<br>
E-commerce → rapid growth trend → ARIMA performs best<br>
Furniture → steady linear growth w/ seasonal peaks → TSLM performs best<br>

These findings highlight the importance of tailored forecasting for inventory planning, budgeting, and retail strategy.

#### Project Objectives
1. Explore and visualize long-term retail sales behavior.
2. Determine whether series exhibit trend, seasonality, or structural changes.
3. Fit and compare forecasting models to identify the best model per category.

**Methods Used**<br>
• Exploratory Data Analysis • Data Visualization • Data Preprocessing • ARIMA • ETS • TSLM
 
**Technologies**<br>
• R

### Data
**Source:** U.S. Census Bureau. (n.d.). Retail and retailers sales time-series collection [Dataset]. Kaggle. https://www.kaggle.com/datasets/census/retail-and-retailers-sales-time-series-collection/data?select=MRTSSM4541USS.csv<br>
