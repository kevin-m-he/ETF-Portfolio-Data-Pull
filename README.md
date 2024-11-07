# ETF-Portfolio-Data-Pull
Python scripts to generate markowitz portfolio allocation datasets on Vanguard's 76 available etfs

ETFs were manually copied from Vanguard's website https://investor.vanguard.com/etf/list#/etf/asset-class/month-end-returns and placed into vanguard_etfs.csv

vanguard_etf_data_pull.ipynb retrieves etf price history and information from yahoo finance

m_portfolio_allocation.ipynb performs Markwotize Portfolio Allocation for 50,000 portfolios and generates csv's that are used in the tableau dashboard below.

Link to the Tableau Dashboard: https://public.tableau.com/views/All-ETFPortfolioOptimizer/All-ETFPortfolioOptimizer?:language=en-US&:display_count=n&:origin=viz_share_link

Spark Fund.xlsx is an example of a modern portfolio allocation, it is NOT FINANCIAL ADVICE. Only another example like the tableau dashboard of what is possible with the python script outputs. Edit the tickers within the script to make your own ETF!! :D

Scripts inspired by: https://www.machinelearningplus.com/machine-learning/portfolio-optimization-python-example/
