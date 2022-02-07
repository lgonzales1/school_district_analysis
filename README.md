# School District Analysis
Analysis of data related to school district testing. 

## Overview
The purpose of this analysis was to identify variables for academic achievement of the fourteen PyCity Schools. The datasets included information regarding the school size, budget, and results of standardized tests for reading and math. We performed two analyses, an initial analysis and refractored, removing Thomas High School 9th graders's academic data. By removing these data points, any artificial inflation caused by this group's abnormally high scores can be removed so the data could be presented more accurately.

## Results
### District Summary
THS's 9th grade academic scores, in general, were higher than the school and district averages. By replacing these data points, the refractored analysis will generate lower academic results. That said, THS' 9th graders make up a small percentage of the overall district student count (461 out of roughly 39,000 students). Additionally, the averages with and without the THS 9th graders are very similar. This indicates that the differences in results to be marginal.

Comparisions with THS 9th graders included (above) and removed (below)

*Figure 1: District Summary, Pre-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/district_summary_original.png)

*Figure 2: District Summary, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/district_summary_revised.png)

### School Summary
As expected, when removing the THS 9th grade scores, the effect on per-school analysis was negligible. After omitting the THS' 9th grade scores, Average Reading increased slightly by 0.05%, % Passing Reading decreased 0.29%, while Average Math, % Passing Math, % Passing Reading, and % Overall Passing decreased very slightly.

*Figure 3: School Summary, Pre-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/school_summary_original.png)

*Figure 4: School Summary, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/school_summary_revised.png)

### Math and Reading Scores By Grade
As predicted, there was very little impact on math and reading scores when omitting the THS 9th grade results. 

*Figure 5: Math Scores by Grade, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/Math_score_by_grade.png)

*Figure 6: Reading Scores by Grade, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/Reading_score_by_grade.png)

### Scores by school spending
There was minimal effect on spending ranges when THS 9th greaders are excluded. 

*Figure 6: Scores by Spending Range, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/scores_by_spending_original.png)

*Figure 7: Scores by Spending Range, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/scores_by_spending_revised.png)


### Scores by school size
When omitting the THS 9th graders, the scores based on school size did not change. 

*Figure 8: Scores by School Size, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/scores_by_size_original.png)

*Figure 9: Scores by School Size, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/scores_by_size_revised.png)

### Scores by school type
After removing the THS 9th grade scores, the math and reading scores by school type did not change. 

*Figure 10: Scores by School Type, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/scores_by_type_original.png)

*Figure 11: Scores by School Type, Post-Adjustment*

![alt text](https://raw.githubusercontent.com/lgonzales1/school_district_analysis/main/scores_by_type_revised.png)

## Summary
In summary, removing the Thomas High School 9th grade scores had a negligible effect on the outcomes of this analysis. This is due to THS 9th graders only making up a small percentage of the overall district student count. If their scores were substantially different than those seen in the district, we would have seen a larger effect. However, THS' 9th grader scores were within range enough to not have a significant effect on our findings. While there were some differences between the two studies (tenths of a percentage point), we can conclude that THS 9th graders are aligned with other schools in the district. 
