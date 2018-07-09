# Udacity Captone Project
# Toxic Comments Challenge from kaggle
Project Overview 
 
Comments that are toxic, such as threats, obscenity, insults, and identity-based hate, are everywhere on the Internet. The large number of toxic comments have prevented people from participating in discussions they are interested in and they have led to communities either limiting or restricting comments altogether. A model that is capable of detecting these types of comments could hopefully help online discussions become more productive and respectful. In the paper Ex Machina: Personal Attacks Seen at Scale the authors discuss solving a similar problem initially using logistic regression and multi-layer perceptrons and planned to in the future use LSTM models. This project is based off the kaggle competition ​Toxic Comment Classification Challenge Problem Statement 
 
The problem is to build a model that can detect and classify different types of toxicity in comments. Given a list of comments the model will predict the probability that each comment is toxic. It will predict 6 different probabilities one for each 6 different types of toxicity. Metrics 
 The model will be scored with a column-wise ​log loss​ function. The score will the be the average of the log loss of each predicted column, where each column is a different type of toxicity. Log Loss will be used to score the model because it quantifies the accuracy of a classifier by penalising false classifications. 
 
This is a repository of the files I used to compete in the Toxic Comment Challenge.  The models used coded in python and run in Jupyter Notebooks.  

The Project report describes the development process for the initial model I used to compete in the competition.
# Install
To run the code from the notebooks the csv files will need to be downloaded from the kaggle website
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data
# Code
The final code used can be found in the python notebook Ensemble.ipynb
