# Halloween Candies and Their Features

## Short description of the Short description of the project, Objective, results and conclusions
Using the dataset, candy_data, from a survey to find the best Halloween candy, I built a logistic regression model that can be used to determine whether a candy has caramel from the 269,000 responses documented. Some questions I was looking to answer as I was doing this project was “what made more candies more desirable than others?”. While building this model, I discovered in a group of 7 features, the only field with relevance to predict if the candy contains is the number of features the candy has. The model resulted in a 89% accuracy where there was less than 30% of entries that contained caramel with a with a positive predictive value of 37% and a negative predictive value of 95%. This implies it will more successfully predict when a candy does not have caramel than when it does. Low positive predictive value is because the number of candies with caramel in the data set is not as significant. In order to correct this, I can either train my model on a new data set with an even greater number of entries or use a different feature as my dependent variable such as chocolate or fruity.

## Dataset being used
The ultimate Halloween Candy Power Ranking - https://www.kaggle.com/datasets/fivethirtyeight/the-ultimate-halloween-candy-power-ranking

## Installation and execution 
1. Clone the repository
2. download the jupyter notebook and follow steps
3. If you want to use the model on a different feature, change the appropriate lines.

## Performance parameters used
Sensitivity of model = 0.7777777777777778
Specificity = 0.76
False positive rate = 0.24
True positive = 0.3684210526315789
True Negative = 0.95

## About Developer
Fourth year computer science major student at Laurier. 
linkedin - https://www.linkedin.com/in/lovette-oyewole/

# License applicable to use code
The dataset is Copyright (c) 2014 ESPN Internet Ventures and distributed under an MIT license.

