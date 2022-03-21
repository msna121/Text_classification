# Text_classification

The input data contains user reviews for different products without any labels. The objective is to categorize the reviews using unsupervized machine learning techniques. In the use case, Latent Dirichilet Allocation is used as the final model to categorize the reviews.

## Steps involved
##### 1. Import required libraries
##### 2. Preprocessing the data
##### 3. Model selection and building the model
[Initial model with 10 topics](https://github.com/msna121/Text_classification/blob/master/lda_10topics.html)
Download and open in browser
##### 4. Selecting optimum number of topics using elbow method
![image](https://github.com/msna121/Text_classification/blob/master/Elbow_method.png)
##### 5. Updating the model and retraining with optimum topics
[Final model with 4 topics](https://github.com/msna121/Text_classification/blob/master/lda_4topics.html)
Download and open in browser
##### 6. Saving the model

# Files:
1. [Input_data](https://github.com/msna121/Text_classification/blob/master/User_Reviews.csv)
2. [Code_file](https://github.com/msna121/Text_classification/blob/master/Text_classification_final.ipynb)
3. [Saved_model](https://github.com/msna121/Text_classification/blob/master/topic_model.pkl)
4. [Output_file_with_custom_named_topics](https://github.com/msna121/Text_classification/blob/master/submission.csv)
5. Referenes - https://www.machinelearningplus.com/nlp/topic-modeling-python-sklearn-examples/, https://spacy.io/api/data-formats, https://towardsdatascience.com/k-means-clustering-8e1e64c1561c
