# CodeClause_fake-news-analysis_keshu
In this advanced python project, I took a political dataset, implemented a TfidfVectorizer, initialized a PassiveAggressiveClassifier, and fit to my model. I committed this project in CodeClause internship.
Steps for detecting fake news with Python:
1) Make necessary imports
2) Read the data and get the shape of the data
3) Get the labels from the DataFrame
4) Split the dataset into training and testing sets
5) Initialize a TfidfVectorizer
6) Initialize a PassiveAggressiveClassifier
7) Confusion matrix

DATASET:
news.csv is the dataset used for this project.This dataset has a shape of 7796×4. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE.
source:www.kaggle.com
