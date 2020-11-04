# spam_sms_classifier
This project classifies whether a short message is spam or not.

# DataEngineering Steps
1. In the very first step the dependent & Independent Fetures are separated
2. In the second step the texts are precrocessed
   - everyting which are not alphabetic or numeric are removed.
   - converted all the words to lowercase
   - all extrea spaces are removed
   - using Stemming technique base word of each word is generated
 3. Used K-Fold crossvalidation to find optimum max_feature value for CountVectorizer
 4. Used K-Fold crossvalidation to find optimum ngram_range value for CountVectorizer
 5. Used K-Fold crossvalidation to find optimum alpha value for MultinomialNB
 6. Created the Bag-of-Words using CountVectorizer of Sklearn
 7. Trained the Naive Bayes model using our data then tested using test data.
 





