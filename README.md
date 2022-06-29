# School_District_Analysis

Analysis of school district using Pandas and Jupyter Notebook

## Overview of Project 

Pandas and Jupyter Notebook were used to complete an analysis of data provided by a school district from excel file Schools Complete [schools_complete.csv](https://github.com/AjaniBenoit/School_District_Analysis/blob/main/schools_complete.csv) and Students Complete [students_complete.csv](https://github.com/AjaniBenoit/School_District_Analysis/blob/main/students_complete.csv). Analysis of the files primarily focused on district school performance in reading and math. Further analysis was completed after concerns raised were raised of academic dishonestly among 9th graders at Thomas High School. The data associated with the 9th graders at Thomas High School was omitted at the request of the School Board.

### Purpose 

The purpose of this report is to provide a summary of the performance of schools within district in the subjects of math and reading. 

## Results 
### How is the District Summary Affected?

The testing data in math and reading was converted into a NaN (Not a number) value from 9th graders from Thomas High School and omitted from the calculation percentage of students that passed math, reading and the overall pass rate 

Original
![Original_district_summary](https://github.com/AjaniBenoit/School_District_Analysis/blob/main/Original_district_summary.png)

Updated
![Updated_district_summary](https://github.com/AjaniBenoit/School_District_Analysis/blob/main/Updated_district_summary.png)

The schools, students and budget remained the same, but the average math score, average reading score percent passing math, percent passing reading and percent overall passing decreased by less than one percent. 

### How is the School Summary Affected?
In the original analysis Thomas High School had 93.27% pass math, 97.31% passing reading with 90.95% overall passing. In the updated analysis the 9th graders were removed. The percentage passing math, reading and overall passing decreased. 

Original 
![Original_school_summary](https://github.com/AjaniBenoit/School_District_Analysis/blob/main/Original_school_summary.png)

Updated
![Updated_school_summary](https://github.com/AjaniBenoit/School_District_Analysis/blob/main/Updated_school_summary.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s Performance relative to the other schools?

In the original analysis, schools were sorted into the top performing schools based on the percent of overall passing student. In the initial analysis, Thomas High School was ranked second after Cabrera High School. In the updated analysis, Thomas High School ranked in the eighth spot after Holden High School.

### How does replacing the ninth-grade scores affect the following: 

#### Math and reading scores by grade 
In the original analysis, the 9th graders at Thomas High School had an average reading score of 83.73  and an average math score of 83.59. In the updated analysis the 9th graders  math and reading scores at Thomas High School was replaced by a NaN variable. 

Math Score

![Math_score_grade]( https://github.com/AjaniBenoit/School_District_Analysis/blob/main/Math_score_grade..png)

Reading Score 

![reading_score_grade]( https://github.com/AjaniBenoit/School_District_Analysis/blob/main/reading_score_grade.png)

#### Scores by school spending
 
In both the initial analysis and the updated analysis Thomas High School spent $631-645 per student. This number did not change after omitting the 9th graders score. 

#### Scores by school size

Thomas High School was categorized as a medium with a total student population falling in the range of 1000 to 1999 students. In the original analysis the percentage overall pass was 90.62. The percentage overall pass decreased in the updated analysis to 90.56.
