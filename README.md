# Gaussian Naive Bayes for text: Spam Filter for e-mail
## ナイーブベイズ分類器によるEメールスパムフィルター
![](https://s3.ap-south-1.amazonaws.com/techleer/204.png)

## Introduction

The equation at the center of naive Bayes is an application of Bayes theorem.

The posterior probability P (cat | doc) is the probability that it is the category cat given the document doc. Unknown documents for which you want to predict categories are classified into categories with the highest posterior probability (MAP estimation). In order to calculate this probability, the prior probability P (cat) on the right side and the likelihood P (doc | cat) are required. P (doc) is common to all categories and can be ignored. The posterior probability P (cat | doc) and the likelihood P (doc | cat) are confusing but different.

## Technical Preferences

| Title | Detail |
|:-----------:|:------------------------------------------------|
| Environment | MacOS Mojave 10.14.3 |
| Language | Python |
| Library | scikit-learn, Numpy, matplotlib, Pandas, Seaborn |
| Dataset | Twitter |
| Algorithm | Gaussian Naive Bayes |

## Refference

- [Understanding Naive Bayes and its application in text classification](https://medium.com/datadriveninvestor/understanding-naive-bayes-and-its-application-in-text-classification-99c38e739f88)
- [6 Easy Steps to Learn Naive Bayes Algorithm](https://www.analyticsvidhya.com/blog/2017/09/naive-bayes-explained/)
- [Implementing a Naive Bayes classifier for text categorization in five steps](https://towardsdatascience.com/implementing-a-naive-bayes-classifier-for-text-categorization-in-five-steps-f9192cdd54c3)
- [Text Classification in NLP — Naive Bayes](https://medium.com/@theflyingmantis/text-classification-in-nlp-naive-bayes-a606bf419f8c)
