# Anime-Analysis-Repo

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence).


1. [Data Extraction and Cleaning](https://github.com/KaiKoiKarp/Anime-Analysis-Repo/blob/main/Data%20Extraction%20and%20Cleaning.ipynb)
2. [Exploratory Data Analysis](https://github.com/KaiKoiKarp/Anime-Analysis-Repo/blob/main/Exploratory%20Data%20Analysis.ipynb)
3. [Pre-machine Learning](https://github.com/KaiKoiKarp/Anime-Analysis-Repo/blob/main/Pre-Machine%20Learning.ipynb)
4. [Machine Learning](https://github.com/KaiKoiKarp/Anime-Analysis-Repo/blob/main/Machine%20Learning%20Part.ipynb)

## Contributors

- @Kai Kiat - Cleaning and Exploratory Data Analysis
- @Marcus - Pre-machine Learning
- @Wei Ming - Machine Learning

## Problem Definition

Are we able to predict the rating of an anime based on it’s factors?

## Predictor Variables Used
1. Genres
2. Production Studio 
3. Period of Release
4. Type (Movie/TV) 

## Response Variable
1. Rating of the Anime 

## Models Used
1. Decision Tree
2. Random Forest
3. Logistic Regression
4. K Neighbours Classifier
5. MultiLayer Perceptron

## Evaluation Metrics Used
1. Accuracy
2. F1 Score

## Conclusion
Decision Tree Classification is relatively inaccurate, they are deterministic in the sense that there is no randomness to split the data, and they tend to overfit. Other machine learning models should be used instead.

MultiLayer Perceptron showed the best performance follwed by K Neighbours Classifier, Random Forest, Logistic Regression, and lastly, Decision Tree. 

## Data Driven Insights
1. Period:
  - Old animes generally fall in the average and good categories
  - Animes with excellent and poor ratings are typically newer animes
2. Studio:
  - Studios like Shin-Ei Animation and OLM generally produce Average and Good animes 
  - Studios like Bones and A1 Picture produce Good and Excellent animes
3. Genres:
  - Based on Manga is the least important genre
  - Romance and School Life are important genres  
4. Type:
  - TV series anime is just as good as movie anime 

## Learning Outcome
- Various Ways of Data Preparation
- Various Data Visualization Techniques
- Various Machine Learning Models
- Drawing Meaningful Insights 

## References
https://www.kaggle.com/datasets/vishalmane10/anime-dataset-2022
https://www.analyticsvidhya.com/blog/2020/05/decision-tree-vs-random-forest-algorithm/
https://towardsdatascience.com/logistic-regression-using-python-sklearn-numpy-mnist-handwriting-recognition-matplotlib-a6b31e2b166a
https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761
https://analyticsindiamag.com/a-beginners-guide-to-scikit-learns-mlpclassifier/
https://medium.com/analytics-vidhya/accuracy-vs-f1-score-6258237beca2
