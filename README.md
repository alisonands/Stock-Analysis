# Stock analysis
![image](1577053187174.jpg)
---

This project talks about 
1. Stock analysis within sectors (4 industries per sector, 5 stocks per industry): 
  - Sourav: Banking - Mortage, Insurance, Asset Management, Credit Services
  - Kunal: Consumer Discretionary - Auto & truck dealerships, Auto Parts, Auto manufacturers, Semiconductors
  - Sakina: Healthcare - Medical Instruments & Supplies, Healthcare plans, Biotech, Drug Manufacturers
  - Alison: Tech - Semiconductors, Software, Computer hardware, Communication Equipment (Telegram, Zoom)
2. We will look at their performance/trends before Covid-19, during Covid-19 and after Covid-19.
3. We will also look for other factors that impacted the stock prices.

The analysis we're going to do is .. 
1. We will look for the best and worst performing industry. 
2. Based on the best and worst performing industries, we will look at the best and worst performing stocks.
3. Find a correlation between volume and average open price.

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

The questions we're going to answer are: 
1. What would be the best industry to invest in?
2. What industry is the most resilient to pandemic?
3. Is there a correlation between the 4 industries?

## Members of the group

The members in this group are: 
1. Alison Andrade (@alisonands2000)
2. Sourav Kumar (@s0uravk)
3. Sakina Jaffri (@SakinaJaffri)
4. Kunal Khirwar (@kunalkhirwar)

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
