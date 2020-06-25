FIFA20_capstone_project
Author: Hongbin Lin
Date: 2020-06-24

# models
https://drive.google.com/drive/folders/1YnoY-NgR8aN6modmLHxIskK6zkyuiwHL?usp=sharing

This folder only contains a README.txt file and the audience should download all the .pkl file from the google drive link shown above and put them into the models file. In this capstone project, I have used 11 models to predict the player's best position and overall rating score. If audience run the jupyter notebook directly, the run time will be pretty long. So, I pre-trained those models so that the audience can use them right away with trainning the models again.

# data
Data folder contains the 'players_20.csv' file for analysis and modelling.

# Images
Image folder contains the screenshot for report

## Introduction:
In this capstone project, I will explore the soccer player's best position and overall rating based on the different attributes. FIFA20 is a video game that is designed by the data collected from the real world, so it can be a good source to analyze data and build up the predictive model.

### Data visualization

### Top 10 clubs
![clubs](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/top_10_club.png)
### Top 10 national teams
![nationality](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/top_10_nations.png)
### Player's value vs 7 different positions
![value](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/player_value.png)
### Player's wage vs 7 different positions
![wage](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/player_wage.png)

### Data modelling(best position)
![accuracy_score](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/accuracy_best_position.png)

### Consufion matrix(best position)
![KNN](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/KNN.png)
![DT](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/DT.png)
![SVC](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/SVC.png)
![RF](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/RF.png)
![SGB](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/XGB.png)
![FNN](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/FNN.png)

### Data modelling(Over rating)
![r2_score](https://github.com/HongbinLin1995/FIFA20_capstone_project/blob/master/images/r2_score_overall.png)
