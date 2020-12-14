# Overview 
## Purpose of the School District Analysis
The purpose of this project is to conduct a school district analysis using Anaconda &amp; Jupyter Notebook. The data we are analyzing comes from two sources: one is a csv containing school data and another is a csv containing data on the students from those schools. The school data file contains information related to the school name, the type of school (whether Charter or District), the size of the school, and the budget of the school. The data on the students contains information such as their name, school, grade, and individual scores on math and reading. The common data between these two files is the "School Name" column. In this analysis we will load our data from the two csv's into dataframes to better visualize the data and sort and group the data, then we will merge the two datasets into one dataframe to find trends, view summaries, and sort by overall performance, math and reading scores, and school spending. We will also address an issue that was brought to light by the school board wherein there is evidence of academic dishonesty; specifically, that reading and math grades for Thomas High School ninth graders appear to have been altered. Therefore we will also clean the data and disregard those grades from Thomas High School ninth graders before conducting the final analysis. 

# Results
## How is the district summary affected?
The district summary is actually not affected much by the changes of replacing 9th grade Thomas High School Student Data with Nan because the District Summary DataFrame is not analyzing only data per student, but also analyzing data by overall school information such as total schools, total students, and total budget. The numbers that look at Average Scores, Passing Scores, and Overall Passing Scores are only slightly different in total. Changes between the original and updated can be found below. 


## How is the school summary affected?
## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
## How does replacing the ninth-grade scores affect the following: 
### Math and reading scores by grade
### Scores by school spending
### Scores by school size
### Scores by school type

# Summary
## Summary of 4 Major Changes in Updated DataFrame
