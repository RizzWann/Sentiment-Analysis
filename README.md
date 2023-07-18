# Sentiment-Analysis
Sentiment Analysis
(a) Prepare a Roman Urdu dataset for multiclass classification (sentiment analysis)
Scrap roman Urdu tweets from Twitter using some Roman Urdu keywords on some topic of your choice.
Scrap around 500 tweets on your topic and label them into five classes (very negative, negative, neutral,
positive, very positive).

(b) Build sentiment classifiers using bag of words and ngram model for the dataset created in part (a).
You can use scikit-learn (machine learning tool for python) for using implementations of classification
algorithms. Perform multiclass classification. For multi class you have to classify the tweets into one of
the five categories (very negative, negative, neutral, positive, very positive).
Split the data into train and test set by using “train_test_split(DataSet)” of scikit.
Implement following feature extraction methods.
Bag of words based on raw counts
Bag of words based on TfIDF
ngrams (unigrams, bigrams, trigrams)
