# email-classification-models
<img src="https://github.com/UrielV1/email-classification-models/blob/master/ham_spam.jpg" alt="https://github.com/UrielV1/email-classification-models/blob/master/ham_spam" width="400"/>

## Project objective
The goal of this project is to build a model which classifies emails as ham or spam

## Project description
- A dataset of 5574 emalis and 2 features (text, label) is given
- The text was cleaned by removing punctuation and stopwords
- The clean text was vectorized using TfidfVectorizer 
- Classic models were built such as: LogR, RF, GB
- Accuracy, Precision and Recall measures were calculated
- Resampling technique was applied to balance the data
- Basic RNN model (sequential) was built
- Dimensionality reduction was executed using PCA method

## Conclusions
- The highest scores were achieved for Random forest model with: acc = 0.976, pre = 0.972, rec = 1
- The results got improved a bit using the resampling method, but computation time was increased
- The fastest model was Logistic regression with very good results: acc = 0.95, pre = 0.95, rec = 0.995
- Using PCA method to reduce dimensionality we got very nice results and less overfitting problem

#### The most accurate model for this problem was RF, and the fastest was LogR
