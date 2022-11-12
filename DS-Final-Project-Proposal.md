DS Final Project Proposal
================
Jennifer Osei, Harry Wang, Angelica Vina Albarrancin, William Anderson,
Riya Bhilegaonkar
2022-11-12

## Team registration and proposal

First, you will define your teams and propose a project. This proposal
should be a half-page to a page in length and include:

## The Group Members (names and UNIs)

William Anderson - waa2119 Haoyang Wang - hw2850 Jennifer Osei - jao2195
Riya Bhilegaonkar - rsb2204 Angelica Vina Albarrancin - av2718

## The Tentative Project Title:

Investigating the leading causes of death in NYC

## The Motivation for this Project:

As a group we were inspired by the historical transition of the popular
causes of death that we encountered in our epidemiology class starting
from the initial contributions of the Bills of Mortality to modern day
leading cause of heart disease. We hope to analyze the leading causes of
death in NYC over the time period of 2007-2019. From a pre-covid era
analysis we hope to avoid any confounding factors of COVID-19
infections. In particular we hope to investigate predictors that play a
role in selected causes of death.

## The Intended Final Products:

Webpage that includes visualizations and test results for the impact of
various predictors such as age, income, race, education status on
leading causes of death in NYC. Each page of the website will contain an
analysis of a predictor done by each individual in the group. The final
product will be a data story that contains reference to historical
progression of leading causes of death as informed through epidemiology.

## The Anticipated Data Sources:

Helpful NYC Health Data Resources:

-   <https://opendata.cityofnewyork.us/>

-   <https://www.health.ny.gov/statistics/>

-   <https://www.health.ny.gov/statistics/sparcs/access/>

Income data:

-   <https://www.point2homes.com/US/Neighborhood/NY/New-York-City-Demographics.html>

-   <https://www.incomebyzipcode.com/newyork>

-   <https://www.nyc.gov/site/hpd/services-and-information/area-median-income.page>

Age Data: \*
<https://health.data.ny.gov/Health/Vital-Statistics-Deaths-by-Region-and-Age-Group-by/c3ns-hz2v>

-   <https://health.data.ny.gov/Health/Vital-Statistics-Opioid-Related-Deaths-by-Age-Grou/qabx-2sqw>

-   <https://health.data.ny.gov/Health/Vital-Statistics-Suicide-Deaths-by-Age-Group-Race-/j6fz-a4ta>

## The Planned Analyses / Visualizations / Coding Challenges:

William Anderson is focusing on analyzing income as a predictor for
different diseases that are the leading cause of death in NYC by
analyzing the following:

-   Plot the correlation between income level and life expectancy

-   Conduct statistical analysis to understand if income plays a role in
    the survival probability of cancer, heart disease, and other
    diseases

-   Visualize a map of neighborhoods in NYC with certain income levels
    and the number of healthcare facilities within a certain radius

-   Stratify the leading causes of death by income level and observe
    trends

Jennifer Osei is focusing on website development & analyzing race and
education as a predictor for different diseases that are the leading
cause of death in NYC by analyzing the following:

-   Plot the correlation between race, education, etc.

-   Conduct statistical analysis to understand if race or educational
    attainment plays a role in the survival probability of cancer, heart
    disease, and other diseases

-   Visualize a map of neighborhoods in NYC by race and education with
    certain and

-   Stratify the leading causes of death by race, education and observe
    trends using plots/ dynamic plots (to visualize over time period).

-   Data permitting, also want to examine access and type of health
    insurance its relation to death outcomes.

Riya Bhilegaonkar is focusing on analyzing age as a predictor for
different diseases that are the leading cause of death in NYC by
analyzing the following:

-   Plot the correlation between age group and life expectancy

-   Visualization for leading causes of death per age group

-   Conduct statistical analysis to understand if race or educational
    attainment plays a role in various diseases:

-   Trend between age group and suicide related deaths (ANOVA,
    Regression Analysis).

-   Trend between age group and opioid related deaths (ANOVA, Regression
    Analysis).

-   Stratify the leading causes of death by age group and observe trends

## The Planned Timeline

``` r
timeline <- cbind( Dates = c("Mo Oct 31, 2022",  "Tu Nov 8, 2022", "Sa Nov 12, 2022", "By Th Nov 18, 2022", "Tu Nov 29, 2022 (12pm - 6pm)", "Tu Dec 6, 2022 (12pm - 6pm)" ), 
                   Actions = c("Inital Team Formed / Inital Project Ideas Discussed", "Project Team Members Finalized", "Final Proposal Github Link Submitted", "Complete Project Review With TA per Schedule", " Scheduled Team Discussion Colaboration Meeting - Story Board", "Scheduled Team Discussion Colaboration Meeting - Synthesis/Video Compilation"),
                   Contributor = c("All/Team","All/Team", "JO", "All/Team", "All/Team", "All/Team"))

knitr::kable(timeline) 
```

| Dates                        | Actions                                                                      | Contributor |
|:-----------------------------|:-----------------------------------------------------------------------------|:------------|
| Mo Oct 31, 2022              | Inital Team Formed / Inital Project Ideas Discussed                          | All/Team    |
| Tu Nov 8, 2022               | Project Team Members Finalized                                               | All/Team    |
| Sa Nov 12, 2022              | Final Proposal Github Link Submitted                                         | JO          |
| By Th Nov 18, 2022           | Complete Project Review With TA per Schedule                                 | All/Team    |
| Tu Nov 29, 2022 (12pm - 6pm) | Scheduled Team Discussion Colaboration Meeting - Story Board                 | All/Team    |
| Tu Dec 6, 2022 (12pm - 6pm)  | Scheduled Team Discussion Colaboration Meeting - Synthesis/Video Compilation | All/Team    |
