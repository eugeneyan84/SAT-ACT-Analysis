# Exploratory Data Analysis: SAT/ACT participation rates and scores in United States (2017 & 2018)

## Problem Statement
In this project, we analyse trends in SAT and ACT participation rates and scores across every state in the United States. We seek to identify factors that may affect participation rates and scores, and make recommendations for where resources can be channeled to for best effect.

## Executive Summary

The SAT and ACT (originally known as America College Test) are standardised tests used by high school students for college and university admissions in the U.S. They are used to gauge students' academic competence in mathematics, writing and reading. In the case of ACT, it provides additional coverage in the area of science too.

With the inception of the new content, format and scoring changes to the SAT in 2016, the College Board strives to analyse statewide participation data in order to determine where resources can be best deployed to improve SAT participation rates.


#### Key takeaways:

- Test participation rate is significantly influenced by state policy and legislation. ACT and SAT participation rates generally have a negative correlation, with more than half the states requiring at least 1 of the tests to be taken. Extra research done for 3 states (Colorado, Ohio and Alaska) to highlight the influence of state policy on the participation rates of the standardised tests.

- Participation rate for a test is negatively correlated with test scores, i.e. for states where participation rate is improved to 100%, the state-wide score means would subsequently drop by a certain degree. This is likely due to the new presence of weaker students in the test-taking cohort which would previously likely contain only students who have made plans and preparation to take the test for college admission purposes.

#### Recommendations

- In states receiving SAT School Day support, College Board should continue work together with 3rd party platforms, such as *Testive* and *Khan Academy*, to provide students with means to not only take SAT for free, but to also prepare them better for the SAT. This would help mitigate any decline in state-level mean scores, whilst helping students achieve reasonably good SAT scores on the onset of participation.

- Alaska has participation rates falling below 50%, and should be targeted for greater inclusion into the SAT School Day program. College Board should work closely with Alaska's state education department to re-emphasize the benefits of SAT, as it serves as a means for college admission into undergraduate-level degree programs in the United States.

## Data Dictionary
Based on `final.csv` combined dataset:
|Feature | Type | Origin Dataset | Description |
|---|---|---|---|
|state | object | SAT_2017 | Name of state|
|sat_participation_rate_2017 | float64 | SAT_2017 | Percentage proportion of graduating class of 2017 taking SAT |
|sat_ebrw_2017 | int84 | SAT_2017 | State-level mean score for Evidence-Based Reading & Writing (SAT) in 2017 |
|sat_math_2017 | int84 | SAT_2017 | State-level mean score for Math (SAT) in 2017 |
|sat_total_2017	| int84 | SAT_2017 | State-level mean total score (SAT) in 2017 |
|act_participation_rate_2017 | float64 | ACT_2017 | Percentage proportion of graduating class of 2017 taking ACT |
|act_english_2017 | float64 | ACT_2017 | State-level mean score for English (ACT) in 2017 |
|act_math_2017 | float64 | ACT_2017 | State-level mean score for Math (ACT) in 2017 |
|act_reading_2017 | float64 | ACT_2017 | State-level mean score for Reading (ACT) in 2017 |
|act_science_2017 | float64 | ACT_2017 | State-level mean score for Science (ACT) in 2017 |
|act_composite_2017 | float64 | ACT_2017 | State-level composite score (ACT) in 2017 |
|sat_participation_rate_2018 | float64 | SAT_2018 | Percentage proportion of graduating class of 2018 taking SAT |
|sat_ebrw_2018 | int84 | SAT_2018 | State-level mean score for Evidence-Based Reading & Writing (SAT) in 2018 |
|sat_math_2018 |  int84 | SAT_2018 | State-level mean score for Math (SAT) in 2018 |
|sat_total_2018 | int84 | SAT_2018 | State-level mean total score (SAT) in 2018 |
|act_participation_rate_2018 | float64 | ACT_2018 | Percentage proportion of graduating class of 2018 taking ACT |
|act_composite_2018 | float64 | ACT_2018 | State-level composite score (ACT) in 2018 |
|act_english_2018 | float64 | ACT_2018 | State-level mean score for English (ACT) in 2018 |
|act_math_2018 | float64 | ACT_2018 | State-level mean score for Math (ACT) in 2018 |
|act_reading_2018 | float64 | ACT_2018 | State-level mean score for Reading (ACT) in 2018 |
|act_science_2018 | float64 | ACT_2018 | State-level mean score for Science (ACT) in 2018 |

