# School District Analysis

## Overview
A school board has asked for analysis on metrics that they have received from all 9th - 12th schools in the district. One of the main focuses was on math and reading scores. We worked closely with Maria to deliver the requested report for a board meeting.

It was deteremined that the reading and math scores from Thomas High School, 9th grade, were altered due to academic dishonesty. Maria wanted to replace those grades with NaNs while keeping the previous data intact. Then run the analysis again. Below is a comparison of what changed.

## Results
  **1. How is the district summary affected?**
 
 There was a small drop in Math and Reading Score averages/percentages.
  
  > Original
![image](https://user-images.githubusercontent.com/90485451/139498026-8167dfe3-dbaa-4666-b84b-df58ee67b7e3.png)

  > Adjusted
![image](https://user-images.githubusercontent.com/90485451/139497939-c101a362-bafa-42b7-baed-285fa8c502f7.png)

#
**2. How is the school summary affected?** 

When the 9th grade scores from Thomas High School were removed, the overal passing % dropped a significant amount - 91% down to 65%.

 > Original
 > ![image](https://user-images.githubusercontent.com/90485451/139499359-0d40338a-cc9f-4366-ae89-87eb359b31eb.png)

 > Adjusted
 > ![image](https://user-images.githubusercontent.com/90485451/139500451-70080172-4fd3-49b2-b346-15ecad6672ec.png)

#
**3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

In the original chart above, Thomas High ranked 2nd in the district. After the ninth grade scores from Thomas High were adjusted, their ranked dropped to about middle bottom.

#
**4. How does replacing the ninth-grade scores affect the following:
 - Math and reading scores by grade: 9th grade scores for Thomas High now show a 'NaN' and are not included in the analysis.
 - Scores by school spending: There was a slight dip in % passing reading and % overall passing.
 - Scores by school size: There was a very small impact when 9th grade scores were changed to Null.
 - Scores by school type: Removing 9th grade scores had little affect scores by school type.

## Summary
