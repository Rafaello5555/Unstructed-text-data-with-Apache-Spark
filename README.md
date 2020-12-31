# Unstructed-text-data-with-Apache-Spark
The file sms.csv contains a selection of SMS messages which have been classified as either 'spam' or 'ham'. There are a total of 5574 SMS, of which 747 have been labelled as spam.

Data dictionary:

id — record identifier

text — content of SMS message

label — spam or ham (integer; 0 = ham and 1 = spam)

Data Preparation:
 First, we  need to prepare the SMS messages as follows:
1)remove punctuation and numbers
2)tokenize (split into individual words)
3)remove stop words
4)apply the hashing trick
5)convert to TF-IDF representation.


Built The  Model: The SMS data have now been prepared for building a classifier. Split the TF-IDF data into training and testing sets. Then we use the training data to fit a Logistic Regression model and finally evaluate the performance of that model on the testing data. The classifier won't be fooled by spam SMS with 95 % accuracy

