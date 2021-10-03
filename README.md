# text_classification
Text Classification

Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

Objective 
To build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.

Steps 
1. Identify URL in the test and remove it
2. Remove all punctuation
3. Remove stop words (the, a, an, in, ...)
4. Count unique words (collections)
5. Splitting training and validation set
6. Create word index
7. Replacing text into series of number
8. Make every sentences/ text same length
9. Reversing keys values in word index dict, for decoding later

Model training 
1. Create LSTM model
2. Naive Bayes Classifiers
