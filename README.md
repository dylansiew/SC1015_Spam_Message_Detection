# Welcome to spam-detetion repository

## About

This is a Mini-Project for SC10105 (Introduction to Data Science and Artificial Intelligence) which focuses on Spam Messages from [Spam DataSet](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset). For detailed walkthrough, please view the source code in order from:

1. [Data Extraction](https://github.com/nicklimmm/movie-analysis/blob/main/data-extraction.ipynb)
2. [Data Visualization](https://github.com/nicklimmm/movie-analysis/blob/main/data-visualization.ipynb)
3. [Data Resampling and Splitting](https://github.com/nicklimmm/movie-analysis/blob/main/data-resampling-and-splitting.ipynb)
4. [Logistic Regression](https://github.com/nicklimmm/movie-analysis/blob/main/logistic-regression.ipynb)
5. [Neural Network](https://github.com/nicklimmm/movie-analysis/blob/main/neural-network.ipynb)
  
## Contributors

- @dylansiew 
- @integr8ti0n

## Problem Definition

- How can we effectively identify Spam messages with the attributes of text messages?
- Which model would be the best to predict it? Or can all models be used to predict it?

## Models Used

1. Naive Bayes
2. Support Vector Machine
3. Random Forest Classifier
4. Logistic Regression

## Conclusion

- All models performed well when predicitng Spam Messages with a low false negative and false positive rate
- Support Vector Machine performed the best of all 4 models (97.7% Accuracy) and there is a logistic correlation between the presence of Phone numbers and the message being Spam
- Running K-Fold resampling on the models produced more accurate performance measure of the models  
- Model Ensemble performed better than all 4 models as it is the cummulation of the 4 models (98.4% Accuracy)
- It is possible to predict Spam messages with sufficiently large datasets for the models to train on. 

## What did we learn from this project?

- Handling imbalanced datasets using resampling methods like K-Fold
- Logistic Regression, Naive Bayes, SVC and RandomForestClassifier from sklearn
- Other packages such as tqdm, Figlet, IPython
- Collaborating using GitHub
- Concepts about Accuracy, Vectorizing, and F1 Score

## References

- <https://www.dataquest.io/blog/jupyter-notebook-tutorial/>
- <https://www.programcreek.com/python/example/103471/wordcloud.STOPWORDS>
- <https://www.kaggle.com/rafjaa/resampling-strategies-for-imbalanced-datasets>
- <https://scikit-learn.org/stable/modules/cross_validation.html>
- <https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html>
- <https://www.npmjs.com/package/figlet>
- <https://medium.com/@cmukesh8688/tf-idf-vectorizer-scikit-learn-dbc0244a911a>
- <https://builtin.com/machine-learning/ensemble-model>
- <https://www.analyticsvidhya.com/blog/2018/06/comprehensive-guide-for-ensemble-models/>
- <https://www.analyticsvidhya.com/blog/2022/02/k-fold-cross-validation-technique-and-its-essentials/>
