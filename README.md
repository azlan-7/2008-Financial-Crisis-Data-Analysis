# 2008-Financial-Crisis-Data-Analysis
In this data project we will focus on exploratory data analysis of stock prices. Keep in mind, this project is just meant to practice your visualization and pandas skills, it is not meant to be a robust financial analysis or be taken as financial advice.

Note: You'll need to install pandas-datareader for this to work! Pandas datareader allows you to read stock information directly from the internet Use these links for install guidance (pip install pandas-datareader), or just follow along with the video lecture.


We need to get data using pandas datareader. We will get stock information for the following banks:

Bank of America
CitiGroup
Goldman Sachs
JPMorgan Chase
Morgan Stanley
Wells Fargo
** Figure out how to get the stock data from Jan 1st 2006 to Jan 1st 2016 for each of these banks. Set each bank to be a separate dataframe, with the variable name for that bank being its ticker symbol. This will involve a few steps:**

Use datetime to set start and end datetime objects.
Figure out the ticker symbol for each bank.
Figure out how to use datareader to grab info on the stock.
** Use this documentation page for hints and instructions (it should just be a matter of replacing certain values. Use google finance as a source, for example:**
