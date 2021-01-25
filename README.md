# School_District_Analysis
## Overview
The goal of this project is to analyze school standardized tests scores and funding in order to reveal insights. These insights are then used for strategic decisions by the school board regarding budget allocation. After I conducted an analysis using the data, the school board found evidence of academic dishonesty with Thomas High School's ninth grade math and reading scores. As a result of this, I removed those scores and redid the analysis.


# Results
   - ## District Summary
   
A district summary of all of the schools' math and reading scores looks like this:

<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/Original_District_Analysis.PNG?raw=true" width = "1200">

After I removed Thomas High School's ninth grade scores, the district summary changed to this:

<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/New_District_Analysis.PNG?raw=true" width = "1200">

We see a slight dip in the overall math and reading scores after I removed the ninth grade data.

   - ## School Summary
Here is the original school summary including all the data:
<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/Original_School_Summary.PNG?raw=true" width = "1200">

Here is the new school summary only excluding Thomas high school's ninth grade data:
<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/New_School_Summary.PNG?raw=true" width = "1200">

Just like in the district summary, we see a slight dip in both math and reading scores after I removed the data.

In both summaries, we see that Thomas High School is performing exceptionally well when compared to the district's average. It has an overall passing rate of 90% while the schools in the district have an average overall passing rate of 65%.

   - ## Ranking
A question I can ask is does removing the ninth grade scores change Thomas High School's Ranking compared to other schools?

Here is the original ranking:
<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/Original_Top_Five.PNG?raw=true" width = "1200">

Here is the new ranking:
<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/New_Top_Five.PNG?raw=true" width = "1200">

Although the % overall passing rate is slightly lower, the ranking of Thomas High School remains the same. 

   - ## Math And Reading Scores by Grade
Let's compare average scores across grades to see if there is a significant difference with ninth grade scores.

Here is Thomas High School's average math scores by grade:

<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/Math_grades.PNG?raw=true" width = "300">

Here is Thomas High School's average reading scores by grade:

<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/Reading_grades.PNG?raw=true" width = "300">

The averages for ninth grade are comparable to the other grades. 
(Once I removed the ninth grade scores, the value under "9th" naturally disappeared as well)

   - ## Scores by School Spending
I grouped the schools by their average spending per student. Removing the ninth grade scores for Thomas High School did not affect the averages here. There was a small difference in the $630-644 field but this disappeared once I rounded the values.

<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/Spending_Ranges.PNG?raw=true" width = "700">

An interesting thing to note is that the average overall passing rate for schools in Thomas High School's bucket is 63%. Compare this to the school's 90% overall passing rate.

   - ## Scores by School Size
I grouped the schools by their school size. Removing Thomas High School's ninth grade scores did not affect these averages.
<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/School_Size.PNG?raw=true" width = "700">

Thomas High School is a medium sized high school. The average overall passing rate for medium sized schools is comparable with Thomas high School's passing rate.

   - ## Scores by School Type
Lastly I grouped the schools by their type. Removing Thomas High School's ninth grade scores did not affect these averages.
<img src ="https://github.com/Kee2u/School_District_Analysis/blob/main/resources/School_Type.PNG?raw=true" width = "700">

Thomas High School is a charter school.The average overall passing rate for charter schools is comparable with Thomas high School's passing rate.

## Summary
Here are four changes from removing the ninth grade math and reading scores:
 - Removing the ninth grade scores decreased the overall passing rate of the school in the district and school summary. 
 - This decrease in overall passing rate brought it closer to the third ranked school (Ranked by overall pass rate)
 - The passing percentages for the school summary were considerably affected when I dropped the ninth grade scores. This is because the calculation of the passing percentage took all the students into account but ignored the ninth grade scores. This resulted in very low passing percentages. I fixed this by subtracting the number of ninth grade students from the total number of students.
 - Removing the ninth grade scores also removed the ninth grade average math and reading scores from the "Math and Reading Scores by Grade" part of my analysis and replaced them with Nan.

 
