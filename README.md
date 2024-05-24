As part of mini project me with my team has developed a language identification tool for both text and speech data.
The text data is obtained from bhasha-abhijnaanam dataset that has the data in the form of unicode consists of 22 indian languages.
The step by step procedure to attain the aim of identifying the language accuarately is as follows:

# 1.Preprocessing
* Word Tokenization
* Stop word removal
* Snowball Stemming

# 2.Feature Extraction
TF-IDF (Term Frequency Inverse Document Frequency) : It is count vectorization technique used in extracting the features of text data.

# 3.Train Test split
This extracted model is now split into training and testing data of test data containing 20% and remaining 80% for testing

# 4.Model Selection
The model used here is Support Vector Machines (SVMs)

#After identifying the language for a given example test case, we have consider another situation for code switching that contains 2 or more languages in a given text.
#To correctly predict language in code switched text we have used a standalone library called langid to identify the language.
