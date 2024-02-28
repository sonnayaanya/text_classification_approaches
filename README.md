This repository contains a notebook with data exploration, pre-processing and implementation of several popular text classification techniques, including CatBoost and TextCat. The dataset is a custom dataset with two balanced classes fused from two data sources: [Women's Clothing E-Commerce Reviews](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews) from kaggle and [Amazon Clothing Reviews](https://snap.stanford.edu/data/web-Amazon-links.html) from SNAP. We find that TextCategorizer trained on raw data outperforms all other approaches, including TextCategorizer trained on pre-processed data. Our work also demonstrated that among classical supervised algorithms the least sophisticated approach, namely logistic regression, outperformed its more advanced counterparts, such as gradient boosting on decision trees and support vector classifier.
