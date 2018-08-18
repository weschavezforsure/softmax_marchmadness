Here I train a softmax classifier to predict the winner of a NCAA tournament game based on 1. the teams' seeds, and 2. the mean amount of points scored per game during the regular season for each team.  This model scored 9th of 505 in "Google Cloud & NCAA® ML Competition 2018-Women's" kaggle competition.  The data is available at: https://www.kaggle.com/c/womens-machine-learning-competition-2018/data

The first two files clean the data and save numpy arrays for input to the softmax classifier.

To run,
```
python createTrainingData.py
python createTestData.py
python softmax_keras.py 
```

Requires keras and numpy.
