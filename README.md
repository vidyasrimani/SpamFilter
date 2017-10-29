# SpamFilter
The email spam filter categorizes mails as Spam or Ham by analysing the contents.

The NLTK python module is used to analyse and train with data.
The Automated spam filtering uses various classifier techniques using sklearn, also a pyhton module



This project uses the following imports:
IMPORTS

import csv
from textblob import TextBlob
import pandas
import sklearn
import cPickle
import numpy as np
from sklearn.feature_extraction.text import CountVectorizer, TfidfTransformer
from sklearn.naive_bayes import MultinomialNB
from sklearn.svm import SVC, LinearSVC
from sklearn.metrics import classification_report, f1_score, accuracy_score, confusion_matrix
from sklearn.pipeline import Pipeline
from sklearn.grid_search import GridSearchCV
from sklearn.cross_validation import StratifiedKFold, cross_val_score, train_test_split 
from sklearn.tree import DecisionTreeClassifier 
from sklearn.learning_curve import learning_curve
%matplotlib inline
import matplotlib.pyplot as plt
