# Technical samples by Vladimir Bogdanov

### Python (numpy, pandas, scikit) data science stack, supervised and unsupervised learning, machine learning models exploration, statistical analysis. 
### There are some training notebooks I've prepared and used for data analysis and exploration of machine learning algorithms. 


## Sentiment Analysis of product reviews for Kaggle Competition | Classification problem

The problem is that sentiment analysis of the product reviews is needed for business use. The "customer" wants us to construct & evaluate the possible quality of such algorithm on a small test sample (only 100 records). No training data provided, so we need to find it somewhere in a good quality and size. Also since testing set has little number of samples, careful feature selection and model ensemble are necessary for high accuracy even after the training sample formation. General description and data are available on [Kaggle](https://www.kaggle.com/c/product-reviews-sentiment-analysis/).

My solution to this could be found here:[Github](https://github.com/VBogdanov1/VBogdanov1.github.io/blob/master/Notebooks/Kaggle_Sentiment_Analysis-InClassCompetition.ipynb). I'll use web parsing to form a sufficient training set of 10,000 records, then vectorise it and compare different classification techniques: separate models as well as their ensemble via VotingClassifier. 


## Binary Classification problem and Data Preparation

Predict Grant Applications is a knowledge competition on Kaggle. This task requires participants to predict the outcome of grant applications for the University of Melbourne.

Objective: for 38 indicators related to the grant application (the area of research of scientists, information on their academic background, the size of the grant, the area in which it is issued, etc.), to predict whether the application will be accepted.

My solution to this could be found here:[Github](https://github.com/VBogdanov1/VBogdanov1.github.io/blob/master/Notebooks/LogReg_and_Preprocessing.ipynb)

Full range of data exploration and preparation: 
- processing of missing values
- handling of categorical attributes
- stratification
- class balancing
- scaling

## Time Series Analysis: predicting Russian average monthly wages 

Based on Russian Federal State Statistics Service data (http://gks.ru) I've tried to predict future monthly wages. I've worked with Time Series data, using STL-decomposition, Box-Cox transformation, Dickey-Fuller test, correlograms, etc. in order to properly clear & transform the data and predict the values. 
 
Solution to this could be found here:[Github](https://github.com/VBogdanov1/VBogdanov1.github.io/blob/master/Notebooks/Time_Series_Analysis_RussianMonthlyWages.ipynb)

## Clustering and visualisation with PCA, t-SNE and MDS

Clustering is an approach to unsupervised machine learning. In this notebook I've just demonstrate its basic functionality using "digits" dataset (it is available [here](http://archive.ics.uci.edu/ml/datasets/Optical+Recognition+of+Handwritten+Digits).

Notebook could be found here:[Github](https://github.com/VBogdanov1/VBogdanov1.github.io/blob/master/Notebooks/Clustering_and_visualisation_via_sklearn.ipynb)


## Statistical analysis

