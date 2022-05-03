# School District Analysis

## Overview
- The school board has determined that there was an act of academic dishonesty towards freshman in regards to the reading and math scores at Thomas High School. Today's objective is to format a DataFrame that replaces both math and reading scores with Nans. Once corrected, we are able to conduct a proper school board analysis to determine how the overall scores will be affected.

1. Replace the 9th grade reading and math scores at Thomas High School with NaN.
2. Combine school and student data into a single dataset.
3. Calculate the data from all students (9th-12th)
4. Create a series for math and reading score averages and format the columns into a new dataframe.
5. Gather information about the school's size, type, and spending totals 


## Resources
- Data Source: PyCitySchools.ipynb
- Software: Python 3.6.1, Anaconda3, Jupyter Notebook  


## Results
### How is the district summary affected?
- The district summary did not have a significant impact when adjusting the initial analysis. Although each score and percentage value decreased, the numbers when rounded whole would still equate to the same values in the original analysis.


![District Summary](https://user-images.githubusercontent.com/102638461/166403703-1b967769-6535-4ada-8a3d-0f9c47077886.png)


### How is the school summary affected?
- In the initial analysis, the students at Thomas High School had significantly high passing percentages that did not allign with their average scores. Therefore, another analysis was conducted to analyze the new data that focused on scores for students grade 10th through 12th. After proper adjustments, the data reveals a significant decrease in passing percentages while the values for total students and their average scores remained the same.


![School Summary](https://user-images.githubusercontent.com/102638461/166404106-5caa99a9-edcd-43ba-ad13-3391d42fd83c.png)


### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
- The replacement of freshman math and reading scores led to the plundge of Thomas High School's ranking. In the original analysis, they ranked at the top 5 with an overall passing percentage of around 90%. Since the adjustments, they now rank at the bottom half of the list with a new overall passing percentage of 65%.

### How does replacing the ninth-grade scores affect the following:
1. Math and reading scores by grade
- Initially, Thomas High School was scored just has high as the other schools. Since the adjustment, the math score for freshman now show up as NaN. 


![Math Scores by Grade](https://user-images.githubusercontent.com/102638461/166404415-c022b0e8-9613-47a8-a23e-940a3f346346.png)

- As for reading scores, the results are identical towards math as the freshman score is once again a missing value.

![Reading Scores by Grade](https://user-images.githubusercontent.com/102638461/166404435-294be940-86a6-4694-9c95-da3ad14cc93b.png)

2. Scores by school spending
- Thomas High School is in the $630-$644 category, but the changes to its score were very minimal. When rounded up, each score remains unaffected.


![Spending Summary](https://user-images.githubusercontent.com/102638461/166404657-961dbe63-6ac8-4bd9-8915-62c10773db49.png)

3. Scores by school size
- Thomas High School falls in the 1000-2000 student medium category, but once again its changes to the score were uneffective. 


![Size Summary](https://user-images.githubusercontent.com/102638461/166404671-38f70416-f23f-4b37-85cc-0f2307d5d833.png)

4. Scores by school type
- Thomas High School is a charter school, but the scores were barely affected in the adjusted analysis.


![Type Summary](https://user-images.githubusercontent.com/102638461/166404677-4086aa65-fea2-4133-8cec-1defcdd13ef3.png)

## Summary
### Four Changes

1. Thomas High School's overall passing rate decreased drastically from 90% to 65%.

2. Passing math and reading percentages also saw a decrease of about 30%.

3. In relative to the other schools in the dataset, Thomas High School's overall performance decreased significantly. 

4. Freshman math and reading scores at Thomas High School now show up as an NaN value.

Therefore, the act of academic dishonestly from the freshman at Thomas High School seems very likely since the other three grade levels experienced very low relative scores.
