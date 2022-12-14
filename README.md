# School_District_Analysis
Python Analysis of school data

Link to the solution: https://github.com/Mishauwa/School_District_Analysis/blob/main/Challenge_Solution.ipynb

## Project Overview
In the following school district analysis project a dateset with student data has to get analysed. 
The dataset provides detailed information about the students and schools. The tasks in the project are the following. 

- Deliverable 1: Collect the student data into a DataFrame.
- Deliverable 2: Prepare a cleaned version of the DataFrame.
- Deliverable 3: Summarize key pieces of the data.
- Deliverable 4: Drill down into the data to analyze specific subsets.
- Deliverable 5: Compare and contrast the data through grouping and aggregation functions.
- Deliverable 6: A written analysis of your results (README.md).

Below you can see an overview of the dataset with it's provided information.

<img width="775" alt="Data_overview" src="https://user-images.githubusercontent.com/69826498/190483969-cce1c8eb-352d-4224-bb1b-ce9c27a7bf80.png">

After cleaning the data and removing duplicates and NAN (mostly missing reading and maths scores by students) we could start the anlaysis with a clean set. 

## Results and Findings

- The average budget between charter and public schools is nearly the same 
    
    <img width="190" alt="schoolbudget_byschooltype" src="https://user-images.githubusercontent.com/69826498/190482975-e16adedd-c892-44d9-a3b6-2219717489fb.png">


- The amount of students per school has a high variation between the schools (min: 171 max: 2038)
    
    <img width="256" alt="studentcountbyschool" src="https://user-images.githubusercontent.com/69826498/190481940-4a1c36cd-827d-4147-b141-22cb0dd5b4f3.png">

- The average math_score is not highly affected by the school type (public or charter)
    
    <img width="217" alt="Math_score_byschooltype" src="https://user-images.githubusercontent.com/69826498/190482122-60382cfa-a74f-41c7-ab66-693b9ec59535.png">

  
## Possible future additional analysis

- Compare whether the number of students per school is affecting the reading or math scores 
    
- Compare reading and math scores between the schools and their school budgets
