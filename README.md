# Stock analysis
![image](Tech/1577053187174.jpg)
---
The members in this group are: 
1. Alison Andrade (@alisonands2000)
2. Sourav Kumar (@s0uravk)
3. Sakina Jaffri (@SakinaJaffri)
4. Kunal Khirwar (@kunalkhirwar)

This repo contains 4 folders that contains the files with the Jupyter notebooks that extract the required data for analysis in each sector. These Jupyter notebooks use AlphaVantage and Yahoo Finance modules to extract the data for the ticker symbols for their respective sectors. The outputs of the csv files that will be merged used for the final analysis. 

Packages used: 
  - For data analysis: AlphaVantage, yfinance
  - Visualizations: Matplotlib, Plotly, Seaborn, hvplot
  - Analysis: Pandas, Numpy, Scipy

This project goes over the following:
- Stock price analysis within various sectors as well as industries and visualize the data.
- Furthermore, it gives volume of stock traded in each sector and each industry.
- And find any correlation within sectors to check if one stock was affected by another stock within the sector.
- As well as calculates moving average in each sector and find the most traded stock in each year.

This report answers the following questions:
1. Which stocks are best performing in their respective sectors? (Sourav)
2. [Which ticker performed the worst/best by year?](Question 1 & 2.ipynb) (Sourav) 
3. How did each sector perform for each year regarding average volume? (Kunal)
4. Find a correlation between industries within each sector. (Kunal)
5. What does the moving average look like for each industry? (Alison)
6. Which stock was most traded in each year? (Alison)
7. What is the allocation of portfolio for each Sector? (Sakina)
8. What is the allocation of portfolio for each Industry?  (Sakina)

Visualizations
1. Which stocks are best performing in there respective sectors? (Sourav)
    - Closing price (Line chart, 4 graphs (top performing stock per industry))
2. Allocation of portfolio for each Industry?  (Sakina)
    - Volume (% total volume Pie chart, industry) – 4 Pie charts
3. What was the correlation between different sectors? (Kunal)
    - correlation (closing prices, between sectors)
4. Which sector has the best moving average in there respective industry? (Alison)
    - Grouped bargraph: price values per sector (xlabel: sectors) --> moving average (1 graph)
5. Which ticker was most traded in each year? (Alison)
    - Answered by bar graph(name of stocks in each sector as xticks and height of the bar will be the average of volume)
6. Which ticker performed the worst/best by year? (Sourav)
    - Best performing stock per sector, compare over all sectors (Bar graph) --> x: year, y: price change ((open-close)/close * 100)
7. How stocks performed over each sector for each year? (Kunal)
    - Best performing stock per sector, compare over all sectors (Bar graph) --> x: year, y: volume (16 graphs total, 4 per year for each sector)
8. Allocation of portfolio for each Sector? (Sakina)
    - Volume (% total volume Pie chart, Sector) – 1 Grand Pie chart



## Work breakdown strucutre**
[Member #] 
Each member will perform data collection for given sectors:
Alison: Tech
Sourav: Banking/Finance
Sakina: Healthcare
Kunal: Automobiles

1. Pulling Data from AV
2. Cleaning Data
3. Merging Data
4. EDA
5. Data Visualization
6. Analysis

## Datasets used: 
- [AlphaVantage package](https://www.alphavantage.co/documentation/) (Alison)
- Yahoo Finance (Sourav)

Alternatives:
- [Market Data](https://docs.marketdata.app/api/)

## Code snippets
`!pip install alpha_vantage`

## Limitations
- Limited industries and limited companies per industry
