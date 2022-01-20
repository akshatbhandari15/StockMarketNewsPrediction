# StockMarketNewsPrediction
I use the dataset from https://www.kaggle.com/aaron7sun/stocknews to build a Transformers based classification model which predicts whether the stock market would rise or fall on the basis the top news headlines of that day.

The dataset contains top 25 headlines of each date and the corresponding movement of DJIA as the label.

I had to reduce each row of the dataset to atmost 512 words as BERT models only take 512 words as input at a time.
