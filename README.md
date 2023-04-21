# Indiegogo-CrowdFunding-Prediction

## About
This project is a mini project for SC1015, which focuses on the prediction of whether a person will likely to run a successful crowd funding campaign. For detailed walkthrough, please view the source code in order from:
  1. [Simple Data Cleaning](https://github.com/OakesOng/Indiegogo-CrowdFunding-Prediction/blob/main/Data%20Cleaning.ipynb)
  2. [EDA & Further Data Cleaning](https://github.com/OakesOng/Indiegogo-CrowdFunding-Prediction/blob/main/EDA%20%26%20Further%20cleaning.ipynb)
  3. [Text Sentiment Extraction with VADER & Distill BERT](https://github.com/OakesOng/Indiegogo-CrowdFunding-Prediction/blob/main/text_polarity_score.ipynb)
  4. [Cleaning of sentiment score](https://github.com/OakesOng/Indiegogo-CrowdFunding-Prediction/blob/main/polarity_score_cleaning.ipynb)
  5. [Classification Modelling](https://github.com/OakesOng/Indiegogo-CrowdFunding-Prediction/blob/main/Machine%20Learning%20Part%20I%20-%20View.ipynb)
  6. [Regression Modelling](https://github.com/OakesOng/Indiegogo-CrowdFunding-Prediction/blob/main/Machine%20Learning%20Part%20II-View.ipynb)

## Contributors
- Asher Lim: Data Sourcing, Data cleaning, Regression, Analysis
- Dennis Chen: Feature engineering, Data Visualization, Classification, Analysis
- Ong Sheng Da: Text Processing, Regression, Classification, Analysis, Hyperparameter Tuning

## Problem definition
- Predicting/ Modelling the outcome of whether the crowdfunding campaign will be successful with a high confidence level
- Modelling the amount of fundings received given the predictors

## Models used
  1. Decision Tree Classifier
  2. RandomForest Classifier
  3. Support Vector Classifier
  4. KNeighbour Classifier
  5. XGB Classifier
  6. Logistic Regressor
  7. XGB Regressor


# Conclusion
  1. We discover the lack of explainability in the sentiment/polarity of titles and taglines in predicting the outcome of a successful campaign in this market (at least for indiegogo). This differs from what we assume from the convention of marketing (using polarity to capture attention to increase success rate).
  2. Factors like Category and Country Launched, launching month and duration of campaign have more weights in deciding the outcome of a successful campaign.
  3. Our model for our classification task can successful predict the outcome of whether someone would get the funding given predictors with confidence level of 82%
  4. Our regression modelling has been concluded a failure due to low explainabiltiy of our model. We decided to reject this problem statement as it might be irresponsible for us to give a non-credible prediction. We have hypothesize that it could be due to lack of explainable predictor in explaining this regression statement with our current predictors. Further feature engineering of text data and incorporation of additional data related to the finance and economy could help to improve explainability. More data points(current approx. 12k) may also be needed for credibility.














Enjoy 😃
