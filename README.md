# CFM101 Team Project #
A Python program that takes a list of stock tickers and generates a portfolio based on our analysis of statistical measurements, and portfolio theory. Based on the CFM101 course project and competition.

## Summary ##
The generator first takes a list of stock tickers, and then... 
* Filters the tickers based on predetermined characteristics (e.g. specific market, minimum number of monthly trading days)
* Obtains the daily percentage returns of each stock's closing prices on a specific time interval
* Calculates measures such as correlation and beta to determine individual and portfolio volatility 
* Tests different strategies by calculating deviation measures to determine the most volatile portfolio  

Notable Python libraries utilized include:
* YFinance
* NumPy
* pandas
* Matplotlib

## Competition ##
The length of the competition was 3 days. Our generator created a portfolio that yielded a ~3% return, which placed us as the runner-up in the project competition!

*Created in collaboration with my team members Johnson Xu and Bodhana Sivagurunathan.*
