# AG News Classification
AG is a collection of more than 1 million news articles. 
News articles have been gathered from more than 2000  news sources by ComeToMyHead in more than 1 year of activity. 
ComeToMyHead is an academic news search engine which has been running since July, 2004. 
The dataset is provided by the academic comunity for research purposes in data mining (clustering, classification, etc), 
information retrieval (ranking, search, etc), xml, data compression, data streaming, and any other non-commercial activity. 
For more information, please refer to the link http://www.di.unipi.it/~gulli/AG_corpus_of_news_articles.html .

The AG's news topic classification dataset is constructed by Xiang Zhang (xiang.zhang@nyu.edu) from the dataset above. 
It is used as a text classification benchmark in the following paper: 
Xiang Zhang, Junbo Zhao, Yann LeCun. Character-level Convolutional Networks for Text Classification. 
Advances in Neural Information Processing Systems 28 (NIPS 2015).

# Model 
Using bidirectional will run our inputs in two ways, one from past to future and one from future to past and what differs this approach from unidirectional is that in the LSTM that runs backwards we preserve information from the future and using the two hidden states combined we are able in any point in time to preserve information from both past and future.

# Results
Recall  is 0.91
Precision  is 0.91
Accuracy  is 0.91
