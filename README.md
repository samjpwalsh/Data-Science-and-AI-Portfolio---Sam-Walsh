This portfolio provides a brief description of the Data Science and Artificial Intelligence projects that I have completed. Each project title links to it's repository, which houses the code and more in depth information about the project. 

# Data Science Projects:

## [Product Review Opinion Mining](https://github.com/samjpwalsh/Product_Review_Opinion_Mining)

   - NLP task to extract product features and assign positive or negative sentiment to those features.
   - Data source is Amazon reviews of various products
   - Spacy's NLP pipeline was used to first pre-process the data then identify nouns and noun phrases (potential features) along with adjectives (likely sentiment bearing)
   - Features pruned using Pointwise Mutual Information (PMI)
   - Sentiment analysed using Naive Bayes classification
   - The final output are product summaries, consisting of the extracted features and aggregate sentiment towards those features
   - The approach taken here was inspired by Hu and Liu, 2004 (https://www.cs.uic.edu/~liub/publications/kdd04-revSummary.pdf)

## [Decision Tree Classification](https://github.com/samjpwalsh/Decision_Tree_Classification)

- Decision tree classifier built from scratch using CART approach
- The algorithm parses a dataset, producing and clearly displaying binary decision tree
- This is tested on two seperate datasets and performance is evaluated using a confusion matrix and k-fold cross validation

## [Car Review Sentiment Analysis](https://github.com/samjpwalsh/Car_Review_Sentiment_Analysis)

- Supervised Learning Classification task to identify positive or negative sentiment in plain text car reviews
- Dataset includes labled reviews but has not been otherwise amended prior to the analysis
- Data is initially pre-processed, stopwords and punctuation removed and words stemmed
- Data is vectorized and sklearn's multinomial Naive Bayes model is trained, using a bag-of-words representation
- Model is extended to bigram and trigrams
- Accuracy is assessed using confusion matrices

## [Naive Bayes Spam Classifier](https://github.com/samjpwalsh/NB_Spam_Classifier)

- Supervised Learning classification task
- Dataset represents a pre-processed set of emails, with the first column representing the binary response variable (either 1 indicating spam, 0 otherwise). The remaining columns represent the presence of a particular word in the email
- Algorithm used for classification is Naive Bayes, using a binary bag-of-words model
- K-fold cross validation used to optimise the smoothing parameter, alpha

# Other AI Related Projects:

## Title
