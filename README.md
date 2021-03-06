# School District Analysis 
## Project Overview
Maria, an employee of the Colorado State School Board, has asked for our team’s assistance in updating and reperforming an analysis for a data set containing various Colorado high schools reading and math scores. The School Board has asked us to clean the data set to remove math and reading scores for 9th graders at Thomas High School, as the data for this High School has been unintentionally altered. The Colorado School Board has asked for our assistance with completing the following tasks:
1. Remove the math and reading scores for 9th graders at Thomas High School
2. Create/reperform the following summaries with the updated math and reading scores:
  - A District Summary that encapsulates the following:
      -  Total Schools
      -  Total Students
      -  Total Budget
      - Average Math Score
      - Average Reading Score
      - Percentage of Students Passing Math
      - Percentage of Students Passing Reading
      - Overall Percentage of Students Passing Reading and Math
  - A School Summary showing the following items for each school:
      - Total Students
      - Total Budget
      - Average Math Score
      - Average Reading Score
      - Percentage of Students Passing Math
      - Percentage of Students Passing Reading
      - Overall Percentage of Students Passing Reading and Math   
  - Show the top 5 and bottom 5 performing schools, based on the overall passing rate
  - A summary of the average math score for each grade level from each school
  - A summary the average reading score for each grade level from each school
  - A summary of the scores based on school spending per student
  - A summary of the scores by school size
  - A summary of the scores by school type 

## Resources
- Data Source: students_complete.csv, schools_complete.csv
- Software: Python 3.6.1, Jupyter Notebook
## Results 
Based on the results of the above-listed summaries our team was able to compare the results to our original summaries to see how the removal of the Thomas High School 9th graders reading and math scores affected the following:
1.	The District Summary
2.	The School Summary
3.	Thomas High schools overall Performance
4.	Math and reading scores by grade
5.	Math and reading scores by school size
6.	Math and reading scores by type
### The District Summary
Below is our original District Summary
![ Original_District Summary]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/Original_District%20Summary.PNG )

Shown below is he updated District Summary with the Thomas High School 9th grader grades removed 
![ New_District Summary]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/New_District%20Summary.PNG )

**Results:**
-	Total School Count, Total Students, and Total budget were unchanged.
-	Average Reading Score remained unchanged.
-	The Average Math Score, Percentage Passing Math, Percentage Passing Reading, and Overall percentage Passing Math and Reading, saw a slight downturn by approximately 0.02%
### The School Summary
Below is our original School Summary.
![Original_School_Summary]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/Original_School_Summary.PNG )

Below is the updated School Summary with the Thomas High School 9th grader grades removed. 
![New_School_Summary]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/New_School_Summary.PNG )

**Results:**
-	Only difference between the two summaries was in Thomas High School results.
-	For the Thomas High School information, the Total Students, Total Budget, and Per Student Budget remained the same.
-	For The Thomas High School scores and score percentages there was a slight downturn.
-	Between the Average Math and Reading score the Average Math Score decreased the most with an approximate 0.06% decrease, thus the Percentage Passing Math and the Overall Percentage of Reading and Math dropped similarly. 
-	If we look at the School Summary before removing the Thomas High School 9th graders from the count then we see that the Passing and Overall Percentages of Thomas High School were between 65%-66%, but these low percentages were driven by the 9th graders being included in the total count driving down the overall average. See the below image that demonstrates what Thomas High school's math and reading percentage passing scores were before removing the 9th graders from the count.

![ _ Thomas_High_ w-9th Grade]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/_%20Thomas_High_%20w-9th%20Grade.PNG )

### Thomas High School Overall Performance
As shown in the images below removing the 9th graders' math and reading scores from the dataset did not change how Thomas High School ranked among the 15 schools in the data set. Thomas High School is still ranked as the second-highest school in terms of the Overall Passing Percentage.

**Original Ranking** 
![Original_School_Ranking]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/Original_School_Ranking.PNG )

**New Ranking**
![New_School_Ranking]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/New_School_Ranking.PNG )

### Math and Reading Scores by Grade
From the below images we can see the only change in scores by grade was that Thomas High School's 9th-grade scores are now 0. Removing the Thomas High School 9th graders did not change 10th – 12th-grade scores at Thomas High School, nor did it change the 9th-12th grade scores at any other school.

**Original Math By Grade**
![ Original_Math_Scores_By_Grade]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/Original_Math_Scores_By_Grade.PNG )

**New Math By Grade**
![ New_Math_By_Grade]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/New_Math_By_Grade.PNG )

**Original Reading By Grade**
![ Original_Reading_Scores_By_Grade]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/Original_Reading_Scores_By_Grade.PNG )

**New Reading By Grade**
![ New_Reading_By_Grade]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/New_Reading_By_Grade.PNG )

### Scores By School Spending
As shown below, removing the 9th grader scores from the spending analysis did not affect the spending analysis.

**Original Scores By Spending**
![ Original_Scores_By_Spending]( Link to Path )

**New Scores By Spending**
![ New_Scores_By_Spending]( Link to Path )

### Scores By School Size
As shown below, removing the 9th grader scores from the school size analysis did not affect the size analysis.

**Original Scores By School Size**

![ Original_Scores_By_Size]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/Original_Scores_By_Size.PNG )

**New Scores By School Size**
![ New_Scores_By_Size]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/New_Scores_By_Size.PNG )

### Scores By School Type
As shown below, removing the 9th grader scores from the school type analysis did not affect the type analysis.

**Original Scores By School Type**
![Original_Scores_By_Type]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/Original_Scores_By_Size.PNG )

**New Scores By School Type**
![New_Scores_By_Type]( https://github.com/lmacera/School_District_Analysis/blob/main/Resources%202/New_Scores_By_Type.PNG )

## Summary
In summary, not many aspects of our analysis changed after removing the 9th grader math and reading scores of the Thomas High School students. From the District Summary analysis, we can see the items that decreased were the Total Average Math and Reading Scores, Total Percentage Passing Math and Reading, and the Overall Percentage Passing both Math and Reading. Additionally, with the School Summary analysis, we can see Thomas High Schools Average Math and Reading Scores, Percentage Passing Math and Reading, and the Overall Percentage Passing both Math and Reading decreased. Though these items decreased from our original analysis the amounts did not decrease significantly.
