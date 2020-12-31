# Unstructed-text-data-with-Apache-Spark
The file sms.csv contains a selection of SMS messages which have been classified as either 'spam' or 'ham'. There are a total of 5574 SMS, of which 747 have been labelled as spam.

Data dictionary:

id — record identifier

text — content of SMS message

label — spam or ham (integer; 0 = ham and 1 = spam)

Data Preparation
 First, we  need to prepare the SMS messages as follows:
1)remove punctuation and numbers
2)tokenize (split into individual words)
3)remove stop words
4)apply the hashing trick
5)convert to TF-IDF representation.






