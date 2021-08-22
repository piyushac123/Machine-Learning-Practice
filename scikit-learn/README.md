## Scikit Learn
### Basics - Scikit-learn-basics.ipynb
- Import packages
- Loading Dataset
- Learning and Predicting
- Plotting image/data
- Type Casting
- Refitting and Updating parameters
- Multiclass vs Multilabel fitting

### Statistical Learning
- #### Machine Learning 
  - build prediction function that are useful in linking different observations, to classifying observations, or learning the structure in an unlabeled dataset.
  - statistical inferences : drawing conclusion on dataset at hand.
- #### Estimator
  - Any object that learns from data.
  - such as classification algorithms, regression algorithms, clustering algorithm or transformers.
- #### Supervised Learning 
  - Train data(x) - features for training
  - Train target(y) - target value for corresponding feature vector
  - Test data(X) - use predict(X) function to predict target variable value using trained estimator
  - Test target(Y) - prediction made by estimator on test data
  - Regression - goal is to predict continuous target variable
  - Classification - goal is to classify observations into set of finite labels
- ### Classification
  - K-nearest neighbour - given a new observation X_test, calculate distance from all train feature vector and assign mode of label of k nearest feature vector.
