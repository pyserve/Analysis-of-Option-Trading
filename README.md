# Analysis-of-Option-Trading
Option Trading Analysis and Visualizations

The business would like to predict any of the columns of data from July 30, 2021 based on the data for July 1 to July 29, 2023. So this is a predictive analysis activity. 

Scikit-learn is a great resource. https://scikit-learn.org/stable/index.html

The data has already been identified and acquired (see file attached), and your task is to apply the remaining stages of the data lifecycle and give your results as a group in a simple report file or Jupyter Notebook to this dropbox. 

You need not have a high accuracy of your prediction model to get good academic grades, however high accuracy results would be very interesting to me.

To calculate accuracy, compare the true values from July 30 with your predicted values.

Feature descriptions:

**symbol:** the underlying stock

**date:** the dataset date

**adjusted close:** the closing price of the underlying stock after extended trading session

**stock price:** the closing price of the underlying stock

**option symbol:** string combining other fields identifying the option

**expiration:** date that the option expires

strike: the price that the option gives you the right to trade the underlying stock

**call/put:** whether the option is a Call (right to buy underlying stock) or a Put (right to sell underlying stock)

**ask/bid/meanprice:** market prices of the option (last offer to sell, last offer to buy, and the average of the two prices)

**iv:** how fearful the market is of a market crash or severe decline in prices

**volume:** number of contracts traded today

**open interest:** number of contracts currently held

**greeks (delta, gamma, vega, theta, rho):** see Investopedia for descriptions https://www.investopedia.com/terms/o/option.asp


**Steps in Data Analysis**
	
1. Data Extraction
2. Data Validation and Cleansing
3. Data Aggregation and Representation
4. Data Analysis
5. Data Visualization
6. Utilization of Analysis Results
