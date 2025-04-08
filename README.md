This tool is designed to accurately identify languages from text and speech data, leveraging the Bhasha Abhijnaanam dataset, which includes 22 Indian languages. The process involves the following steps:

##1. Preprocessing
Word Tokenization: Split text into individual words.

Stopword Removal: Eliminate common, uninformative words.

Snowball Stemming: Reduce words to their base form using the Snowball Stemmer.

##2. Feature Extraction
TF-IDF (Term Frequency-Inverse Document Frequency): A statistical method to extract relevant features, capturing the importance of words within the dataset.

##3. Train-Test Split
The dataset is split into 80% training and 20% testing data to train and evaluate the model.

##4. Model Selection
Support Vector Machines (SVMs) are used for classification, providing an effective approach for language identification.

##5. Code Switching
For code-switched text (where two or more languages are used together), the langid library is employed to detect the individual languages present in the input.
