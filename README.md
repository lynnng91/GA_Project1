# GA_Project1
Project 1 for General Assembly - ACT and SAT analysis

# Problem Statement

The mission of this assignment is:

- To assess trends in ACT and SAT participation rates and performance; and
- To understand factors that affect participation rates and performance; and
- To provide recommendations to improve participation rates and performance in States where they are both low

# Executive Summary

1. SAT participation rates have grown strongly over the 2017-18 period whilst ACT participation has slightly declined

- Average SAT participation rates have grown by ~5% over the 2017-18 period, and minimum participation rates have improved from a 2% participation rate to 8%
-Average ACT participation rates have experienced a slight decline, which has mainly been due to Colorado students [favoring the SAT], which has resulted in a drop in participation from 100% in 2017 to 30% in 2018 (SAT participation rates for Colorado had increased from 11% to 100% in the same time period)

2. Average total SAT scores and ACT composite had shown a year-on-year decline, although at a lower magnitude for the ACT

-Average total SAT scores decreased to 1120 in 2018 from 1126 in the previous year, however min-max for total scores had improved. This suggests that whilst there are better candidates in this cohort compared to the previous year, there is a larger population of the cohort at the lower end of the spectrum (which is shown by a lower 50% percentile result)
-There was a small decline in average composite scores for the ACT (from 21.51 to 21.49) however is negligible given its low magnitude. Candidates at the lower end of the spectrum showed some improvement, with 25% quartile scores showing a ~0.2 score improvement.

3. Median household income and overall ethnicity of the state has little influence on overall participation rates and performance

- Median household income showed little correlation to test participation rates and performance – which is a surprise as the initial hypothesis was that states that are more affluent would be able to afford additional tuition and test fees which would boost test performances and participation rates

- Overall ethnicity also had little influence however this may be because the lower class ethnicity groups are not enrolled in school to begin with and is not considered within the population

4. However, the ethnicity distribution of the candidate group seemed to influence test scores

- Although data was limited, using the SAT 2018 candidate data, there was a strong correlation between student ethnicity and test scores – where states with a higher white population scored higher than states with a low to middle ratio of white population

- In 2018, Colorado and Illinois switched over from ACT to SAT which has resulted in participation rates for the SAT to drastically increase from 2017-18


5. In the past, state policy has been fairly successful in influencing participation rates and could be exercised to further encourage students to participate in standardized testing

- To encourage higher participation rates, the College Board could encourage colleges to ensure potential applicants take a mandatory testing, or increase state funding to encourage students to participate or use state funding to provide additional tuition for the students who would otherwise not participate due to the lack of self-confidence.

- Given that most colleges are moving away from standardized test scores, the best option may be to use funding and policies to influence participation rates

# Data dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|US State|
|act2017_participation|float|ACT|State participation rate in percentage terms in 2017|
|act2017_english|float|ACT|ACT English Scores in 2017|
|act2017_math|float|ACT|ACT Math Scores in 2017|
|act2017_reading|float|ACT|ACT Reading Scores in 2017|
|act2017_science|float|ACT|ACT Science Scores in 2017|
|act2017_composite|float|ACT|ACT Composite Scores in 2017|
|sat2017_participation|float|SAT|State participation rate in percentage terms in 2017|
|sat2017_reading_writing|int|SAT|SAT Evidence-Based Reading and Writing Scores in 2017|
|sat2017_math|int|SAT|SAT Math Scores in 2017|
|sat2017_total|int|SAT|SAT Total Scores in 2017|
|act2018_participation|float|ACT|State participation rate in percentage terms in 2018|
|act2018_english|float|ACT|ACT English Scores in 2018|
|act2018_math|float|ACT|ACT Math Scores in 2018|
|act2018_reading|float|ACT|ACT Reading Scores in 2018|
|act2018_science|float|ACT|ACT Science Scores in 2018|
|act2018_composite|float|ACT|ACT Composite Scores in 2018|
|sat2018_participation|float|SAT|State participation rate in percentage terms in 2018|
|sat2018_reading_writing|int|SAT|SAT Evidence-Based Reading and Writing Scores in 2018|
|sat2018_math|int|SAT|SAT Math Scores in 2018|
|sat2018_total|int|SAT|SAT Total Scores in 2018|
|hh_income17|float|-|Median Household Income by State in 2017|
|percentage_white|float|-|Percentage of White Ethnicity Households by State in 2017|
|percentage_asian|float|-|Percentage of Asian Ethnicity Households by State in 2017|
|white_students|float|-|Percentage of White Ethnicity Students enrolled in SAT by State in 2018|

# Conclusions and Recommendations

For States with low participation such as Minnesota that has a very low SAT participation rate at the moment at 4%, a suggestion for the College Board would be to actively encourage participation rates through public funding for tests, or to ensure college testing is mandatory for all college students.

To inform my investigations, additional data that could be interesting to explore are candidate information such as gender, first language of student, student's parent's highest education, average student teacher ratios, students' choice of university and degree, as well as % of students that has participated as a result of state funding (to understand if funding has been effective in increasing participation). All of these could be interesting to further understand how graduating seniors make their decision between participating in college tests and as to which test they take.
