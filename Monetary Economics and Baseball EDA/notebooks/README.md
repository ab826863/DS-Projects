
# Correlation Analysis Monetary Economics and Baseball :baseball:
Here is our Milestone I repository for the University of Michigan MADS program. You will discover all the code and visualization of our exploratory data analysis.

## Project Description
Our project team have a two stage exploratory analysis. It aims to investigate the impact of various economic factors on the financial decisions of baseball teams and how financial decision affect their performance. Specifically, our objective is to explore how federal interest rates and major stock market indices affect baseball teams' payroll spending, subsequently impacting their hitting, pitching, and overall performance metrics. We will also assess the economic resilience of large market teams compared to the smaller ones. For reference, 8 of the last 10 teams to win the world series have had their payroll rank in the top 10 of the league’s highest payrolls. 

## Dataset Description
We have total of 5 different datasources for baseball, interest rates, and stock market indices.

**Data Source: Stathead** 
Stathead is a comprehensive sports statistics and research tool that provides in-depth data analysis and insights across various sports. It is part of the Sports Reference family, known for its detailed databases of sports history, records, and statistics. Regarding baseball performance statistics relevant to our project, it contains both hitting and pitching data for each team.

location: https://stathead.com/baseball/

Format: CSV

Access Mehtod: Direct Download

**Data Source: Baseball Prospectus**
Baseball Prospectus is a leading resource in the baseball community known for its in-depth analysis, statistics, and insights into the game. It is known for its publication, the Baseball Prospectus Annual, which features projections, analyses and essays on various aspects of baseball. For our project, we are utilizing payroll information from 2000-2020.

location: https://legacy.baseballprospectus.com/compensation/

Format: HTML -> Dataframe

Access Mehtod: BS4 Webscrape


**Data Source: SteveTheUmp**
SteveTheUmp.com is a niche website focused on the world of umpiring in baseball. It serves as the go-to resource for umpires and officiating fanatics. For our use case, it allows us to easily scrape payroll data, specifically for the years 1998, 1999, and 2021-2023.

location: https://www.stevetheump.com/Payrolls.htm

Format: HTML -> Dataframe

Access Mehtod: BS4 Web Scraping


**Data Source: Yahoo Finance API**
Yahoo Finance provides stock market data through its free API library integrated in Python. It covers historical stock market data for major indices such as the S&P 500, NASDAQ, and Dow Jones Industrial Average. . The dataset spans approximately 26 years, from 1998 to 2022, and consists of around 7000 daily records for each index. The data is constructed by the following features: date, open, close, high, and low, to provide an overview of the index performances.

location: https://pypi.org/project/yfinance/

Format: CSV

Access Mehtod: API

**Data Source: St. Louis FRED API**
The St. Louis Federal Reserve provides economic data through its FRED API, a widely used source for accessing economic statistics. Integrated easily with Python, it offers vast data, including the Federal Funds Rate and various other securities. For our project, the data extracted spans from 1998 to 2023, primarily focusing on the Federal Funds Rate data. This dataset allows for an in-depth exploration of monetary policy impacts over this time frame, containing daily and monthly records that offer insights into the economic conditions and policy decisions.

location: https://fred.stlouisfed.org/docs/api/fred/

Format: JSON

Access Mehtod: API

## Environment
Though it is collaborative project with different versions of Python environment used, we recommend using Python 3.8.12 or later versions. To run .ipynb(Jupyter Notebook), you would need Jupyter installed in your Python environment.

``` bash
pip install Jupyter
```

Following libraries and corresponding versions were used in this EDA project:

pandas           : 1.5.3
numpy            : 1.24.3
matplotlib       : 3.7.1
scikit-learn     : 1.2.2
seaborn          : 0.12.2
pandas_datareader: 0.10.0
scipy            : 1.9.1
statsmodels      : 0.14.1
yfinance         : 0.2.35
requests         : 2.31.0
lets_plot        : 4.2.0
bs4              : 4.12.2
re               : 2.2.1