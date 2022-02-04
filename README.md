Problem statement:
Can I build a model that predicts salary based of soccer player position for the US league(MLS)?
Answer: no

One true statement about sports is that stars are always payed better than those who fly under the radar. In soccer, the stars are usually those who score the goals, no matter how well the rest of the team played. As a result, I examined salary data expecting to see higher pay for the Forward position players(those who often get to take shots on goal). I looked at salary data for players in Major League Soccer from 2007-2017 and attempted to build a model that predicts a player's salary based off of their position to within, ideally, 50,000 dollars. However, the models I built did not work at all. I tried Linear Regression, K nearest neighbors, Decision trees, Bagged deicision trees, Random forest, and a support vector machine, and the best score was the Decision tree model at 0.0160 train accuracy and 0.0187 test accuracy. Due to time constraints I elected to present statistical data instead, showing that indeed soccer players in MLS who played the forward position were payed much higher than less glamorous positions such as defender. Forwards were payed less than the overall average player salary initially, but sky rocketed above the average from 2010 onward. 

Source:
https://www.kaggle.com/crawford/us-major-league-soccer-salaries
