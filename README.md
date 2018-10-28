# Hotel_Review_NLP
Used Bag of Word Model to predict if the Review is Positive or Negative


### Cleaning the Dataset 
  - Removing all the Puntuations
  - Converting the words into lower case
  - Splitting the string into a list
  - Removing all the useless words like a the called stopwords
  - Applied stemming to reduce dimension eg : loved--->love
  - Converted the list back to string
  - Appended the string back to corpus
  
### Creating a Bag of Words Model
  - Used CountVectorier to convert corpus to a table where each row = 1 review and each column corresponds to each word
  - Removed rare words my setting max_features to 1500 out of 1700
  
### Used Gaussian Naive Bayes Classifier 
