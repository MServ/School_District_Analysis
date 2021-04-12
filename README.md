# School_District_Analysis
Analysis of standardized test data and student funding for a school system

## Analysis Overview
This analysis was done to check whether there was any academic dishonesty among the ninth grade students at Thomas High School(THS). Their math and reading grades were replaced with null values to see how this would affect the overall analysis.

## Results
There were no significant differences in the results noted by excluding the grades of the ninth graders from THS.

### District summary
- The district summary was unaffected ![Initial district summary](/Resources/Initial_District_Summary.png) ![New district summary](/Resources/New_District_Summary.png).

### School Summary
- The school summary was unaffected ![Initial school summary](/Resources/Initial_Per_School_Summary.png) ![New school summary](/Resources/Initial_Per_School_Summary.png)

### High vs. Low Performing Schools
- THS performance was minorly affected compared with other schools ![Initial performance](/Resources/Initial_High_Low_Performing.png) ![New performance](/Resources/New_High_Low_Performing.png). The math and reading scores, as well as the percent of students passing math and reading, both individually and combined, were slightly higher for the initial analysis, which contained the ninth graders' scores. Before removing ninth graders average math scores were 0.06% higher, average reading scores were 0.05% lower, percent of students passing math were 0.09% higher, percent of students passing reading were 0.29% higher, and overall percent of students passing both math and reading were 0.32% higher.

### Math and Reading Scores by Grade
- The math and reading scores by grade were unaffected other than showing NaN(null) for THS ninth graders ![Initial math scores by grade](/Resources/Initial_Math_Scores_by_Grade.png) ![New math scores by grade](/Resources/New_Math_Scores_by_Grade.png) ![Initial reading scores by grade](/Resources/Initial_Reading_Scores_by_Grade.png) ![New reading scores by grade](/Resources/New_Reading_Scores_by_Grade.png)

### Scores by School Spending, School Size, and School Type
- Scores by school spending, school size, and school type were all unaffected ![Initial scores by school](/Resources/Initial_Spending_Summary.png) ![New scores by school](/Resources/New_Spending_Summary.png) ![Initial scores by size](/Resources/Initial_Scores_by_Size.png) ![New scores by size](/Resources/New_Scores_by_Size.png) ![Initial scores by type](/Resources/Initial_Scores_by_Type.png) ![New scores by type](/Resources/New_Scores_by_Type.png)

## Summary
There were no major changes between the general analysis in ![PyCityChallenge_testing](PyCityChallenge_testing.ipynb) and the analysis of academic dishonesty ![PyCityChallenge](PyCityChallenge.ipynb). There were only minor differences between the two analyses, as seen in the High and Low Performing Schools. These differences were in slightly higher math scores, slightly lower reading scores, and higher percent of students passing math and reading, both individually and combined. It does seem strange that the decreased score for reading resulted in a higher percent of students passing. However, given the fractional differences, there is no significant evidence of academic dishonesty.
