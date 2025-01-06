# Automotive Car Loan Analysis

This repository contains an in-depth analysis of automotive loan and car purchase trends over a 10-year period, segmented quarterly. The analysis addresses key questions about the interplay between loan approvals, car purchases, and loan rates.

Analysis Overview

Key Questions Explored:

    1.	Are the number of people taking out loans increasing or decreasing?
    
    2.	Has the number of people purchasing cars increased or decreased?
    
    3.	Do trends in loan approvals correlate with trends in car purchases?

# ----------------------------------------------------------------

# Tools and Frameworks:

Jupyter Notebook: For data cleaning, merging, and analysis.

Python (Pandas, Matplotlib): Used for data manipulation and visualization.

VS Code: Development environment for creating and analyzing the data.

# ----------------------------------------------------------------

# Key Steps:

Data Cleaning and Transformation: Standardized formats, renamed columns, handled missing values, and merged datasets for comprehensive analysis.

Trend Analysis: Created visualizations to compare metrics like total loans, average car sales per person, and loan rates.

Population Adjustments: Accounted for population growth to provide per capita insights into car purchases.

# ----------------------------------------------------------------

# Summary of Findings:

Loan Trends: The number of people taking out loans has been rapidly decreasing post-COVID-19, with loan rates playing a significant role.

Car Purchase Trends: Car purchases per person have shown an increasing trend, returning to pre-pandemic levels.

Loan and Purchase Correlation: While loan approvals and car purchases initially moved together, post-pandemic loan rate fluctuations caused a divergence.


# ----------------------------------------------------------------

# Statistical Analysis:

**Total Loan Amount** 

*T-statistic: -9.49*

Interpretation: 
    a. The large negative t-statistic suggests that the Total Loan Amount decreased significantly after the onset of the COVID-19 pandemic.

**Average Loan Rate**

*T-statistic: 0.63*

Interpretation: The small t-statistic suggests that loan rates remained relatively stable despite the pandemic.

**Average Financed Amount**

*T-statistic: -12.34*

Interpretation: The large negative t-statistic indicates a considerable decrease in the average amount financed per loan after the COVID-19 outbreak.

**Average Loan Amount**

*T-statistic: -9.71*

Interpretation: Similar to the Average Financed Amount, this suggests a significant decrease in the average loan size post-COVID.

**Total People Getting Loans**

*T-statistic: 3.89*

Interpretation: The positive t-statistic suggests an increase in the number of people getting loans after the COVID-19 pandemic began.

# ----------------------------------------------------------------

# Data Sources

To ensure we had consistency among all our data sets, we first reviewed the timeframe we wanted to focus on.  to work with a large enough timeframe that we could see visible trends in the data. Since data for Population for 2024 was not yet available, we chose to end our pull parameter for all the data at Q4 2023.  FRED (Federal Reserve Bank of St. Louis) enables a pull parameter to be set for each data set.  Once we determined our range, we extracted the relevant .csv files into our GitHub repository.  The files we chose are noted below:

•Balance Sheet: Total Assets: Loans to Individuals: Other Loans to Individuals: Auto Loans
    
https://fred.stlouisfed.org/seriesBeta/QBPBSTASLNINDVOLNINDCARLN

•Average Finance Rate of New Car Loans at Finance Companies, Amount of Finance Weighted 

https://fred.stlouisfed.org/series/RIELPCFANNM

•Average Amount Financed for New Car Loans at Finance Companies

https://fred.stlouisfed.org/series/DTCTLVENANM

•Total Vehicle Sales

https://fred.stlouisfed.org/series/TOTALSA

•Auto Inventory/Sales Ratio 

https://fred.stlouisfed.org/series/AISRSA 

•Population

https://fred.stlouisfed.org/seriesBeta/POPTHM

•API - Population Data

https://api.census.gov/data/2019/pep/charagegroups?get=NAME,POP&for=us:*&key={census_key}

•API 2 - Population Data

https://datausa.io/api/data?drilldowns=Nation&measures=Population








5:31