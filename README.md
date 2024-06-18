# DATA-WRANGLING
Assignment Overview
Data Wrangling or Munging is a process in which we clean up the data set and make it ready for data analysis. In this assignment you will perform the following tasks:
1.	Identify duplicate rows in the data frame.
2.	Remove duplicate rows from the dataframe.
3.	Find the number of missing values for all columns.
4.	Find the value counts for the column "Employment".
5.	Normalize the data using two existing columns. 
 

df = pd.read_csv("https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m1_survey_data.csv")
1.	Finding duplicates
2.	Find how many duplicate rows exist in the dataframe.
3.	Remove the duplicate rows from the dataframe
4.	Verify if duplicates were actually dropped.
5.	Find the missing values for all columns.
6.	Find out how many rows are missing in the column 'WorkLoc'
7.	Find the value counts for the column WorkLoc.
8.	Identify the value that is most frequent (majority) in the WorkLoc column.
9.	Impute (replace) all the empty rows in the column WorkLoc with the value that you have identified as majority.
10.	After imputation there should ideally not be any empty rows in the WorkLoc column. Verify if imputing was successful

Normalizing data
There are two columns in the dataset that talk about compensation.
One is "CompFreq". This column shows how often a developer is paid (Yearly, Monthly, Weekly).
The other is "CompTotal". This column talks about how much the developer is paid per Year, Month, or Week depending upon his/her "CompFreq".
This makes it difficult to compare the total compensation of the developers.
In this section you will create a new column called 'NormalizedAnnualCompensation' which contains the 'Annual Compensation' irrespective of the 'CompFreq'.
Once this column is ready, it makes comparison of salaries easy. 

1.	List out the various categories in the column 'CompFreq'
2.	Create a new column named 'NormalizedAnnualCompensation'. Use the hint given below if needed.
