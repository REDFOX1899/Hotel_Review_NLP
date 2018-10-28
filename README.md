# Hotel_Review_NLP
Used Bag of Word Model to predict if the Review is Positive or Negative


Cleaning the Dataset 
  1.Removing all the Puntuations
  2.Converting the words into lower case
  3.Splitting the string into a list
  4.Removing all the useless words like a the called stopwords
  5.Applied stemming to reduce dimension eg : loved--->love
  6.Converted the list back to string
  7.Appended the string back to corpus
  
Creating a Bag of Words Model
  1.Used CountVectorier to convert corpus to a table where each row = 1 review and each column corresponds to each word
  2.Removed rare words my setting max_features to 1500 out of 1700
  
 Used Gaussian Naive Bayes Classifier 
  
