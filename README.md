### Problem Statement

Identifying Entities in Healthcare Data

In this assignment,  performed the following broad steps:
1. process and modify the data into sentence format. This step done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
2. Define the features to build the CRF model.
3. Apply these features in each sentence of the train and the test dataset to get the feature values.
4. Once the features are computed,  define the target variable and then build the CRF model.
5. Perform the evaluation using a test data set.
6. Create a dictionary in which diseases are keys and treatments are values.
 
##Steps Involved

**Data preprocessing**
1. Data preprocessing and modifying dataset
2. Construct proper sentences from individual words and print five sentences with labels.
3. Print the correct count of the number of sentences in the processed train and test dataset.
4. Correctly count the number of lines of labels in the processed train and test dataset.
**Concept identification**
1.  POS tagging
2. Use a toolkit like spaCy to extract those tokens that have NOUN or PROPN as their PoS tag and find their frequency from the entire dataset that comprises both the train and the test datasets.
3. Print the top 25 most common tokens with NOUN or PROPN PoS tags for the entire dataset that comprises both the train and the test datasets.
**Defining the features for CRF**
1. Use a toolkit like spaCy to extract those tokens that have NOUN or PROPN as their PoS tag and find their frequency from the entire dataset that comprises both the train and the test datasets.
2. Print the top 25 most common tokens with NOUN or PROPN PoS tags for the entire dataset that comprises both the train and the test datasets.
**Getting the features words and sentences**
1. Write the code to get the features' value of a sentence after defining the features in the previous step.
2. Write the code to get a list of labels of a given preprocessed label line that you have created earlier.
**Defining input and target variables**
1. Extract the features' values for each sentence as an input variable for the CRF model in the test and the train dataset.
2. Extract the labels as the target variable for the test and the train dataset.
Building the model
1. Build the CRF model for a custom NER application using the features and the target variables.
**Evaluating the model**
1. Predict the labels of each of the tokens in each sentence of the test dataset that has been preprocessed earlier.
2. Calculate the f1 score using the actual and the predicted labels of the test dataset.
**Identifying the diseases and predicted treatment using a custom NER**
1. Create the code or logic to get all the predicted treatments (T) labels corresponding to each disease (D) label in the test dataset. You can refer to the following image to get an idea on how to create a dictionary where diseases are working as keys and treatments are working as values.
2. Predict the treatment for the disease named 'hereditary retinoblastoma'.
