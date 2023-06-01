# Hospital-Information-System
Create my first SQL Database

For this exercise, I have created two tables, Hospital and Doctor. 

Create those two tables on the SQL server before starting the exercise.

Please find below the SQL queries to prepare the required data for our exercise. SQL Queries for data preparation

1. Create database using SQL
2. Tables should be like this:

Hospital_Id Hospital_Name Bed Count
1 (name of hospitals) 300
2 (name of hospitals) 600
3 (name of hospitals) 900
4 (name of hospitals) 1200
5 (name of hospitals) 1500

Doctor_Id Doctor_Name Hospital_Code Joining_Date Specialty Salary Experience
101 (Names) (1 digit) Yyyy-mm-dd Null
(three
digits)
(Names) (1 digit) Yyyy-mm-dd Null
(three
digits)
(Names) (1 digit) Yyyy-mm-dd Null
(three
digits)
(Names) (1 digit) Yyyy-mm-dd Null
(three
digits)
(Names) (1 digit) Yyyy-mm-dd Null
(three
digits)
(Names) (1 digit) Yyyy-mm-dd Null

SQL Data model that supposedly using for this task:

Doctor
HOSPITAL
Hospital_Id
Hospital_Name
Bed_Count


Doctor_Id
Doctor_Name Hospital_Id Joining_Date
Specialty
Salary
Experience

Tasks:

1. Connect to your database serverand print its version 2. 

2. Add 50 sample records

3. Fetch Hospital and Doctor Information using hospital Id and doctor Id

4. Get the list of the doctors as per given specialty and salary 

5. Get the list of the doctors from a given hospital

6. Update doctor experience in year
