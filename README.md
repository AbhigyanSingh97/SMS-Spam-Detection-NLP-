# SMS-Spam-Detection-NLP-

Description : Worked with a dataset containing of 5500 sms datas approximately.

Language: Python

Approach: Data was a text file,so used pandas to seperate the data in two columns(label and messages) 

The messages column had preprocessing done on it.
1.tokenization
2.removal of stopwords
3.lemmatization

For Logistic Rgression and MultinomialNB models Count vectorizer was done and on the output of it Tfidf Transformation was done.

For LSTM and GRU models the input data was one hot encoded and the data was padded with pre padding of 20.

Algorithm used: Logistic Regression, MultinomialNB, LSTM and GRU.
