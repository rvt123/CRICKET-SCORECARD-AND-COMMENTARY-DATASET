# CRICKET-SCORECARD-AND-COMMENTARY-DATASET
Match Scorecard and Commentary Data from 2017 for ODI, Test, T20, IPL, BBL, PSL.
This Dataset is also available on Kaggle: https://www.kaggle.com/raghuvansht/cricket-scorecard-and-commentary-dataset
Due to large file size Commentary files could not be added here please visit the Kaggle Dataset link.

Cricket is being played for ages. Cricket was halted due to Corona Virus and it resumed again. But the Dataset we have is ages old so, I Raghuvansh Tahlan an aspiring Data Scientist and an avid Cricket lover bring you my Personal Cricket Dataset which covers Matches from 2017 till Pre-COVID(2020). The Dataset is 3 fold first a CSV file containing each row for a Match, then Batting and Bowling Scorecard CSV files for each match and a CSV file per match containing ball-by-ball commentary for each match.
The data covers International Matches(ODI, T20, Test Match) and leagues namely Indian Premier League(IPL), Big Bash League(BBL) and Pakistan Super League(PSL).
The Dataset covers over 1200 Cricket Matches.

UNDERSTANDING THE DATA
"INTERNATIONAL_MATCH.csv" contains one row per match and contains Superficial data for each match i.e. Name of the teams, Unique ID for each team, Venue, Venue Unique ID, Date of the Match, Result of the Match and most importantly "MATCH NUMBER". This number matches with the scorecards files and commentary files.

The "BATTING" folder contains batting scorecard CSV files. The name of every file in the Batting folder is named as "XXBATTINGSCORECARD.csv" where "XX" is the "MATCH NUMBER".
The "BOWLING" folder contains bowling scorecard CSV files. The name of every file in the Bowling folder is named as "XXBOWLINGSCORECARD.csv" where "XX" is the "MATCH NUMBER".

"COMMENTARYINTLMATCH" folder contains Ball-by-ball commentary CSV files. The name of every file in the Commentary folder is named as "XX_COMMENTARY.csv" where "XX" is the "MATCH NUMBER".

Let's Understand the structure by an example:
A row in the "INTERNATIONALMATCH.csv" file contains match number as "12345" then it's Batting Scorecard CSV file will be in "BATTING" folder named as "12345BATTINGSCORECARD.csv", Bowling Scorecard CSV file will be in "BOWLING" folder named as "12345BOWLINGSCORECARD.csv", and Commentary CSV file will be in "COMMENTARYINTLMATCH" named as "12345COMMENTARY.csv".

I would like people to come up with kaggle Kernels and Analyze the Data and mention me when you use the data and I will try to keep the Dataset as updated as possible. I can be reached at:
LinkedIn: https://www.linkedin.com/in/raghuvansh-tahlan/
Medium: https://medium.com/@raghuginnu
