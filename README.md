# SetimentAnalysis of News Article to Predict Stock Trend
In this project, using news articles, historical stock price, and sentiment wording dictionary combined with sentiment analysis and modeling techniques, we will create a system that analyzes news and generates polarity for it, resulting in determining the flow of the Stock Market.

We will use pysentiment2 library (https://pypi.org/project/pysentiment2/) for Sentiment analysis. 

This Library is based on Loughran and McDonald Financial Sentiment Dictionaries.

This Project uses two datasets: -
1. NewsDataset - https://www.kaggle.com/rmisra/news-category-dataset
2. Apple Stock Proce Dataset - https://www.kaggle.com/khoongweihao/aaplcsv

The size for news article dataset is very big so can be accesed from source url .

# Project Flow 

![ProjectFlow](https://user-images.githubusercontent.com/81599198/150951250-8b58dcd0-717e-4a22-ac60-f09adcf06280.png)

We have used three modelling technique - Naive Bayes,  GradientBoosting and Support Vector 
Machine (SVM).

K=5 Fold Validation is used on models.

Based F1 Score and Accuracy Score are key metrics for Model Evaluation. 
