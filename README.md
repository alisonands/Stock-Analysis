# Stock analysis
![image](Tech/1577053187174.jpg)
---
The members in this group are: 
1. Alison Andrade (@alisonands2000)
2. Sourav Kumar (@s0uravk)
3. Sakina Jaffri (@SakinaJaffri)
4. Kunal Khirwar (@kunalkhirwar)

This repo contains 4 folders that contains the files with the Jupyter notebooks that extract the required data for analysis in each sector. These Jupyter notebooks use AlphaVantage and Yahoo Finance modules to extract the data for the ticker symbols for their respective sectors. The outputs of the csv files that will be merged used for the final analysis. 

| **Automobiles**          | **Healthcare**                   | **Technology** | **Finance**      |
|--------------------------|----------------------------------|----------------|------------------|
| Semiconductors           | Medical Instruments and Supplies | Semiconductors | Credit Services  |
| Auto & Truck Dealerships | Healthcare Plan                  | Software       | Asset Management |
| Auto Parts               | Biotechnology                    | Consumer Tech  | Insurance        |
| Auto Manufacturers       | Drug Manufacturers               | Info Tech      | Mortgage         |

Packages used: 
  - For data extraction: [AlphaVantage package](https://www.alphavantage.co/documentation/), yfinance
  - Visualizations: Matplotlib, Plotly, Seaborn, hvplot
  - Analysis: Pandas, Numpy, Scipy

This report answers the following questions:
1. Which stocks are best performing in their respective sectors? (Sourav)
2. Which ticker performed the worst/best by year? (Sourav) 
3. How did each sector perform for each year regarding average volume? (Kunal)
4. Find a correlation between industries within each sector. (Kunal)
5. What does the moving average look like for each industry? (Alison)
6. Which stock was most traded in each year? (Alison)
7. What is the allocation of portfolio for each Sector? (Sakina)
8. What is the allocation of portfolio for each Industry?  (Sakina)


Alternatives:
- [Market Data](https://docs.marketdata.app/api/)

## Code snippets
`!pip install alpha_vantage`
`!pip install yfinance`

## Limitations
While our analysis provides valuable insights, it is essential to acknowledge certain limitations. The data used in the analysis represents a small fraction of the entire stock market, and should be acknowledged as a limitation, as this is not fully representative of the entire market.
Factors such as market sentiment, geopolitical events(i.e. The war in Ukraine, 2022), and unforeseen circumstances may also not be fully captured in our methodology.
