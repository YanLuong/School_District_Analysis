# School District Analysis

### Overview of the school district analysis


----

### Results

After the Thomas High School ninth grade results were replaced with NaNs, the school district analysis was repeated to see how the changes have impacted the analysis across the board. The results will address the following bulleted points:

* #### District Summary
  In the district summary, there has been a slight drop across nearly all the metrics. The most noticeable decrease is in the *'% Overall Passing'* where it decreased from 65.2% to 64.9%. Please see results below, with the first image showing the results prior to altering the Thomas High School 9th grade and the latter after alteration.
  
  
  ![district summary before clean](https://github.com/YanLuong/School_District_Analysis/blob/main/Resources/District%20Summary%20df%20before%20cleaning.png)
  

  ![district summary after THS clean](https://github.com/YanLuong/School_District_Analysis/blob/main/Resources/District%20Summary%20Clean.png)

* #### School Summary
  In the School Summary, Thomas High School remains in second position. It is in the top 5 performing high schools (by '% Overall Passing') in this analysis even after the ninth grade data was altered. As expected, there was a decrease across the average math and reading scores and the passing percentages. The *'% Overall Passing'* results for Thomas High School was previously at 90.94% which decreased to 90.63% after altering Thomas High School's 9th grade data. The decreases are quite small overall, due to Thomas High School 9th grade students (461 students) accounting for a small proportion (1.17%) of the total number of students of 39170. 
  
  ![school summary after THS clean](https://github.com/YanLuong/School_District_Analysis/blob/main/Resources/School%20Summary%20Cleaned%20top5.png)
  

* #### How did replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  Replacing the ninth grade math and reading scores did pull down their overall performance but it's decrease is insignificant especially in comparison to the other schools. The impact was not large enough for the school to drop in position when ranked by *% Overall Passing*.


* #### How did replacing the ninth-grade scores affect the following:
    - ##### Math and reading scores by grade:
        In the Math and Reading scores by grade, we can see the 'NaN' replacement appear in the data frame for Thomas High School ninth grade student scores in both Math and Reading. Please see below image for the Math score by grade and highlighting the 'NaN' entry for the ninth grade scores.
        
        
        
        
        ![Math score by grade](https://github.com/YanLuong/School_District_Analysis/blob/main/Resources/Maths_by_grade.png)
        
        
        
    - ##### Scores by school spending:
         We can see that after the ninth grade scores were adjusted that there was a very small impact on the scores by school spending. Thomas High School falls in the $630-$644 spending range so that is where the impact is seen. The difference in score is only noticeable in the decimal. If we were to refer to the formatted dataframe (without decimals) then we would not see any difference at all as the decrease was so minor. Refer to the first screenshot (non formatted to show the decimals) to see the difference prior to removing ninth grade scores and the latter image showing the scores after replacing the ninth grade scores. Altering the ninth grade scores dropped the '% Overall Passing' by 0.08 in the score by school spending analysis.
         
         ![Scores by spending](https://github.com/YanLuong/School_District_Analysis/blob/main/Resources/Score_by_spending_with_THSninthgrade.png)
         
         ![Scores by spending cleaned](https://github.com/YanLuong/School_District_Analysis/blob/main/Resources/Score_by_spending_clean.png)
         
         
         
         
         
    - ##### Scores by school size:
        Thomas High School is a medium sized school so the changes made to the ninth grade scores will have affected the medium sized school scores. As with all the other analysis, the decrease in scores is very subtle and again, only noticeable in the decimals. The '% Overall passing' dropped by 0.07 after the ninth grade score replacement.     

    - ##### Scores by school type:
        Thomas High School is a charter school so any adjustments made to the ninth grade scores from Thomas High School would affect the charter school scores specifically. The difference is barely noticable and it is only when you consider the decimals that you see the decrease of 0.04 in the '% Overall Passing' score. 
    
-----    
    
### Conclusion
Overall, replacing the ninth grade scores for Thomas High School in the School District Analysis had an impact across all the analysis.
  1. The biggest change can be seen directly in the Thomas High School summary performance. Not including the ninth grade scores dragged the scores down in maths and reading for the school. The change can be seen in the '% Overall Passing' as it decreased from 90.94% to 90.63%.
  2. In the District Summary, the most noticeable change is in the '% Overall Passing' as it's score decreased from 65.2% to 64.9%. To get a better idea of how significant this is, we would need more comparison data like data from the previous years or data from other districts to compare. The decrease in scores also appear to be more significant in maths than reading.
  3. When referring to the grade by scores analysis, we see can the ninth grade scores for Thomas High School are replaced with NaNs which stands out in the data. Whereas in the School Summary and District Summary, the ninth grade results can be masked and the decrease is subtle.  
  4. Another change worth mentioning, is the Scores By School Size analysis also saw a drop in their '% Overall Passing' score. This score decreased from 90.62% to 90.55%. What is interesting to note, is that all the medium sized school happen to be charter schools with '% Overall Passing' score in the 90% range or close to it. 



