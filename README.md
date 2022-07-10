# MLB-Game-Predictor
Using Machine Learning and publicly available statistics to predict the results of Major League Baseball games.

# Instructions
- Run the Training_Data program to scrape and organize the data from all prior games during the season
- Run the Model program to use that training data to create, tune and test a Random Forest model for predicting the result of the matches
- Run the Predictor program to predict the results of the matches using a Monte Carlo style simulation which will calculate each team's chance of winning

# Future Objectives/Areas of improvement
- Find a way to account for players who are injured/unavailable for a given game.
- Include the rolling statistics instead of the cumulative statistics which will better account for winning/losing streaks and recent form overall
- Consider adding different Machine Learning Models such as a Neural Network or a Support Vector Machine
