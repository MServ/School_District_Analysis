# School_District_Analysis
Analysis of standardized test data and student funding for a school system

## Analysis Overview
This analysis was done to check whether there was any academic dishonesty among the ninth grade students at Thomas High School(THS). Their math and reading grades were replaced with null values to see how this would affect the overall analysis.

## Results
There were no significant differences in the results noted by excluding the grades of the ninth graders from THS.
- The district summary was unaffected ![Initial district summary](/Resources/Initial_District_Summary.png) ![New district summary](/Resources/New_District_Summary.png)
- The school summary was unaffected ![Initial school summary](/Resources/Initial_Per_School_Summary.png) ![New school summary](/Resources/Initial_Per_School_Summary.png)
- THS performance was relatively unaffected compared with other schools, only a fraction of a digit changed ![Initial performance](/Resources/Initial_High_Low_Performing.png) ![New performance](/Resources/New_High_Low_Performing.png)
- The math and reading scores by grade were unaffected other than showing NaN(null) for THS ninth graders ![Initial math scores by grade](/Resources/Initial_Math_Scores_by_Grade.png) ![New math scores by grade](/Resources/New_Math_Scores_by_Grade.png) ![Initial reading scores by grade](/Resources/Initial_Reading_Scores_by_Grade.png) ![New reading scores by grade](/Resources/New_Reading_Scores_by_Grade.png)
- Scores by school spending, school size, and school type were all unaffected ![Initial scores by school](/Resources/Initial_Spending_Summary.png) ![New scores by school](/Resources/New_Spending_Summary.png) ![Initial scores by size](/Resources/Initial_Scores_by_Size.png) ![New scores by size](/Resources/New_Scores_by_Size.png) ![Initial scores by type](/Resources/Initial_Scores_by_Type.png) ![New scores by type](/Resources/New_Scores_by_Type.png)

## Summary
Some changes between the general analysis in ![PyCityChallenge_testing](PyCityChallenge_testing.ipynb) and the analysis of academic dishonesty ![PyCityChallenge](PyCityChallenge.ipynb) were:
- Replaced THS ninth grader scores with null/NaN, which was directly seen in the math and reading scores by grade
- Used the .loc() function in numerous places to find and/or edit certain data
