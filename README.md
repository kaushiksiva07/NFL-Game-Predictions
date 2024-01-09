## NFL-Game-Predictions

This project centers around predicting the winner of NFL games using a metric called Expected Points Added (EPA). The core idea revolves around assessing the advantage a team gains by positioning the ball closer to the opponent's endzone during a play. EPA values are computed at the inception of each play, indicating the expected number of points a team might score through a successful completion. Notably, these values can be both positive and negative.

For instance, when a team starts with a 1st and 10 on their 1-yard line, the EPA is negative as the opponent is more likely to score next. The project computed EPA for passing and rushing plays concerning both offensive and defensive strategies. These computations were further adjusted to accommodate the opponent's strength. To enhance predictive accuracy over the course of a season, a rolling average approach was adopted.

Moreover, after conducting Exploratory Data Analysis (EDA), it was evident that passing offense significantly influences game outcomes. To capture quarterback (QB) performance, the metric Completion Percentage Over Expected (CPOE) was integrated. Additionally, the Point Differential between teams was considered as a crucial feature in the prediction model.
