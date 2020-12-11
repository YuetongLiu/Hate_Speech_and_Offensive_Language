# Hate_Speech_and_Offensive_Language

### Authors

YuxiangWang: ywang594@jhu.edu

Jingxi Liu: jliu238@jhu.edu

Wenkai Luo: wluo14@jhu.edu

Yuetong Liu: yliu390@jhu.edu

## Summary

The development of network makes the spread and negative influence of hate speech break through the limitation of region and time; however, it also provides a platform to detect and limit hate speech by artificial intelligence. In this study, we will use skip-gram based word2vec method or n-gram with tfidf as vectorizers using PMI as an indicator to realize feature selection. Then we use Word Count dictionary (LIWC) and LDA to complete our feature extraction and apply logistic regression and support vector machine (SVM) as text classification techniques to develop a model that can distinguish tweets containing hate speech key words into three categories (hate speech, offensive speech, and normal speech).

## Directory roadmap

**data** includes raw data and data generated in the intermediate steps:

* labeled_data.csv: raw data\
* lda_infer.csv: features extracted using LDA
* word2vec_skip.csv: features extracted using skip-gram
* liwc.csv: features extracted using LIWC

**doc** includes the written portions of the project, including:

* Proposal
* Proposal Feedback
* Presentation

**code** includes the python code developed for the project. We have four major sections they are merged into Final.ipynb as the final writeup.

* Feature_Extraction.ipynb data pre-processing and 3 feature extraction methods(LIWC, Skip-gram and LDA)
* Logistic_n_SVM.ipynb (Logistic Regression and SVM)
* CNN.ipynb

