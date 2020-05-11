# DS3001FinalProject
Data Sources

Tweet Data: https://github.com/yumoxu/stocknet-dataset

Contains tweet, the userID, and the time that the tweet was created from January 2014 - 2016. 


Financial Data: https://www.tradingview.com/

Tableau Files

The final dashboard is in the Stocks Combined Tableau File

### tweet_data.xlsx
contains tweets for JPMorgan (JPM), 3M (MMM), and Bank of America (BAC) from January 2014 to December 2015
##### details:
* text: contents of tweet
* created_at: timestamp of tweet
* user_id_str: user id of tweeter
* symbol: corresponding stock (ticker code)
* source: Tweet Data: https://github.com/yumoxu/stocknet-dataset

### text_cleaning.ipynb
contains simple python script for converting tweet text data from array to string
