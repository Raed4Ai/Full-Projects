In this project I collected historical data for the Dow Jones stock index covering the period from 2011 to the end of 2020. 
The dataset includes features such as Volume, Open Price, High, Low, and the Target Closing Price to be predicted. In addition
to the stock data, I incorporated sentiment analysis by gathering financial and economic news related to the U.S.A market during 
the same time frame. These news articles were preprocessed and analyzed using a pre-trained FinancialBERT model to classify each
article’s sentiment as Positive, Negative, or Neutral. For each day I calculated the average sentiment score to create a new feature
called Day Sentiment which was then merged with the stock data.
Finally I built and trained an LSTM model to predict the closing stock price based on the time series data enriched with sentiment insights.

and achieved :
R squared score = 0.9014 .
MAE = 0.0317 .
