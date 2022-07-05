# School District Analysis

## Overview

The school board has notified that our initial school district analysis file shows evidence of academic dishonesty. The user is tasked with repeating an already-completed school district analysis with the goal of finding evidence of academic dishonesty for ninth graders from Thomas High School. 

### Purpose 

The purpose of this project is to verse the user in pandas, a software library written for the Python language that specializes in data manipulation and analysis. Moreover, they are to practice cross-referencing two variations of datasets to find implicative values that may provide clarity for a potentially significant situation. 

## Results

### District Summary

Comparing our District Summary fata frames showed small, but potentially significant changes for Average Math (-0.1%), 
Passing Math % (-0.2%), Passing Reading % (-0.1%), and Overall Passing % (-0.3%).

#### Original 
<img width="780" alt="District_Summary_Old" src="https://user-images.githubusercontent.com/106895220/177077850-86b68118-8171-4879-a076-c2e15adfb38f.png">

#### Clean
<img width="781" alt="District_Summary_New" src="https://user-images.githubusercontent.com/106895220/177077858-10b7ad45-7919-4f53-9c96-c730215b95ef.png">

### School Summary

Significant changes for all metrics: Average Math (-0.07%) , Average Reading (0.05%), Passing Math % (-26.37%), Passing Reading % (-27.65%), and Overall Passing % (-25.87%).

#### Original 

<img width="883" alt="School_Summary_Old" src="https://user-images.githubusercontent.com/106895220/177085504-85d49edb-0a1a-4490-9eab-c57203c3ebcf.png">

#### Clean

<img width="884" alt="School_Summary_New" src="https://user-images.githubusercontent.com/106895220/177082502-a1911700-0c07-4239-b0e8-a36fd55b41b5.png">

### Relative Performance Change

While omission of ninth grade scores heavily diminished school passing percentages, Thomas High School remains ranked second in the district.

#### Original 

<img width="883" alt="Rankings_Old" src="https://user-images.githubusercontent.com/106895220/177086471-3f4ce494-2d92-498e-a6da-5c1dfe89b590.png">

#### Clean

<img width="889" alt="Rankings_New" src="https://user-images.githubusercontent.com/106895220/177086487-957e7d38-3905-4748-aaf1-cb81e97cea06.png">

#### 10th - 12th Metrics

Note that, despite the drop in passing percentages in the School Summary, 10th through 12th graders at Thomas High School still performed exceptionally and in line with what is expected based on performance metrics.

<img width="885" alt="10th_to_12th" src="https://user-images.githubusercontent.com/106895220/177088874-cf27db14-c15e-473f-a484-3aab5a5ae73a.png">


### Math and Reading Scores by Grade

Removing ninth grade values seems to hae no effect on math and reading scores for other grades.

#### Math Scores by Grade

<img width="274" alt="Math_Score_by_Grade" src="https://user-images.githubusercontent.com/106895220/177094141-a4935028-6838-4c50-84f1-318ae3afa260.png">

#### Reading Scores by Grade

<img width="265" alt="Reading_Score_by_Grade" src="https://user-images.githubusercontent.com/106895220/177094159-09bcd6d4-3bc6-4670-8012-dfb8fb2f2ef5.png">

### Scores by School Spending



<img width="741" alt="Score by Spending" src="https://user-images.githubusercontent.com/106895220/177099313-f763bce8-bc2b-45f1-91b2-595fa8f228ab.png">


### Scores by School Size

The Size dataframe remains identical, though lack of change may provide insight on performance when measured against size. Averages for Large schools drastically decrease compared to their smaller counterparts. In the context of academic dishonesty, if modified test scores were only found in Thomas High School (a smaller, top performing school), then it may give insight to the effects of smaller school cultures compared to larger ones (increased competitive environment, school's need and/or student desparation for prestige, a curriculum deemed too challenging for entry-level students?). 


Scores_by_size<img width="692" alt="image" src="https://user-images.githubusercontent.com/106895220/177098872-e067a03d-db5b-4bc2-b46e-77db1d829c38.png">


### Scores by School Type



<img width="654" alt="Scores by School Type" src="https://user-images.githubusercontent.com/106895220/177097914-3c59548e-c0bc-4d9d-99cb-2605ce787f14.png">
