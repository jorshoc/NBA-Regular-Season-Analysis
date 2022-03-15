# NBA Regular Season Analysis Overview
##### Goal:
- Accurately predict NBA teams' regular season records
- Determine the impact that Dean Oliver's Four Factors - shooting percentage, turnovers, offensive rebounds and free throw rate - have on an NBA team's regular season record

##### Project Sections: 
1. Import Packages
2. Clean Data
3. Expore Data with Visualizations
4. Train and Test an MLR Model

##### Data:
- Downloaded from https://cleaningtheglass.com/
- 150 observations: 30 NBA teams' data from the following 5 regular seasons: 2014-2015, 2015-2016, 2016-2017, 2017-2018, and 2018-2019 
- Our data contains the following 9 variables:
    - Wins: Number of wins a team had in a given season
    - EFG: A team's effective field goal percentage in a given season
         - Effective field goal percentage is closely related to field goal percentage, which is the percentage of attempted shots that were made
    - TPP: A team's turnover per possession percentage in a given season
    - ORP: A team's offensive rebounding percentage in a given season
         - Offensive rebounding percentage is percentage of a team's own misses that they rebounded
    - FTR: A team's free throw rate in a given season
         - FTR is the number of free throws a team made per 100 field goal attempts
    - OEFG: A team's opponents' EFG in a given season
    - OTPP: A team's opponents' TPP in a given season
    - OORP: A team's opponents OORP in a given season
    - OFTR: A team's opponents OFTR in a given season
