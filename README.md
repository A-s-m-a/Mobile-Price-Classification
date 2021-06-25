# Mobile-Price-Classification
A Machine Learning Project to predict the Price Class of a Mobile based on its Specifications

#### We studied the entire dataset we had for the topic on Kaggle found all the important information on the data we were going to work on 

- The Data Preprocessing
  1. Description of Data 
  2. Info about the data
  3. The Correlation between the attributes
  4. The attributes that are most correlated with the Price Range ( Our target )
  5. Outlier Analysis of Non-categorical Data
  6. Histogram of all the attributes
  
#### Next we tried a total of 9 Machine Learning Algorithms for each we made a confusion matrix and the most contributing features were found

1. Logistic Regression
2. Decision Tree(gini)
3. Decision Tree(entropy)
4. Random Forest
5. KNN
6. Naive Bayes
7. SVM
8. GBC
9. XGB

#### We compared the accuracies of all the models and found that SVM is the best classifier for our project
#### We then performed EDA Analysis on the best 8 feautres that we found in SVM
#### Using the test data we then used our model to predict values for the unseen data 
#### Made a classification report for our SVM Model
#### Finally Applied LDA for Dimensionality Reduction and plot the our values on a graph to visualize the proper distrubtion of our price ranges
