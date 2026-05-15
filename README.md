# League_of_legend_win_prediction
This project studies whether early-game team statistics can be used to predict match outcomes in League of
Legends. After cleaning the original dataset of 24,225 matches, I constructed difference-based features
comparing blue-team and red-team advantages. Exploratory analysis showed strong separation between wins
and losses for gold, experience, kills, damage, and tower pressure. Logistic regression achieved the best
overall performance among the tested models, with accuracy of 0.764 and AUC of 0.845. Regularized logistic
regression, Random Forest, and XGBoost produced very similar results, suggesting that the available features
contain a strong but limited early-game signal. The main interpretation is that early economic and combat
advantages are highly predictive, while more complex models did not substantially outperform the simpler,
interpretable logistic regression model.
