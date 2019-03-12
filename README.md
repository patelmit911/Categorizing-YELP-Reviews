# Categorizing YELP Reviews
Using Natural Language Processing and Python pipeline, built a model to classify yelp reviews with 92% accuracy. Later tried to improve the model using tfidf to extract features but the accuracy decreased so concluded that for this dataset, it's better to use the CountVectorizer for feature extraction.

I used the [Yelp Review Data Set from Kaggle](https://www.kaggle.com/c/yelp-recsys-2013).
Each observation in this dataset is a review of a particular business by a particular user.
The "stars" column is the number of stars (1 through 5) assigned by the reviewer to the business. The "cool" column is the number of "cool" votes this review received from other Yelp users. All reviews start with 0 "cool" votes, and there is no limit to how many "cool" votes a review can receive. The "useful" and "funny" columns are similar to the "cool" column.


