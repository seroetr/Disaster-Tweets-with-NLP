### Disaster Tweets Classifications by Machine Learning,  which is currently `Kaggle Competition`.
- `train.csv` and `test.csv` files can be found via `https://www.kaggle.com/competitions/nlp-getting-started/data`.
- Columns in `train.csv' dataset are:
  - id
  - text
  - location
  - keyword
  - target
 - You will be predicting if tweet is a real disaster (1) or not (0)
 - Machine learning models such as LightGBM, XGBoost, RandomForest, and CatBoost Classifiers have been used to predict the disaster tweets.
 - RandomizedSearchCv is used to tune hyperparameters for models.
 
Models | LGBMClassifier | CatBoostClassifier | XGBClassifier | RandomForestClassifier
| :---: | :---: | :---: | :---: | :---:
Accuracy  | 0.7634 | 0.7706 | 0.7648 | 0.7873

- RandomForestClassifier has demonstrated higher accuracy than rest of the models. Therefore, Test data is evaluated using RandomForestClassifier.


