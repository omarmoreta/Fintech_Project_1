# Fintech_Project_1
#### Stock Portfolio Analysis: this project compares the performance of portfolios that are composed of different assets and weights. It includes different financial calculations, tables, and Monte Carlo simulations. The analysis will be on past and future performance of the portfolios, as well as suggestions for improving that performance.

## How to run the project

1. Clone the project locally:

     ```git clone https://github.com/omarmoreta/Fintech_Project_1.git```
     
2. Open the project and install required dependencies:
    
     ```cd Fintech_Project_1```
     
     ```pip install -r requirements.txt```

3. Delete ```.example``` extension from the ```.env.example``` file on the top-level to convert to ```.env``` file and add your alpaca api and secret keys. If you do not have an account you will need to sign up to generate keys. Reference: [Alpaca API Docs](https://alpaca.markets/docs/introduction/).

4. Next open the ```Portfolios``` directory and run cells in each jupyter notebook for financial analysis.

# Backstory

> Why we did this
### - Eammon's real life portfolio as "jump off" point
> Method overall
### - In depth quantitative portfolio analysis.
### - Benchmark comparision.
### - "Under the hood" analysis of portfolio stocks
### - Clustering investigation for interaction between stocks

<br>

# Mike
# New Technologies/Libraries 
## 1. OpenBB terminal SDK
#### - Open source project, Bloomberg Terminal like data access & performance
#### - Uses publically available data sources as well as API access. Sources include Coinbase, FRED, Alpha Vantage
#### - Requires Python 3.8 or greater, pip install openbb
#### - https://docs.openbb.co/
## 2.  Riskfolio-Lib
#### - Portfolio optimization library using alogrithims and mathetmatical modeling
#### - pip install riskfolio
#### - https://riskfolio-lib.readthedocs.io/

<br>

# Eli

## Lets talk about risk
 What is <b>Risk</b>?  What is the context?

### Portfolio Risk
> ``` The possibility of losing money or missing out on investment goals and objectives ```

### How did risk factor into our portfolios?

> Risk plays an enormous factor in each of our investment portfolios.  You will see that some of our growth potential has to do with the level of exposure we have to specific industries.

> ``` How willing are you to lose it all? ```

### Return Spread
---
![Standard Deviation](Resources/Images/stddev.png)

### How does that translate over time?

![Returns](Resources/Images/returns.png)

## Class Betterment
---
### What are some ways to mitigate risk?

- Diversification
- Asset Allocation
- Risk Tolerance
- Hedging
- Time

<br>

# Omar

### Performance
According to the stock analysis of the stock portfolio, which was chosen based off the high market caps, the performance was very good between the years 2013-2023. The daily returns range was between 10 and -11 percent at the most high and low during this time, but daily returns stayed pretty tight around 2 and -2 percent for the portfolio. 

I think I got very lucky with the porfolio because the stocks were very closely correlated except for 3 stocks (CVS, IBM, and BA). Compared to the SP500, the portfolio doubled its returns during the same time. I think the long time horizon helped against the SP500 since it has to account for many more stocks across different sectors. I definitely could have diversified better but regardless of the stocks being closely correlated, it was helped by market trending higher during this time and it worked out in the porfolios favor.

### MonteCarlo
During the 500 MonteCarlo simulations for the next 10 years (using data from the previous 8 (2015-2013) Alpaca data limit) there is a 95% chance that an initial investment of 10000 in the portfolio over the next 10 years will end within the range of 25684.13 and 287672.74.

<br>

# Eamonn 

> Dividends

<br>

# Review 

> Q/A (Dave & Co.)
