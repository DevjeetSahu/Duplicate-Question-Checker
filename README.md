# Abstract : 
This is a NLP based project which uses the Random - forest classifiers to predict if two given questions are duplicate or not. This project uses the dataset from Kaggle (https://www.kaggle.com/c/quora-question-pairs). Since the dataset is too large it is trained on a random dataset of 30,000 cases. Data is preprocessed and some feature engineering is done to add some important new features with the help of fuzzywuzzy library. Data is visualized with each feature to see its dependency on the prediction. Random forest classifier and xgboost classifier were used to obtain an accuracy of 78.8% and 79.4% respectively. However, the random forest classifier was chosen over xgboost classifier due to a more correct confusion matrix of random forest classifier. The web app is deployed using streamlit.
https://duplicate-question-checker-devjeet-sahu.streamlit.app/
