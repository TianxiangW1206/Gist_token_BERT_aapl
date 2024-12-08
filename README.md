Gist_token_ver2 has the updated code using Gist token +BERT, reaches f1-score of 0.7259.

Gist_token_model.ipynb contains the saved model of gist token and the downstreamming taskd of predicting stock price change, using Gist token + BERT + Random forest

dataset used(Apple bews and stock, cleaned and processed): 
train_stock_news.csv  and  test_stock_news.csv 

downstreamming:
Gist_token_model.ipynb contains the stock price prediction using gist token compression, achieving the accuracy of 0.75, and weighted avg f1-score of 0.72

CSE291Project_downstream.ipynb contains the stock price prediction using BERT only, where the weighted avg f1-score is only 0.51
