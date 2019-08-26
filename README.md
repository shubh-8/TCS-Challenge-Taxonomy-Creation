# TCS-Challenge-Taxonomy-Creation

#### Out of 5 problems, I choose Taxonomy Creation problem. This is a Tag prediction based problem. In which we have to create a hierarchy of tags, also known as Taxonomy.
#### Data Source: https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data
#### Stack Exchange has released this data which consist of Question descriptions, Titles and their Tags.

Stack Exchange is a network of question-and-answer websites on topics in diverse fields, each site covering a specific topic. The primary purpose of each Stack Exchange site is to enable users to post questions and answer them.<br>

Our task is to predict the tags (a.k.a. keywords, topics, summaries), given only the question text and its title and create hierarchy of tags. The dataset contains content from disparate stack exchange sites, containing a mix of both technical and non-technical questions.

#### Problem Statement : Predict the tags based on the content of the questions posted on Stack Exchange sites and form taxonomy.

My solution is divided into two i-python notebooks.
1. Taxonomy Creation - EDA.ipynb
2. Taxonomy Creation - Model.ipynb

#### 1. Taxonomy Creation - EDA.ipynb
It consist of the analysis part of the solution.

#### 2. Taxonomy Creation - Model.ipynb
It consist of the modelling part of the solution

I have trained two models:

__1. NB_model.sav__ is the saved MultinomialNB with OneVsRest Classifier model. This model is trained on 3M data points.

__2. LR_model__ is the saved Logistic Regression with OneVsRest Classifier model. This model is trained on 1M data points (due to hardware limitations).

Thus, please consider NB_model.sav model for evaluation.

