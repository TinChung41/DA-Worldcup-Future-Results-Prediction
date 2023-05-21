# DA-Worldcup-Future-Results-Prediction
You can see the colab notebook using this [link](https://colab.research.google.com/drive/18z2ytzwypwl8JWMsLuyv6JAjwHMD-5hr?usp=sharing)

## Data
The project utilizes a comprehensive dataset of historical World Cup match results. We have obtained this data from the "International
soccer matches and team strengths (1993-2022)" dataset available on Kaggle. You can access the dataset here. The dataset contains a wide range of information, 
including team names, match scores, player statistics, and more. We have processed and organized the data to fit the requirements of this project. The dataset is regularly
updated to ensure the latest results are incorporated into the predictions.

## Data processing:
### Excel: Use excel to fix and choose a range for the desired prediction:
We decided to choose the range from the year 2000 to 2022 to see the prediction
base on the last 22 years' data. Identify future trends based on historical data. The
reason behind this decision was between 1993 to 2000:

Secondly, the world cup started in 1930, and the data was recorded back in
1993. So 2000 is simply a number that our group decided to work on, and
the result turns out doesn’t affect too much.

### Google Colaboratory Notebook/Jupyter Notebook(ipynb file)
Programing Language: Python
Use the popular libraries in python to do the following processes;
-Import, clean, tidy, and visualize data
-Build model: Decision tree, Random forest, and draw conclusions for Worldcup
prediction

### Visualize the prediction

This notebook use a interesting visualization method: **Using Bar Chart to visualize ranking**, which is contradicting becasue  Bar charts are primarily used to represent
categorical or discrete data, where the length of each bar corresponds to a specific value

Top 10 teams based on FIFA rank
![image](https://github.com/TinChung41/DA-Worldcup-Future-Results-Prediction/assets/98845918/8c9ce0eb-ff49-4b44-ac5d-135148f7f498)

* Top 10 teams with the highest atacking point

![image](https://github.com/TinChung41/DA-Worldcup-Future-Results-Prediction/assets/98845918/1f03f1b4-7bc5-4f29-bcf1-dd124805ea78)

* Top 10 teams with the highest midfield points

![image](https://github.com/TinChung41/DA-Worldcup-Future-Results-Prediction/assets/98845918/7faf96f0-e2c9-48e1-9154-6565d631ad29)

* Top 10 teams with the highest Defense point

![image](https://github.com/TinChung41/DA-Worldcup-Future-Results-Prediction/assets/98845918/4a97545f-dda8-4428-9b5d-29c7dde83443)

##  Winning Change of top 10 teams

Brazil in top 4 offense_score and top 5 in defense_score,midfield_score
Yet Brazil has the record for the most World Cup titles in soccer history with five,
taking home the trophy in 1958, 1962, 1970, and 1994 and, most recently, in 2002.
Maybe because we exclude the data from before the year 2000. Which is when
Brazil's team was in its prime. Plus the data only got recorded in 1993, so the
Brazil team was not as strong as they were supposed to be. This should be
accountable when we make our prediction of which team/country would win the
2022 World Cup title

2022 qualified teams
![image](https://github.com/TinChung41/DA-Worldcup-Future-Results-Prediction/assets/98845918/ab706338-36ab-4b67-bbd2-761032ae27cc)

All the 21 rankings mean over time are all in the range 55(Saudi Arabia
approximately 56.647, ). The outliers clearly are Canada and Qatar rank up
78 and 84 in the FIFA ranking mean since 2000 till now.
![image](https://github.com/TinChung41/DA-Worldcup-Future-Results-Prediction/assets/98845918/44cb8e44-d704-44db-ad37-ad408adc1de2)

## Predictions for Knockout Stage - Removing Draw status
![image](https://github.com/TinChung41/DA-Worldcup-Future-Results-Prediction/assets/98845918/c3988327-1974-4d78-b036-3d88841fe2dd)

## Simulation for Round 16, Quarter-Final World, Semi-Final World Cup, and  Winner World Cup 2022
![image](https://github.com/TinChung41/DA-Worldcup-Future-Results-Prediction/assets/98845918/2e397931-c897-41e7-9e97-89f1dcd24244)


