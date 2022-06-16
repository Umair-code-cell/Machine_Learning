# Machine_Learning

## Introduction
The purpose of this project is to comprehensively assess three different learning models in order to comparatively analyze their significance & Extensive experimental applications. 

## Method
All the models have been developed by implementing Python programming in the
Jupyter notebook. The development of the models started  by following the common
procedure of Machine Learning:

1) Importing Data: We imported the dataset using Pandas library.


2) Splitting Data: We split our dataset into a development set and a test set, The
development set consists on 85% of data while test set consists on 15% of
data. The split of the dataset is performed by using SKlearn library which
allows the shuffle of the data automatically. The preprocesssing procedure was
trivial in our case so we decided not to implement it.

3) Visualizing Data: To visualize the results we achieved and the learning curves
throughout the development of the project we used Matplotlib library .

4) Hyperparameter Tuning: For the optimization of the parameters we ran a grid
search using the tools provided by SKlearn. We preferred this tool as it has
a feature with the possibility to parellelize the search, even if it provides less
flexibility on the results.

5) Validation method: To validate our model we used k-folds cross validation. We
chose K=5 in such a way that we are left with 80% data as a training set and
20% data as a validation set. As we get the scores of all the k-folds, we
calculate the mean of the score over all the k-folds. We report the variance in
the graph.

6) Model Assessment: The assessment of the model was carried out using
hold-out method. Thus, the assessing of the selected model has been done on
the overall test set.

## Models
1) Keras Neural Network

2) SKLearn Support Vector Regressor

3) SKLearn K-Nearest Neighbor Regressor

