# School District Analysis
## Overview of Project
The purpose of this analysis was to provide insight on high school reading and math scores across 15 high schools in one school district. The sample included 39,170 students. Results were first cleaned to removed unnecessar prefixes and suffixes from student names. Average scores and passing percentages were calculated for the entire district and within each school. Average scores and passing percentages were further analyzed by grade within each schools, school budget, school size, and school type. This process was completed twice. The first was completed with the entire sample. The second was conducted omitting scores of 461 9th grade students from Thomas High School. This report illuminates on how removing data can alter results. 

## Results 
### District Summary Results 
**District summary with complete data**
![District Summary 1](/images/district_summary_no.jpg)
District summary with omission of Thomas High School ninth graders
![District Summary 2](/images/district_summary_ths.jpg)
- There are differences in average math scores (change of 0.1), and percentages in students passing math (0.2%) and overall (0.1%). These difference may show the Thomas High School ninth graders contributed to a higher average math score. The change in percentage may have resulted in the inconsistency between decimal places. Oddly, while the average reading score is the same, there is a decrease of 0.3% in the percentage in students passing reading after the omission of the ninth grade sample. This again could be due to the inconsistent formatting. 

### School Summary Results 
**School summary with complete data**
![School Summary 1](/images/school_summary_no.jpg)
**School summary with omission of Thomas High School ninth graders**
![School Summary 2](/images/school_summary_ths.jpg)
- Similarly to the district analysis, the school summary analysis is inconsistent with significant digits across the two samples. While the differences are small, it is difficult to determine if it is a difference in average score or if it is a difference due to rounding errors.

### Performance Comparison 
Despite removing the ninth grade scores from Thomas High School, the school still remains the second top performing school of the sample. 

### Math Average Scores by Grades
**School summary of math average scores with complete data**

![School Summary Math Scores 1](/images/grade_summary_math_no.jpg)

**School summary of math average scores with omission of Thomas High School ninth graders**

![School Summary Math Scores 2](/images/grade_summary_math_ths.jpg)

- Since the ninth grade scores from Thomas High School have been removed from the sample, the difference between the averages is that there is no average for ninth grade for Thomas High School. 

### Reading Average Scores by Grades
**School summary of reading average scores with complete data**

![School Summary Reading Scores 1](/images/grade_summary_reading_no.jpg)

**School summary of reading average scores with omission of Thomas High School ninth graders**

![School Summary Reading Scores 2](/images/grade_summary_reading_ths.jpg)

- Since the ninth grade scores from Thomas High School have been removed from the sample, the difference between the averages is that there is no average for ninth grade for Thomas High School. 

### Summary by Spending Ranges 
**Summary by spending ranges with complete data**
![Summary Spending Bins 1](/images/by_spending_bin_no.jpg)
**Summary by spending ranges with omission of Thomas High School ninth graders**
![Summary Spending Bins 2](/images/by_spending_bin_ths.jpg)
- Scores and percentages were not affected by the omission of scores. Because the subsample of 461 student scores is about 0.0117 of the total student sample, the effects of this omission in this disaggreation of data is difficult to see, especially when metrics are rounded to the tenth place or nearest whole number.

### Summary by School Type 
**Summary by school type with complete data**
![Summary School Type 1](/images/by_school_type_no.jpg)
**Summary by school type with omission of Thomas High School ninth graders**
![Summary School Type 2](/images/by_school_type_ths.jpg)
- Similarly, scores and percentages were not affected by the omission of scores. Again, the effects of this omission in this disaggreation of data is difficult to see, especially when metrics are rounded to the tenth place or nearest whole number.





