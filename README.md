# SKLearn-Stock-Analysis

- Implement Log Loss, Precision, Recall, Accuracy, hamming loss
## Datasets
I will test on 1 to 500 stocks, slowly incrementing. 
The end goal is to find the model that performs bests on the largest dataset.
-1 stock
-5 stocks
-10 stocks
-25 stocks
-50 stocks
-100 stocks
-250 stocks
-500 stocks
## Feature Selection
I will use increasily complex feature sets.
All data will be normalized.
1) The first selection will be the base stock information (6 features)
2) The second selection will be the stock plus technical indicators (90 features)
3) The next selection series will be the stock data saved sequentially.
- 30 features (5 days of information)
- 60 features (10 days of information)
- 150 features (25 days of information)
- 300 features (50 days of information)
- 600 features (100 days of information)
4) The next selection series will be the stock data + technical indicators + s&p 500 stock information technical indicators + BND information (186 features)
5) The final selection series will be the stock data + technical indicators saved sequentially 
- 450 features (5 days of information)
- 900 features (10 days of information)
- 2250 features (25 days of information)
- 4500 features (50 days of information)
- 9000 features (100 days of information)
## Models to Train
### Linear Models
- LinearRegression Imp
- Ridge Imp
- Lasso Imp
- Lars Imp
- Lars Lasso Imp
- Perceptron
- Linear Discriminant Analysis
- Quadratic Discriminant Analysis
### Mid Models
- SVC
- SGD 
- Nearest Neighbors set to kdtree
- Nearest Centroid
- KNeighborsTransformer
- Gaussian Process Classification 
- Partial Least Squares transformer and regressor.
### Naive Bayes
- Gaussian Naive Bayes
- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- Complement Naive Bayes
- Categorical Naive Bayes
### Ensembles
- Gradient-boosted trees
- Bagging classifier
- Voting Classifier (hard and soft)
- Stacking Classifier
- AdaBoostClassifier
