# 2016.M3.TQF-ML.Kobe_Shot_Selection

### Project description

Kobe Bryant marked his retirement from the NBA by scoring 60 points in his final game as a Los Angeles Laker on Wednesday, April 12, 2016. Drafted into the NBA at the age of 17, Kobe earned the sport’s highest accolades throughout his long career.

Using 20 years of data on Kobe's swishes and misses, we want to predict which shot will find the bottom of the net. The focus of this project is to extract effective features from the raw data which contains lots of information.

### Features

some features I created by myself

'action_type'

'combined_shot_type'

'season'

'opponent'

'home_game'

'loc_x' : horizontal coordinates of the shot location

'loc_y' : vertical coordinates of the shot location

'shot_distance' 

'shot_zone_area'

'is_last_minute' : whether the shot is made at the last minute of the quarter.

'age'

'previous_shot_type' : the type of his previous shot attempt

'previous_shot_made' : whether the previous shot is made

'distance_from_staples' : the distance from LA.

### Methods

Try KNN/logistic/SVM/RandomForest/AdaBoost to choose a better model.

### Data

from Kaggle's website: https://www.kaggle.com/c/kobe-bryant-shot-selection

### Conclusion

The best model for this project is Logistic Regression. And the linear models(Logistic,SVM,Adaboost) all perform better than non linear models(KNN,RandomForest). The best test accuracies is around 68%.
