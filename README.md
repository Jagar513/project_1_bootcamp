# Automotive Car Loan Analysis

The attached analysis dives in to Auto Loan patterns over a 10-year period, broken down by quarter; to answer the questions below.

    1.	Are the number of people taking out loans increasing or decreasing?
    
    2.	Has the number of people purchasing cars increased or decreased?
    
    3.	Do trends in loan approvals correlate with trends in car purchases?

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
