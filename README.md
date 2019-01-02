### anly580-wine-project

_This project applies text classification methods for predicting a wine’s variety from its tasting note, or description. See [final_paper.pdf](https://github.com/kgedney/anly580-wine-project/blob/master/final_paper.pdf) for full details._ 

##### Dataset:
- Scraped data from https://www.thewinecellarinsider.com/
- Kaggle dataset from Wine Enthusiast magazine https://www.kaggle.com/zynicide/wine-reviews#winemag-data_first150k.csv

##### Models:
- Linear SVM 
- Simple pooling model based on [FastText](https://github.com/facebookresearch/fastText)
- LSTM
- Bidirectional LSTM

##### Results:
Test accuracies are below for the 28-class wine variety classification task. As a baseline, a majority class classifier would achieve baseline is 0.13 accuracy (Chardonnay). 

| Model  | Test Accuracy |
| ------------- | ------------- |
| SVM  | 0.83  |
| Simple Pooling  | 0.84  |
| LSTM  | 0.82  |
| Bi-LSTM  | 0.83 |


##### Word2Vec:
In a separate but related task, word embeddings are fit on the wine tasting notes using the Word2Vec algorithm. These reveal interesting clusters and relationships of wine-related words that can be explored here: http://kag.georgetown.domains/nlpproject/index.html 

