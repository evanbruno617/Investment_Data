# Investment_Analysis
---
## Purpose
The purpose of this project is to extract financial data of stocks and compare their financial data with other stocks in their respective sector or industry.

## Extracting data
---
### Scraping
---
In order to know which stocks are in each sector the first step was to extract it from stockmonitor website 

![image](https://github.com/evanbruno617/Investment_Data/blob/main/Resources/Screenshot%202023-05-24%20at%208.45.19%20PM.png)

### Extracting Financial Data
---
Afterwards the financial data of each stock in each sector was extracted using a TD api key. All of the stocks financial data was combined into one csv file for each sector

![image](https://github.com/evanbruno617/Investment_Data/blob/main/Resources/Screenshot%202023-05-24%20at%208.47.48%20PM.png)

## Cleaning the data
---
After the financial data for each sector was extracted the data was cleaned by removing any uncessary columns are rows and transposing the dataset. The final dataset was sorted by peRatio and GrossmarginTTM

![image](https://github.com/evanbruno617/Investment_Data/blob/main/Resources/Screenshot%202023-05-24%20at%208.48.14%20PM.png)

## Conclusion
---
The final dataset allows the user to sort it and analyze whichever way they chose in order for them to perform their own financial analysis of stocks. The way I chose to sort it found the stocks that had the lowest peRatio but also had the high Gross Margin TTM which signies that they are undervalued but still highly profitable therefore implying it that it could be a good investment.

