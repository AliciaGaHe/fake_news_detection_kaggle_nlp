Here we solve the fake news detection problem proposed by kaggle using NLP.

data > data in csv format.
data_analysis > exploratory data analysis (EDA).
models > 1_tfidf_logistic_regression.ipynb > TF-IDF for NLP and logistic regression for classification.
models > 2_word2vec_word_embedding_neural_network.ipynb > Word2Vec for NLP and LSTM network for classification.
models > 3_spacy_word_embedding_neural_network.ipynb > SpaCy for NLP and bidirectional LSTM network for classification.

Conclusions:
* We get really good results with all models. So I would choose the simpliest one (model explained in 1_tfidf_logistic_regression.ipynb).
* Perhaps we are not working with the  best initial data, because we can classify the news using their subject only. Therefore, we could introduce noise in the initial data and after try again the models proposed above.