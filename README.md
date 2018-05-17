# Stock-Market-Analysis-on-S&P 500-companies 

The S&P 500 stock market index, comprises 505 common stocks issued by 500 large-cap companies and traded on American stock exchanges.

Combining s&p 500 data - 

The list of S&P 500 companies is obtained from Wikipedia by using Beautiful Soup . The data of each company from year 2000 upto 2016 obtained from yahoo and is getting saved in a folder named 'stock_dfs' . The Adj Close price of all companies are saved in 'sp500_joined_closes.csv'

Preprocessing data for machine learning - 

If the Adj Close price increases by certain percent , that stock is bought(1) . If it decreases by certain percent , that stock is sold(-1) , otherwise it is hold(0). The features for training the model are one day percentage change of Adj Close Prices . The labels are 1,0,-1 .
