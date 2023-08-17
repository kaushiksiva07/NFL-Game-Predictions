## NFL-Game-Predictions

Predicts winner of an NFL game. Primarily focuses on using Expected Points Added which is the idea that having the ball closer to your opponent's endzone is better than possessing it further away.
This value is computed at the begginning of every play and tells us what is the expected number of points that team will gain from completing this play successfully. This value can take on both postiive and negative values.
For example, if a team is 1st and 10 on their own 1 yeard line, they would have a negative EPA since the opponent is more likely to score next. Using this measurement, EPA was calculated for passing and rushing plays for both
offense and defense. This was then adjusted for the strength of the opponent and a rolling average was used so that we can form better predications as the season progresses. Addionally, through some EDA, it was found that 
passing offense was the most influential feature so Completion Percentage Over Expected was incorporated to account for QB performance as well as the Point Differential between teams.
