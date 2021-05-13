# PyCitySchools with Pandas

## Overview of the School District Analysis
Maria, a school disctrict data scientist, requested our help to gather all standardized test data in the district for analysis. We needed to aggregate the raw data about student test scores, school spending, school size, and school type to show trends in school performance. This analysis will be used by the school board to make decisions about future school budget allotments. However, after our initial analysis was delivered, the school board noticed academic dishonesty within the ninth grade test scores at Thomas High School. We were then tasked with replacing the ninth grade scores at Thomas High School with "NaN's" while not affecting the rest of the data. The school district analysis was then be repeated and any changes in the analysis were described. 

## Resources
- Data Source: students_complete.csv
- Software: Anaconda 4.10.1, Python: 3.9.4, Jupyter Notebook

## Results
### District Summary Differences
#### Original District Summary
![Image of Original District Summary](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/Original_District_Summary.png)

#### New District Summary
![Image of New District Summary](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/New_District_Summary.png)

- Repeat analysis showed the following changes in the district summary:
  - Average math score decreased by 0.1
  - Percentage of students passing math decreased by 0.2
  - Percentage of studnets passing reading decreased by 0.3
  - Percentage of studnets passing both math and reading decreased by 0.1

### School Summary Differences
#### Original School Summary
![Image of Original School Summary](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/Original_School_Summary.png)


#### New School Summary
![Image of New School Summary](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/New_School_Summary.png)

- Repeat analysis showed the following changes in the individual summary for Thomas High School:
  - Average math score decreased by 0.07
  - Average reading score increased by 0.05
  - Percentage of students passing math decreased by 0.08
  - Percentage of studnets passing reading decreased by 0.29
  - Percentage of studnets passing both math and reading decreased by 0.32

### Thomas High School Updated Performance
![Image of Top Five Schools](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/Top_Five_Schools_1.png)

- Repeat analysis showed that Thomas High School is still the second highest performing school in the district based on the percentage of students passing both math and reading standardized tests. Although the overall passing rate decreased to 90.63% once all the flawed ninth grade scores were removed, Thomas High School still performed better than Griffin High School. 

### Math and Reading Scores By Grade
#### Math Scores
![Image of Math Scores](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/Math_Scores_By_Grade.png)

- This chart shows the replacement of the ninth grade math scores at Thomas High School with "NaN". However, none of the scores for grades 10-12 at Thomas High School were changed. Similarly, the data for the other schools remained unchanged.

#### Reading Scores
![Image of Reading Scores](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/Reading_Scores_By_Grade.png)

- This chart shows the replacement of the ninth grade reading scores at Thomas High School with "NaN". However, none of the scores for grades 10-12 at Thomas High School were changed. Similarly, the data for the other schools remained unchanged.

### Scores By School Spending
![Image of Scores by Spending](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/Scores_By_Spending.png)

- Repeat analysis showed no change in outcomes in scores based on school spending per student.

### Scores By School Size
![Image of Scores by Size](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/Scores_By_Size.png)

- Repeat analysis showed no change in outcomes in scores based on the number of students in each school.

### Scores By School Type
![Image of Scores by Type](https://github.com/jpb12002/School_District_Analysis/blob/main/Resources/Scores_By_Type.png)

- Repeat analysis showed no change in outcomes in scores based on the type of school (Charter vs. District).

## Summary

