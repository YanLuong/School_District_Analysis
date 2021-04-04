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


* #### How does replacing the ninth-grade scores affect the following:
    - ##### Math and reading scores by grade:
           In the Math and Reading scores by grade, we can see the 'NaN' replacement appear in the data frame for Thomas High School ninth grade student scores      in both Math and Reading. Please see below image for the Math score by grade.
        
        
        
        
        ![Math score by grade](https://github.com/YanLuong/School_District_Analysis/blob/main/Resources/Maths_by_grade.png)
        
        
        
    - Scores by school spending
    - Scores by school size
    - Scores by school type

Conclusion




