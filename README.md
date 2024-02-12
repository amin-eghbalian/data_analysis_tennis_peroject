![My Image](images/tennis_img.jpg)
# Analysis Of Tennis Matches

This project is about analysis of tennis matches and data was gathered in two monthes from sep 2023 to oct 2023. Data set has fifteen tables about home and away team, all matches features, odds and etc. This was a raw data set that required processes from cognition of tables and contents to cleaning process and managing inappropriate contents.

## Requirements

This project requires the following modules:
- numpy
- pandas
- seaborn
- matplotlib 
- notebook

## Python Packages Used

- General Purpose: pathlib, os, and many more.
- Data Manipulation: Packages used for handling and importing dataset such as pandas, numpy.
- Data Visualization: Include packages which were used to plot graphs such as seaborn, matplotlib.

## Code structure

```
├── tennis_data_20231212
│   ├── raw_match_parquet
│   ├── raw_odds_parquet
│   ├── raw_point_by_point_parquet
│   ├── raw_statistics_parquet
│   ├── raw_teniss_power_parquet
|   └── raw_vote_parquet
├── HW10_project_data.ipynb
├── README.md
└── .gitignore
```

## Data section

* Data structure description
    - List of tables
        - home_team
        - home_team_score
        - away_ream
        - away_ream_score
        - event
        - vote
        - venue
        - tournament
        - odds
        - power
        - game
        - time
        - round
        - season
        - period
    - File formats
        - .parquet files

## Results

This analysis on one hand shows some information about players like distribution of left/right handed, ranks, correlation between height and rank and etc. On the other some analysis about matches has been done, like number of winns, number of championships for each countires and ect. For future work an ML modle will reveal more aspect of data.
