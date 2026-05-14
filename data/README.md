# Data Folder
This folder contains raw and cleaned datasets on occupation and wage data from 2013–2016.
The original data comes from the Bureau of Labor Statistics and is retrieved from TidyTuesday.

## Codebook

|variable              |class     |description |
|:---------------------|:---------|:-----------|
|year                  |integer   | Year          |
|occupation            |character | Specific job/career           |
|major_category        |character | Broad category of occupation           |
|minor_category        |character | Fine category of occupation           |
|total_workers         |double    | Total estimated full-time workers > 16 years old           |
|workers_male          |double    |  Estimated MALE full-time workers > 16 years old         |
|workers_female        |double    | Estimated FEMALE full-time workers > 16 years old |
|percent_female        |double    | The percent of females for specific occupation |
|total_earnings        |double    | Total estimated median earnings for full-time workers > 16 years old |
|total_earnings_male   |double    | Estimated MALE median earnings for full-time workers > 16 years old |
|total_earnings_female |double    | Estimated FEMALE median earnings for full-time workers > 16 years old |
|wage_percent_of_male  |double    | Female wages as percent of male wages - NA for occupations with small sample size  |
|wage_gap              |double    | Wage difference between male and female median earnings within an occupation