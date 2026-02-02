# epl-2018-2019-data-analysis

Attendance Analysis

Which home team has the highest average attendance?

df.groupby('home_team_name')['attendance'].mean().sort_values(ascending=False)


How would you get the stadium name along with that average attendance?

Goals Analysis

Which match had the most total goals?

df.loc[df['total_goal_count'].idxmax()]


How to calculate average goals per game for each team?

Cards & Fouls

Which team got the most yellow cards at home?

Calculate the total number of red cards per match.

Shots & Possession

How to find the team with the highest average shots on target at home?

Compare home vs away possession: average possession per team.

xG & Pre-Match Stats

Which team had the highest average pre-match xG at home?

How to calculate the correlation between Pre-Match PPG and actual goals scored?

Odds & Betting Stats

Which matches had the highest over 2.5 goals probability based on odds?

Find matches where btts_percentage_pre_match > 70%.

Time-Based Analysis

How to find the average number of goals in the first half?

Which Game Week had the highest total goals?
