# Inclusive Activity-Based Learning (ABL) Assessment in Mathematics
## Project Overview
This project focuses on assessing the impact and inclusivity of Activity-Based Learning (ABL) methods in supporting Mathematics education within selected public secondary schools in Dar es Salaam, Tanzania.

The analysis relies on survey data collected from teachers regarding their knowledge and challenges, combined with student pre-test and post-test scores, to determine the overall effectiveness and equitable benefit of the ABL intervention.

# Specific Objectives and Analysis Performed
The analysis was structured around three specific research objectives:

| Objective | Analysis Performed | Key Variables | | 1. Explore Teacher Knowledge | Pearson Correlation | Knowledge_Score vs. Performance_Gain | | 2. Identify Teacher Challenges | Mean Score Ranking & Pearson Correlation | Challenge_Score vs. Performance_Gain | | 3. Assess Performance Enhancement & Inclusivity | ANCOVA (Type II) & Visual Analysis | Post_Test_Score controlled by Pre_Test_Score and grouped by Gender or Training Status. |

# Methodology Summary
**Data Integration:** Four primary CSV files (Demographics, Knowledge, Challenges, and Student Impact) were loaded.

**Feature Engineering:** Teacher-level Likert scores were calculated to create composite variables (Knowledge_Score and Challenge_Score).

**Teacher ID Imputation:** Due to missing explicit student-teacher linking, students (N=79) were sequentially assigned to the available teachers (N=27) in a cyclical fashion.

**Data Filtering:** Student records linked to the missing Teacher ID 1 were excluded from analyses requiring teacher variables (reducing sample size to N=76 for these specific tests).

**Statistical Modeling:** ANCOVA was used to assess factor effects while controlling for the strong influence of the baseline (Pre_Test_Score).

# Key Findings (Based on Analysis)
| Finding | Statistical Result | Implication | | Performance Enhancement | Strong visual evidence (Dot Plot) | ABL successfully leads to significant individual learning gains for students. | | Gender Inclusivity | ANCOVA Gender p=0.8616 (Not Significant) | The intervention is equitable; gender does not significantly predict differential performance gain. | | Teacher Training Impact | ANCOVA Training p=0.7411 (Not Significant) | Whether a teacher received the measured training does not significantly affect student outcomes. | | Teacher Knowledge Influence | Correlation r=−0.050, p=0.6660 (Not Significant) | Teacher's measured knowledge level did not correlate with student performance gain. | | Top Challenges | Bar chart visualization | Key obstacles identified were Lack of Resources, Time Constraints, and Large Class Size. |

# Visualization Highlights
The analysis produced three key visualizations crucial for interpreting the results:

**Paired Pre/Post-Test Dot Plot:** Shows the individual transition of every student's score, providing compelling evidence of the overall positive intervention effect.

**Top 5 Challenges Horizontal Bar Chart:** Clearly ranks the obstacles teachers most strongly agree they face, with Lack of Resources being the top-ranked issue.

**Performance Gain Box Plot:** Visually compares the distribution of learning gains between different student cohorts (e.g., Inclusive Status), supported by statistical annotation for significance testing.
