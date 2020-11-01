# Siddharth Boppana's Portfolio of Computer Science Projects
------------
## Projects I'm Currently Working On or Planning To
* [NFL Next Gen Stats Big Data Bowl](https://www.kaggle.com/c/nfl-big-data-bowl-2021)
* [MNIST Data Set Digit Recognizer](https://www.kaggle.com/c/digit-recognizer)

## Finished Projects

### [Fantasy Football Quarterback Points Estimator](https://github.com/AskSid/Fantasy-Football-Regression)
* Predicts the total season fantasy football points for a quarterback based on their previous season data
* Data originally from profootballreference.com
* Used a neural network from the TensorFlow/Keras library trained with a regression output
* Outputs a ranking of the top 30 quarterbacks by fantasy football points
* Does slightly worse than some ESPN analysts when using a mean-squared error metric of accuracy

![](/images/fantasy_regression.png)
* Table displays the actual fantasy points rankings, one ESPN analyst's rankings, and the neural network's ranking for the 2019-2020 season

### [Fantasy Football Wide Receiver Points Classifier](https://github.com/AskSid/Fantasy-Football-Classification)
* Predicts the interval of a wide receiver's fantasy football points per game between 1 and 5
* 1 indicates less than 10 points per game, 2 indicates between 10 and 15 points per game, and so on until 5 which indicates more than 25 points per game
* Used a neural network from the TensorFlow/Keras library trained with a classification output
* Ranks receivers by categorizing them by interval based on their previous season performance
* Data originally from profootballreference.com

![](/images/fantasy_classifier.png)
* Model's predicted top-30 fantasy points per game receivers in the 2019-2020 season

### [Housing Prices Estimator](https://github.com/AskSid/Housing-Prices-Regression)
* From kaggle.com competition Ames Housing dataset as training and testing data
* Used regression analysis with a random forest regressor and a gradient boosting regressor to determine which would result in a more accurate output
* Evaluated based on the root mean squared error between the log of the predicted value and log of the observed sales value
* Accuracy of 98.14% and 98.73% using square eror of random forest and gradient boosting regressor respectively
* Submitted on kaggle.com competition, placed 2371 out of 4480 submissions on first attempt

![](/images/housing_prices.png)
* Red is actual housing prices, blue is predicted housing prices by model

### [Pixelated Clothing Classifier](https://github.com/AskSid/Clothing-Classifier)
* Data from MNIST Fashion dataset of 25 by 25 pixelated grayscale images of clothing
* Used a convolutional neural network to classify images into 10 types of clothing by training the model
* The accuracy on the test set was 88.64% for classifying the images

![](/images/clothing_classifier.png)
* Bar graph indicates percentage chance of image being different types of clothing, left has image with the model's predicted probability of type

### [BHS Schedule](https://github.com/AskSid/schedule_classes)
* Built for my personal use to determine what classes I have everyday for my school schedule
* Predicts what classes a student will have based on a 7-day waterfall schedule where the student has 6 classes a day 


