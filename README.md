# School District Analysis
## Overview 
The purpose of this analysis is to evaluate school distric performance of high school students in math and reading. The school board would like a better understanding of performance metrics and evaluate academic honesty. There appears to be some anomalies in the data in respect to Thomas High School's math and reading scores for the 9th grade students. The school board would like the analysis to include the replacement of the math and reading scores for Thomas High School with "NaNs" while keeping the rest of the data intact to describe how these changes affected the overall analysis.


## Results
After replacing Thomas High School 9th grade's test scores with "NaNs" (as shown below), the analysis was repeated and a district summary dataframe created. 
The district analysis summary was not affected by the update to the 9th grade test scores. 

**Images will display original first, update second.**

![Original district summary](https://github.com/courtneysims/School_District_Analysis/blob/877f300fcf408f04df29fe6022a92b339534aeee/Resource/district_summary_original.png)
![Updated district summary (NaNs)](https://github.com/courtneysims/School_District_Analysis/blob/b21b88522213e05f0785baece301c7e6dba0dee8/Resource/district_summary_update.png)

The changes of replacing the grades with "NaNs" for 9th grade at Thomas High School also did not affect the ranking of the top performing schools which ranked Thomas High School in the top five.
![Top Rank Original](https://github.com/courtneysims/School_District_Analysis/blob/b21b88522213e05f0785baece301c7e6dba0dee8/Resource/top_schools_original.png) ![Top rank Update](https://github.com/courtneysims/School_District_Analysis/blob/962ee5821b12b0a0069594864e4c80e40a854c3c/Resource/top_schools_update.png)

The only scores impacted by the change is the dataframe displaying test scores by grade which lists "NaNs" for 9th grade at Thomas High School. Calculating an average of the math and reading scores with the update would return a noticeable change because a whole grade's data is not represented by the omission. For the overall school performance in math and reading,  passing percentages for reading and math scores for all grades show a small change in this metric, less than 0.5%. Compared to other school performances in test scores, the replaced 9th grade test scores do not affect Thomas High School in math and reading.

![math scores by grade Original](https://github.com/courtneysims/School_District_Analysis/blob/962ee5821b12b0a0069594864e4c80e40a854c3c/Resource/math_score_original.png) ![math scores by grade update](https://github.com/courtneysims/School_District_Analysis/blob/962ee5821b12b0a0069594864e4c80e40a854c3c/Resource/math_scores_grade_update.png)

![reading scores by grade original](https://github.com/courtneysims/School_District_Analysis/blob/962ee5821b12b0a0069594864e4c80e40a854c3c/Resource/reading_score_original.png)![reading scores by grade update](https://github.com/courtneysims/School_District_Analysis/blob/962ee5821b12b0a0069594864e4c80e40a854c3c/Resource/reading_score_grade_update.png)

The impact on scores for the metrics: school spending, school size, and school type did not return appreciable changes as well. 







## Summary
The analysis is unable to determine the degree of academic dishonesty to Thomas High School 9th grade math and reading scores. However, The updated analysis shows small changes of less than 0.5% in performance metrics. For scores by school spending, there is no change. The school size, representing Thomas High as a medium size school, is also not noticeably affected by the omitted graded. Finally, scores by school type, charter, are not noticeably affected by the omitted grades. The overall performance of Thomas High School for math and reading is not affected with the school maintaining the same ranking. 
