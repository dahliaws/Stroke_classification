# Stroke_classification
### Binary classification for predicting stroke using a kaggle dataset.

The objective was to identify and refine the best classification model for determining those at risk of stroke. After training and testing different classifiers the most effective for this given dataset was a decision tree classifier. 

The dataset was extremely imbalanced causing problems with overfitting. Several different solutions were used to reduce this problem. Some worked better than others.

1. Removing the population <40 where stroke was far less common. 
2. Determining feature importance: Different features and feature combinations were tested for finding ideal fit.
3. Different classification algorithms were tested and the decision tree classifier was found to have the same effectivity as Random Forest. Other classifiers did not work at all.
4. Grid search and Random Oversampling were effective tools for reducing overfitting.
5. Properly pruning the decision tree rendered the best recall.

The goal was to obtain the highest recall (highest fraction of relevant instances) for stroke.

### Workflow:
1. Exploratory Data Analysis
2. Data Cleaning
3. Training and testing
4. Improvement and refinement of the model 
