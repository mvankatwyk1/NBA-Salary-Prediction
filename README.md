# NBA Salary Prediction
Question: Build different models and find the best one to see how accurately an NBA Player's salary can be predicted based on many different features. With the top model, find the top five features that contribute most to this prediction 

Finding the data:  
The data is found on two different websites-
https://hoopshype.com/salaries/players/2019-2020/
https://www.basketball-reference.com/leagues/NBA_2020_per_game.html
The first website shows salaries for each NBA player during the 2019-2020 season. 
The second website shows many different features such as the player's position, team, average minutes played in a game, average three pointers, age, etc. There are a total of 31 features that are used. 
The data is read in to the file by using the read_html function in pandas. 

Cleaning the data: 
Looking at the data with how it is read in, there is some cleaning that needs to be done. 
1) Some extra lines were read in from the websites and need to be deleted 
2) There are some duplicate players (ones that 
