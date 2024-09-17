# ECE2112_PA4
John Felipe M. Domingo

# Introduction

This is an introductory assignment to help students understand the basics of Python.
Done by an undergraduate student of Electronics Engineering at the University of Santo Tomas.
Section: 2ECE-A

This Programming Assignment deals with the use of Data Wrangling and Data Visualization. 

**- Data Wrangling** is the process of gathering, collecting, and transforming Raw data into another
format for better understanding, decision-making, accessing, and analysis in less time. 
Data Wrangling is also known as Data Munging.

**- Data Visualization** provides a good, organized pictorial presentation of the data which makes
it easier to understand, observe, and analyze.

To start with this assignment we must import the numpy, pandas, matplotlib, and seaborn libraries and the 
boards2.xlsx file into the Jupyter Notebook. Download first the boards2.xlsx file into your computer and then 
move the file into your Jupyter Notebook folder. To import the .xlsx file into the notebook and turn it into
a data frame, use the function "pd.DataFrame(pd.read_excel())."

![image](https://github.com/user-attachments/assets/90009232-9ec6-4438-a9d7-d437ab349a5f)

# Problems
## 1. Create the following data frames:

### A.) Filename: Instru = ["Name", "GEAS", "Electronics > 70"]; where Track is constant as Instrumentation and hometown Luzon.

For this problem, using the pandas library, utilize the techniques of Subsetting, Splicing, and Indexing in order 
to filter out the students with the given conditions. When the Track, and hometown is constant, the operators used in this
given scenario should be "*==*" and "*&*" which denotes the student with the Track that *is equal to* 'Instrumentation'  
*and* the Hometown which *is equal to* 'Luzon.'

![image](https://github.com/user-attachments/assets/c59fd39f-b289-4f9b-80e0-c89e98828ffa)

### B.) Filename: Mindy = ["Name", "Track", "Electronics", Average >= 55"]; where hometown is as constant as Mindanao and gender Female.

For this problem, continue on utilizing the previous techniques in the pandas library in order to filter out the students with
the given conditions. But before starting out the problem, create first a data frame which computes the averages of all students
in the .xlsx file. For this instance, the data frame is named df['Average'] and in order to compute for the respective averages,
solve for the summation of scores from, Math, Electronics, GEAS, and Communications, and then divide them by 4.

After solving for the Average scores of the students, filter out the students using the operators "*==*", "*>=*', "*&*". to denote
that we are looking for students who lives in their hometown as 'Mindanao', and whose Gender is 'Female", who has an 
Average of "greater than or equal to 55".

![image](https://github.com/user-attachments/assets/d3bcd1fc-17d0-4902-81e3-0ace65e71fd0)

## 2. Create a visualization that shows how the different features contributes to the average grade. Does the chosen track in college,
gender, or hometown contributes to a higher score?

For both of these problems, the 'Track' is grouped together with either 'Gender' or 'Hometown' in order to simplify the chart that is 
going to be used in the problem. For this instance, the chart that is utilzied is the Box plot as it easily shows the spread (distribution)
and skewness in the data. In order to create the box plot, utilize the libraries matplotlib and seaborn.

### A.) Distribution of Average Grades based on Track and Gender.

![image](https://github.com/user-attachments/assets/0b49c5de-819a-44f5-b82f-5ee81ca07dce)


### B.) Distribution of Grades based on Track and Hometown.

![image](https://github.com/user-attachments/assets/f7bf003d-00af-49ea-a3b4-60b86217c9bc)

# Version History

The verion history includes:

Initial submission for the progress report.
PA4PR: [Domingo_JF_PA4_PR.pdf](https://github.com/user-attachments/files/17023590/Domingo_JF_PA4_PR.pdf)

Final submission for the assignment.
PA4.0: [Domingo_JF_PA4.pdf](https://github.com/user-attachments/files/17023591/Domingo_JF_PA4.pdf)

