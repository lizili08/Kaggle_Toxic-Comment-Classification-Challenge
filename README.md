# Kaggle_Toxic-Comment-Classification-Challenge
# 比赛连接：https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/overview
## 本方案旨在复现top1方案来练习机器学习在二分类中的应用
### Dataset Description

You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

-toxic
-severe_toxic
-obscene
-threat
-insult
-identity_hate
-You must create a model which predicts a probability of each type of toxicity for each comment.

### File descriptions
train.csv - the training set, contains comments with their binary labels
test.csv - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.
sample_submission.csv - a sample submission file in the correct format
test_labels.csv - labels for the test data; value of -1 indicates it was not used for scoring; (Note: file added after competition close!)

### Usage
The dataset under CC0, with the underlying comment text being governed by Wikipedia's CC-SA-3.0
