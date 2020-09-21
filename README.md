# School_District_Analysis


## Overview of School_District_Analysis

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. She has asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the math and reading scores have been replaced, Maria would like us to repeat the school district analysis that we did in this module and write up a report to describe how these changes affected the overall analysis.

## Resources
- Data Source: schools_complete.csv , students_complete.csv
- Software: Python 3.8.3, Jupyter notebook, 6.0.3

## School_District_Analysis Results:
The analysis of the School_District_Analysis show that:
- How is the district summary affected?
  By substracing grade 9th from total student, Total number of sudent in district summary decrised to 38709. All scores in reading and math decrised slightly by decimal amount.
  
- How is the school summary affected? Changing reading and math scores of garde 9th to nan for Thomas High School,droped the passing percentages significantly. % Passing_Reading : 69.6636  % Passing_Math :66.9113,  However after replacing the % Passing_Reading ,% Passing_Math and % Overall_Passing with amounts for grades 9th-12th , its perfomance increase and went up very close to the perevious amounts and again took the second position among other schools.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Before changing the scores with nan, Thomas High School was in the second place based on the performance. After changing to nan, Thomas High School changed its position and falles close to the bottom 5 of the list. However after replacing the % Passing_Reading ,% Passing_Math and % Overall_Passing with amounts for grades 9th-12th , its perfomance increase and went up very close to the perevious amounts and again took the second position among other schools.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  It did not affect Math and reading scores by grade.
  - Scores by school spending
  It did not affect scores by school spending.
  - Scores by school size
  It did not affect scores by school size.
  - Scores by school type
  It did not affect scores by school type.

## School_District_Analysis Summary
 Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
 According to the pictures,Total number of students decrease to 38709, Average math and reading scores decreased . Also percentage pass of reading , math and overall passing droped slightly.

![district summary:](School_District_Analysis/district_summary.png)
![new district summary:](School_District_Analysis/new_district_summary.png)

