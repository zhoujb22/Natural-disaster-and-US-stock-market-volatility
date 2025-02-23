# Natural-disaster-and-US-stock-market-volatility

## 1. Introduction

Natural disasters are significant events that disrupt human lives, infrastructure, and economies. Their impacts extend beyond the physical and humanitarian toll, reverberating through financial systems, including stock markets. As the frequency and intensity of disasters such as Floods, Tropical Cyclones, and Severe Storms increase—likely exacerbated by climate change—understanding their economic consequences becomes ever more crucial. While broad market indices may offer insights into overall market stability, industry-specific analyses can reveal vulnerabilities and resilience within sectors closely tied to regional and disaster-specific factors.

This project explores the financial implications of natural disasters by examining stock price movements across industries in the U.S. Using data from the NOAA Billion-Dollar Disaster Database and stock market datasets, our research aims to quantify the abnormal returns experienced by companies in the real estate, utilities, and healthcare sectors during and after disasters. By analyzing disasters with varying geographic and economic footprints, such as Floods, Tropical Cyclones, and severe storms, we aim to provide actionable insights into disaster-specific market responses and their impact on investor behavior.

## Research Question

What are the immediate and short-term financial impacts of extreme natural disasters, such as **Floods, Tropical Cyclones, and Severe Storms** on the stock prices of U.S. companies, and how do these impacts vary across industries?


### Motivation

Our motivation for this study stems from the need to:

1) **Understand Localized Impacts:** Industries like real estate and utilities are inherently tied to specific regions, making them highly sensitive to localized disasters. A Flood in Florida or a Tropical Cyclone in Texas, for example, could directly impact property values, infrastructure, and revenue streams for companies headquartered in those areas.

2) **Inform Investment Decisions:** Identifying patterns in stock price movements during disaster periods can help investors and portfolio managers make more informed decisions about risk and diversification strategies.

3) **Support Policy Development:** Insights from this research can guide policymakers in designing resilience measures, such as improved disaster preparedness and industry-specific support mechanisms.

### Methodology

To analyze the financial impacts of natural disasters on industry-specific stock performance by:

1) Quantifying **abnormal returns (AR)** and **cumulative abnormal return (CAAR)** for companies during disaster periods, based on **event study** methodology.

2) Comparing the responses of different industries (e.g., real estate, utilities, and healthcare) to specific disaster types (Floods, Tropical Cyclones, and Severe Storms).


## Data Sources

**Natural Disaster Data:**
1) NOAA Billion-Dollar Disaster Database, detailing disaster type, location, and economic costs.
    - The disaster data of different states are from the .csv file in Location-Based Data.

**Stock Market Data:**
1) Daily price data for companies in the S&P 500, categorized by industry.
    - Daily price data for companies are from yahoo.
    - The industry information are from the S&P_500_companies.csv.
2) S&P 500 index data for calculating market returns.
    - S&P 500 index data are from S&P500_index.


# Authors

This project was initially conceived by Jinbo Zhou as part of a course assignment for ECON323 at the University of British Columbia (UBC) from September 2024 to December 2024. The project, along with the primary research approach, was developed by Jinbo and completed by a group consisting of Jinbo Zhou, Michael Li, Siya Kuhu Shumbhan, and Manan Shah. However, due to time constraints during the course, the completion of the assignment was limited. In February 2025, Jinbo enhanced the project by providing more detailed explanations, visualizations, and subsequent analyses, improving the overall completion of the assignment. This version was finalized in Tsinghua University in February 2025.

# References

1. NOAA Billion-Dollar Disasters Database: https://www.ncei.noaa.gov/access/billions/
2. S&P 500 Index Data: https://www.nasdaq.com/market-activity/index/spx/historical?page=1&rows_per_page=10&timeline=y10
3. Market Yield on U.S. Treasury Securities at 10-Year Constant Maturity, Quoted on an Investment Basis: https://fred.stlouisfed.org/series/DGS10
4. Yahoo Finance API for Historical Closing Prices of S&P 500 Companies:
- Python package: https://pypi.org/project/yfinance/
- Documentation and stock data retrieval: https://finance.yahoo.com/