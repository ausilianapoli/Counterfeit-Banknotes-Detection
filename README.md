# Counterfeit Banknotes Detection
Banknotes are one of the most important assets of a country. Some criminals introduce fake notes which bear a resemblance to original note to create discrepancies of the money in the financial market. It is difficult for humans to tell true and fake banknotes apart especially because they have a lot of similar features. Fake notes are created with precision, hence there is need for an efficient algorithm which accurately predicts whether a banknote is genuine or not.  

## Dataset
Two datasets of genuine and not genuine banknotes will be examined:
- [Banknote Authentication Data from UCI](https://archive.ics.uci.edu/ml/datasets/banknote+authentication);
- [Swiss Banknote Data from R documentation](https://www.rdocumentation.org/packages/uskewFactors/versions/2.0/topics/Swiss%20Banknote%20Data).  

These datasets have different features and the goal of my analysis is to classify genuine (label 0) and counterfeit (label 1) banknotes comparing different features through Machine Learning algorithms.  

## Requirements
- Python3
- Jupyter Notebook

## Results
For all classification techniques both datasets will be splitted in training set (70%) and testing set (30%).
Five algorithms will be compared:
- Naive Bayes;
- Logistic Regression;
- Decision Trees;
- Random Forest;
- SVM.  

The *Swiss Dataset* is very didactic and so it is classified by all tested classifiers easily.  
The *UCI Dataset* is used by Kumar et al. (Bank Note Authentication Using Decision Tree rules and Machine Learning Techniques.) and Upadhyaya et al. (Decision Tree model for classification of fake and genuine banknotes using SPSS.) to perform their analysis with the same goal. All results will be compared. Moreover, the results of this work have got variability in accord to the choice of seed for the random split of dataset.
