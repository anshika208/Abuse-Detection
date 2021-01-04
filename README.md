# abuse-detection
this project uses 2 most commonly used languages i.e. DEVANAGIRI  and ENGLISH tweets for training our model.  

# preprocessing data
the tweets obtained are first cleaned by removing stopwords , punctuations , special characters , urls etc. Stopwords for devanagiri tweeets are present in abusestopword.txt file and is made manually. the tweets after cleaning were manually classified as 0 or 1 indicating it is abusive or not. lemmatization , stemming and tokenization were used for the input data to make it suitable for training. 

# model creation
bag of words and tfidf were used to convert data into machine readable form. bag of words and tfidf were then fed on logistic regression , naive bayes , random forest classifiers .
for devanagiri tweets two methods of cleaning and training were used. one is in hindi_cleandata and in other files devanagiri tweets are converted first into english and then cleaned and trained.
