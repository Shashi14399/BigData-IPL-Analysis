# BigData-IPL-Analysis
Simulating an entire IPL match ball by ball using the previous matches given the batting and bowling order of both the teams.
This project gives ball by ball predictions of a given match. Ball to ball commentry of previous IPL matches data obtained from ESPN cricinfo was used to train the model and obtain probability of 0,1,2,3,4,5,6 runs and out in that ball for a particular batsmen-bowler pair(pvp CSV file).
K-Means Clustering and Collaberative filtering was used to obtain two other CSV files. These are used if a particular batsmen-bowler pair not present in the pvp.csv
