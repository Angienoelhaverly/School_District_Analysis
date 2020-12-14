# Overview 
## Purpose of the School District Analysis
The purpose of this project is to conduct a school district analysis using Anaconda &amp; Jupyter Notebook. The data we are analyzing comes from two sources: one is a csv containing school data and another is a csv containing data on the students from those schools. The school data file contains information related to the school name, the type of school (whether Charter or District), the size of the school, and the budget of the school. The data on the students contains information such as their name, school, grade, and individual scores on math and reading. The common data between these two files is the "School Name" column. In this analysis we will load our data from the two csv's into dataframes to better visualize the data and sort and group the data, then we will merge the two datasets into one dataframe to find trends, view summaries, and sort by overall performance, math and reading scores, and school spending. We will also address an issue that was brought to light by the school board wherein there is evidence of academic dishonesty; specifically, that reading and math grades for Thomas High School ninth graders appear to have been altered. Therefore we will also clean the data and disregard those grades from Thomas High School ninth graders before conducting the final analysis. 

# Results
## How is the district summary affected?
The district summary is actually not affected much by the changes of replacing 9th grade Thomas High School Student Data with Nan because the District Summary DataFrame is not analyzing only data per student, but also analyzing data by overall school information such as total schools, total students, and total budget. The numbers that look at Average Scores, Passing Scores, and Overall Passing Scores are only slightly different in total. The very slight change that is a slight decrease in overall passing and average scores is likely due to the fact that when we exclude the data that was falsified (9th graders from Thomas High School), the average passing scores go down a little. These changes between the original and updated summary can be found below. 
### Original District Summary
![DS Original](https://user-images.githubusercontent.com/73972332/102035199-a9d8f200-3d74-11eb-8d20-82d0dbb06cc6.png)
### Refactored District Summary
![DS Updated](https://user-images.githubusercontent.com/73972332/102041632-d09f2480-3d84-11eb-88d3-dc60716dbb1c.png)
## How is the school summary affected?
The school summary dataframe is affected in that after removing the false/altered data from the calculations, the scores drop overall for Thomas High School. When the falsified data was included, the scores were much higher for the percentage of those passing math, reading, and overall. When the data is excluded, the passing scores drop from the mid 90's to the mid 60's. This makes sense, given that the falsified/innacurate data would reflect a higher score overall and that the general scores would drop when the data is not counted. See the differences below in the two graphs (one for the original, and one that is filtered). 
### Original Per School Summary
![Per School Summary Original](https://user-images.githubusercontent.com/73972332/102043045-45279280-3d88-11eb-9e88-dcac11df71f9.png)
### Refactored Per School Summary
![Per School Summary Updated](https://user-images.githubusercontent.com/73972332/102043065-4f499100-3d88-11eb-9c9f-46e6e04694f4.png)
## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
## How does replacing the ninth-grade scores affect the following: 
### Math and reading scores by grade
### Scores by school spending
### Scores by school size
### Scores by school type

# Summary
## Summary of 4 Major Changes in Updated DataFrame
