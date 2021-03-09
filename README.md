#### 1-Day Solo Hackathon

**Problem Statement**

Determine whether a stock price will close up or down based on the news released about the stock during a trading day.

**Executive Summary**

This Analysis examined Apple stock price between December 2006 and November 2016 to test whether published news impact stock price direction. This work was part of a one-day solo hackathon, where I had to source, clean, analyze the data and build models to test the problem statement. I used five models to test the hypothesis with the best performing model being Logistic Regression using news sentiment as the only predictor. The accuracy of the best model was 54% - slightly better than the Null Model with accuracy score of 51%. 

**File Directory**

- cleaning and EDA: cleaning_and_eda.ipynb

- data/
    - ApppleNewsStock.csv 
    - apple_clean.csv
    - apple_vect_clean.csv

- models/
    - logistic_regression.ipynb 
    - countvectorizer_naive_bayes.ipynb
    - gradientboosting_classifier.ipynb
    - logistic_regression_on_sentiment.ipynb
    - SVC.ipynb
    
**Data**

Apple Stock Data: 2006 - 2016
Data Sources: https://www.kaggle.com/BidecInnovations/stock-price-and-news-realted-to-it/code

**Conclusion**

Based on the model results, we can conclude that news as a stand-alone is not a great predictor of a stock price direction. **Caveat:** subject to the news sample being relevant to the stock.