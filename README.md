# Kindle Review Sentiment Analysis

### Overview of the Project
This is a personal project of kindle review sentiment analysis  which aims to understand the working of word2vec and avg word2vec

### About the Dataset

Context - This is a subset of dataset of Book reviews from Amazon Kindle Store Categor.

Content 5-core dataset of product reviews from Amazon Kindle Store category from May 1996 - July 2014. Contains total of 982619 entries. Each reviewer has at least 5 reviews and each product has at least 5 reviews in this dataset. Columns

*   asin - ID of the Product, like B000FA64PK
*   helpful - helpfulness rating of the review - example: 2/3
*   overall - rating of the product
*   reviewText - text of the review (heading)
*   reviewTime - time of the review (raw)
*   reviewerID - ID of the reviewer, like A3SPTOKDG7WBLN
*   reviewrName - name of the reviewer
*   summary - summary of the review
*   unixReviewTime - unix timestamp

### Workflow Diagram
![Worflow Diagram of the Project](https://github.com/ratul-07/kindle-review-sentiment-analysis/blob/main/Images/Workflow%20Diagram.png)

### Data Visualization

  ![Confusion Matrix using GNB](https://github.com/ratul-07/kindle-review-sentiment-analysis/blob/main/Images/GaussianNB%20CM%20KindleRA.png)


  ![Confusion Matrix using RF](https://github.com/ratul-07/kindle-review-sentiment-analysis/blob/main/Images/RandomForest%20CM%20KindleRA.png)


  ![Confusion Matrix using LR](https://github.com/ratul-07/kindle-review-sentiment-analysis/blob/main/Images/LogisticRegression%20CM%20%20KindleRA.png)

### Results
#### Accuracy Score

* Gaussian Naive Bayes Classifier - 0.74125
* Random Forest Classifier - 0.767916
* Logistic Regression - 0.815833
  
