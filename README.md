# March_Madness_Predictor-
Data Analysis and prediction models for College Basketball

Goal : predict the winner of College basktball games.

Source : RegularSeasonDetailedResults.csv from https://www.kaggle.com/c/mens-machine-learning-competition-2019/data.

Best model : scikit-learn logisitc regression, 67.09% acurate.

Data : Used average statistics from games that season leading up to the game to predict. Only included games where each team has played at least 10 games earlier that season.
  Statistics : (Averages of previous games that season)
    Score : score
    FGM / FGA : Field Goals (Shots) Made / Attempted
    FGM3 / FGA3 : 3 Point Field Goals Made / Attempted
    FTM / FTA : Free Throws Made / Attempted
    OR : Offensive Rebounds
    DR : Defensive Rebounds
    Ast : Assists
    TO : Turnovers
    Stl : Steals
    Blk : Blocks
    PF : Personal Fouls
