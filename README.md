Project Overview:
  
  - Risk analytics project in the banking domain, using SQL and EDA to understand and minimize financial risk in customer lending decisions.
  - The goal is to explore customer data, identify key risk factors, and derive insights that can help in making more informed lending decisions.

Project Structure:

  -  SQL Part/ (SQL Part 1.ipynb, SQL Part 2.ipynb) · EDA Part/ (EDA Part 1.ipynb, EDA Part 2.ipynb, customers_df.csv) · dataset/ (banking-clients(date formated).csv) · README.md

Description:

  - SQL Part:
      - Contains analytical SQL queries on customer financial data. The raw dataset was uploaded to a PostgreSQL database in SQL Part 1.ipynb using pgAdmin / pandas.
      - In SQL Part 2.ipynb, the table was modified and analyzed using SQL queries to explore key financial metrics and risk patterns, with query outputs displayed below each result. Each question is followed by its corresponding SQL query (in markdown) and a screenshot of the output displayed below it and key insights summarizing the findings.

  - EDA Part:
      - Exploratory data analysis using Python.
      - The notebooks import the table from the SQL database via pandas, perform cleaning and preparation (shape/info, merges, missing-value checks, descriptive statistics etc), and run univariate, bivariate and multivariate analyses.
      - EDA Part 2.ipynb extends the analysis using the exported customers_df.csv
      - Tools: Python · pandas · numpy · matplotlib · seaborn
  
  - dataset: Raw dataset

- Author:

  Prajwal Rahangdale
