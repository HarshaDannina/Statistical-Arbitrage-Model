# Statistical-Arbitrage-Model
Machine learning model to predict stock data for a year

 ![alt text](https://cdn-images-1.medium.com/max/800/1*w_gWr6Q1sACAMzxhLnDFvg.png "Statistical Arbitrage Model")
 
 
**Statistical Arbitrage**: For a family of stocks, generally belonging to the same sector or industry, 
there exists a correlation between prices of each of the stocks. 
There, though, exist anomalous times when for a small period of time, the correlation is broken. 
But the market self corrects in some time and the correlation is re-established. 
During this small window of time when correlation is anomalous, there exists a money-making opportunity for quantitative traders. 

 ![alt text](https://cdn-images-1.medium.com/max/800/1*IPP7m_tu5VwSLAr2XIwaiA.jpeg "You Need an Algorithm, Not a Data Scientist
")

First, you have many types of data The stock market is like candy-land for any data scientists who are even remotely interested in finance. 
Hat you can choose from. 
You can find prices, fundamentals, global macroeconomic indicators, volatility indices, etc… the list goes on and on. 
Second, the data can be very granular. 
You can easily get time series data by day (or even minute) for each company, 
which allows you think creatively about trading strategies. Finally, the financial markets generally have short feedback cycles. 
Therefore, you can quickly validate your predictions on new data. Here is the equity data of stocks listed on NSE over 2016 and 2017.

 **Dataset (https://drive.google.com/file/d/1kyNXxSM-_MSW4kSUJ90HlPQaxPCVti5L/view)** 
 
 From the data we extracted "20MICRONS" data and stored in csv file. The code for ectraction is in [20Micron.py](https://github.com/HarshaManoj/Statistical-Arbitrage-Model/blob/master/20Microns.py)
 
 After then the project guide is available in [PPT](https://github.com/HarshaManoj/Statistical-Arbitrage-Model/blob/master/STATISTICAL%20ARBITRAGE%20MODEL.pptx)
 
 I did time series analysis to seperate 2016 & 2017 reports as Training and Testing data respectively.
 
 Then did regression with **TheilSenRegressor**.
 
 The prediction graph over 2017 is plotted with an accuracy of 98.2%
 
 ![alt text](https://github.com/HarshaManoj/Statistical-Arbitrage-Model/blob/master/TheilSenRegressor-98.2.png "Prediction plot")
 
Here is the detailed blog in Medium
https://medium.com/@harshamanoj/statistical-arbitrage-model-256d1bc9b801
