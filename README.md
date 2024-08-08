# pandas-student-outcomes-analysis
For this project, I utilized the pandas module within Python to examine student test score data from an anonymous district to support the school board and mayor in making strategic decisions regarding future school budgets and priorities. I aggregated the data to showcase trends in school performance, including the following:

**District Summary**
Performed calculations and created a high-level snapshot of the district's key metrics in a DataFrame.
- Total number of unique schools
- Total students
- Total budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

**School Summary**
Performed calculations and created a DataFrame that summarizes key metrics about each school.
- School name
- School type
- Total students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

**Highest-Performing Schools (by % Overall Passing)**
- Sorted the schools by % Overall Passing in descending order and display the top 5 rows.
- Saved the results in a DataFrame called "top_schools".

**Lowest-Performing Schools (by % Overall Passing)**
- Sorted the schools by % Overall Passing in ascending order and display the top 5 rows.
- Saved the results in a DataFrame called "bottom_schools".

**Math Scores by Grade**
- Performed the necessary calculations to create a DataFrame that lists the average math score for students in each grade level (9th, 10th, 11th, 12th) at each school.

**Reading Scores by Grade**
- Created a DataFrame that lists the average reading score for students in each grade level (9th, 10th, 11th, 12th) at each school.

**Scores by School Spending**
- Create a table that breaks down school performance based on average spending ranges (per student), including:
- Average math score
- Average reading score
- % passing math (the percentage of students who passed math)
- % passing reading (the percentage of students who passed reading)
- % overall passing (the percentage of students who passed math AND reading)

**Scores by School Size**
- Used pd.cut on the "Total Students" column of the per_school_summary DataFrame.
- Created a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

**Scores by School Type**
- Used the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
- This new DataFrame shows school performance based on the "School Type".

