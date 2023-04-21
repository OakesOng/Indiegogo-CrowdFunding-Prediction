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
  8. VADER
  9. Distill BERT


# Conclusion
  1. We discover the lack of explainability in the sentiment/polarity of titles and taglines in predicting the outcome of a successful campaign in this market (at least for indiegogo). This differs from what we assume from the convention of marketing (using polarity to capture attention to increase success rate).
  2. Factors like Category and Country Launched, launching month and duration of campaign have more weights in deciding the outcome of a successful campaign.
  3. Our model for our classification task can successful predict the outcome of whether someone would get the funding given predictors with confidence level of 82%
  4. Our regression modelling has been concluded a failure due to low explainabiltiy of our model. We decided to reject this problem statement as it might be irresponsible for us to give a non-credible prediction. We have hypothesize that it could be due to lack of explainable predictor in explaining this regression statement with our current predictors. Further feature engineering of text data and incorporation of additional data related to the finance and economy could help to improve explainability.

# What did we learn from this project
  1. Different Statistical Test usage and limitations
  2. More predictors doesn't means better for model
  3. Stratified Cross Validation to reduce underfitting/overfitting in imbalance datasets
  4. BERT & VADER language model for sentiment prediction. Text data have more meaning than just words!
  5. SVM, XGB, KNeighbours, RandomForest, Logistic Regression (and many more models while researching like Naive-Bayes etc)
  6. Precision, Recall, F1 Score
  7. Hyperparameter Tuning
  8. Constrasting models behaviours
  9. Unexpected Outcomes Do Appear!!! (Assumptions made using common sense may fail sometimes/ many times)

# Referrences
- https://www.kaggle.com/datasets/quentinmcteer/indiegogo-crowdfunding-data
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6813708/#:~:text=The%20Student%27s%20t%20test%20is,mean%20difference%20was%20statistically%20significant.
- https://towardsdatascience.com/anova-test-with-python-cfbf4013328b
- https://statistics.laerd.com/statistical-guides/one-way-anova-statistical-guide-3.php#:~:text=There%20are%20two%20tests%20that,the%20Welch%20test%20is%20best.
- https://towardsdatascience.com/levels-of-measurement-statistics-and-python-implementations-8ff8e7867d0b
- https://www.ibm.com/docs/en/cognos-analytics/11.1.0?topic=terms-cramrs-v
- https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/correlation-pearson-kendall-spearman/
- https://datascience.stackexchange.com/questions/64260/pearson-vs-spearman-vs-kendall
- https://towardsdatascience.com/levels-of-measurement-statistics-and-python-implementations-8ff8e7867d0b
- https://resources.nu.edu/statsresources/Pointbiserial#:~:text=The%20Point%2DBiserial%20Correlation%20is,no%2C%20true%2Ffalse).
- https://towardsdatascience.com/bert-roberta-distilbert-xlnet-which-one-to-use-3d5ab82ba5f8
- https://www.kaggle.com/code/robikscube/sentiment-analysis-python-youtube-tutorial
- https://towardsdatascience.com/one-hot-encoding-is-making-your-tree-based-ensembles-worse-heres-why-d64b282b5769
- https://www.kaggle.com/code/prashant111/svm-classifier-tutorial
- https://www.kaggle.com/code/prashant111/knn-classifier-tutorial
- https://www.kaggle.com/getting-started/145362
- https://xgboost.readthedocs.io/en/stable/
- https://towardsdatascience.com/accuracy-precision-recall-or-f1-331fb37c5cb9
- https://www.analyticsvidhya.com/blog/2021/05/4-ways-to-evaluate-your-machine-learning-model-cross-validation-techniques-with-python-code/
- https://grabngoinfo.com/hyperparameter-tuning-for-xgboost-grid-search-vs-random-search-vs-bayesian-optimization/
- https://www.vebuso.com/2020/03/svm-hyperparameter-tuning-using-gridsearchcv/

#Video 
- (Video Presentation)[https://www.youtube.com/watch?v=tXAGxscohRc&ab_channel=Asher]












Enjoy 😃
