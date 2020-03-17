# Project Title

This project is analyzing data for experimental study with 3X2 factorial design to understand user's perception of AI, human and human aided by AI moderators. The experiment involve two studies for three countries: US, Poland and Spain.

## Getting Started

Copy the project using git hub link and you can proceed to run individual files for each study for each country. 

### Prerequisites

install packages ggplot2, dplyr, ggpubr

```
install.packages("ggpubr")
```


### Break down into end to end tests

We first conduct randomization test for each dataset for variables like age, sex, education, gender, AI awareness etc. The analysis invlove OSL regression models using dummy variables by controlling for variables which are not randomly distributed among three conditions specially for US.
Post hoc analysis is performed to see the results for pairwise comparision.
