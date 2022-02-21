# School-District-Analysis
## Overview of School District Analysis
 school district asked for a snapshot of several key metrics by each school campus and by the district level. The main analysis focused on the performance of math and reading scores in preparation for a meeting. However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect of cheating. The school board asked for the data to be removed and analyzed again for a comparison.
## Results
#### How is the District summary affected?
- Original Analysis:
The testing data of 461 9th graders at Thomas High School was turned into null data, which recalculated the percentages of passing math, passing reading, and the overall passing. The total count of students did not change as that was run on the count of the student ids, which was not turned into null data.
- Adjusted Analysis:
When comparing the two charts, removing less than 500 test scores had a nominal impact on the almost 40,000 student data set. The change was less than a 1% difference and the numbers would still round to the same whole number.

#### How is the School summary affected?
- Original Analysis:
In the original analysis, Thomas High School started with a high overall passing rate, which was a concern to the school board as being too high. After calculating the total number of 10th - 12th grade students as the new denominator, we adjusted the numbers accordingly.

- Adjusted Analysis:
Removing the 9th grade students from the data set had a large impact by dropping from 81% to 65% for the overall passing rate.

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Original Analysis:
In the original analysis, Thomas High School ranked very high in the district raising red flags with the school board.

- Adjusted Analysis:
After adjusting the 9th grade data, Thomas High School ranked within the average ranking.


#### How does replacing the ninth-grade scores affect the following:
- Math and Reading Scores by grade
Adjusted Averages using the Math and Reading Scores
The  scores have been replaced with null values and shows up in Python programming as NaN .
The THS 9th graders received a math & reading score of "0".
All other grades in THS maintained their scores.
All other grades, 9th, 10th, 111th, 12th in all the other schools were not impacted.

- Scores by School Spending
Scores by school spending

Nominal changes

There was very little spending impact by changing the 9th grade scores.

- Scores by School Size

Nominal Changes

There was very little impact by campus size due to changing the 9th grade scores.

- Scores by School Type

Nominal Changes

There was very little impact by school type by changing the 9th grade scores.

## Summary:
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The overall passing rate for Thomas High School changed dramatically from 81% to 65%.

2. Thomas High School's ranking dropped.

3. In addition to the overall passing rate, the campus math and reading averages and passing percentages all saw small shifts.

4. There were not many major changes. Most were nominal.
