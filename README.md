# Wikipedia-Article-Classification

This project involves creating a binary classification model to classify Wikipedia articles as featured and non-featured. 
The project involves data extraction, feature engineering, and model building using Python's Wikipedia API.

### Data Extraction:
Python's Wikipedia API was used to extract the article data in raw format. The data was obtained from the provided repository of Wikipedia articles. The data was separated by "@$@" and "@@" delimiter. Each article's name had a labeling denoting whether it was a featured article or not.

### Feature Engineering:
To create the features for each article, the Wikipedia API was used to extract relevant information. Features that might correlate with the target label were extracted. Sampled articles were created from the dataset to reduce the sample size and get only those articles that can be classified using the API. Features were created during the exploratory data analysis. Relevant features were extracted using the API. I created number of words, number of sections , number of links and redability score as features. The readability scores play majore role in featured article classification

### Model Building:
Different machine learning models were built to classify the articles as featured and non-featured. Random Forest, SVM, and Logistic Regression models were trained on the dataset. The models were evaluated on the basis of accuracy, precision, recall, and F1 score. Random Forest gave the best accuracy of 93.7%. SVM gave an accuracy of 92.46% and Logistic Regression gave an accuracy of 91.29%.

### Conclusion:
The project successfully created a binary classification model to classify Wikipedia articles as featured and non-featured. The project involved data extraction, feature engineering, and model building using Python's Wikipedia API. The models were evaluated on the basis of accuracy, precision, recall, and F1 score. Random Forest gave the best accuracy of 93.7%.
Though, it is Regression project, Logistic regression shown 91.29% and SVM shown 92.46% , little bit better than Logistic.

### Learning Outcomes :
 * Wikipedia API
 * Basics of SPacy and nltk
 * Data Preprocessing techniques
 * Hypertuning techniques for SVM and random forest models

### Post-Evaluation questions:
1. What’s the accuracy you are getting?
Ans : 91.29 % for Logistic regression

2. What if you choose SVM instead of logistic regression?
Ans : Peformance has improved well for SVM

3. What features do you think are important?
Ans : Readability score and words count are important.
