## This project focused on the Kaggle competition `Natural Language Processing with Disaster Tweets`. The required dataset is obtained from and submission for this competition are made on Kaggle.
## Link to Competition: https://www.kaggle.com/competitions/nlp-getting-started/overview

### GitHub link: 

## The final code is added to the `P8_ALDA.ipynb` file. We have also added the code which we used for Midway report submission.
## For this project we are using Python 3.12.7 version.
## The dataset reuquired to run this project is also present in the nlp-getting-started directory. Where `train.csv` and `test.csv`. Here, we split the train.csv into training and validation datasets, whereas test.csv file was used to check the results of final selected appraoch.

## This code uses following libraries, amke sure you have those installed on your device. We would strongly encourage you to create a new virtual environment to test this code with having following set of libraries installed.

- numpy
- pandas
- matplotlib
- wordcloud
- re
- collections
- seaborn
- sklearn
- nltk
- gensim
- xgboost

- nltk.download('punkt')
- nltk.download('stopwords')
- nltk.download('wordnet')
- nltk.download('punkt_tab')

## After finalizing SVM + Count Vectorizer approach along with hyperparameter tuning, we made predictions on test.csv file and submitted the results to the Kaggle competition. Where we achieved F1 score of 79.28%.