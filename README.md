# Classification_of_Comments #

**Introduction:** This challenge was posted in Kaggle by Jigsaw in collaboration with Google’s Alphabet. The reason I chose this dataset is to classify and remove or block rude comments online. All the comments were drawn from Wikipedia talk page where people can post their opinions and experiences online. By implementation of this project, we can reduce online harassment to provide freedom to post publicly.

**Aim:** To classify comments into 6 categories based on level of toxicity.

We have used _pandas_profiling_ library to outline the dataset.

**Feature Extraction:** We performed feature extraction which is the process of taking out a list of words from the text data and then transforming them into a feature set which would be used as predictors for classification. There are many ways to extract features using NLP techniques, in this project I have used the following two approach-
* Count Vectorization
* Term Frequency - Inverse Document Frequency (TF-IDF)

**Classification Models:**

1.Naive Bayes
2.Logistic Regression
3.Random Forest
4.Gradient Boosting

**Final Model:**

Random Forest
