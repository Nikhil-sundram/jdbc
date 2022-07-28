# Java JDBC API

The project implements a programmed solution to compute average assignment rating and overall rating for each student and/or subjects to measure effectiveness of learning.
CRUD operations are performed on data using Java code and the changes are reflected on to the database.

There are multiple subjects and each subject has its own assignment categories - test, lab, project and quiz. Each student can give similar assignment different times. So each time when similar assignment category is entered for a student for a similar subject, the program automatically calculates the assignment number and appends at the end of the name of the category (For eg. test_1, test_2, test_3 and so on).

Whenever a particular assignment category is removed for a student, its particular data is deleted and overall score is updated for that particular student.

# To exectute code successfully.
App.java file contains main method.
MySQL database is used in this project. Its dependecy is written into the pom.xml file. 
Sql queries to create databases with different required tables are put into Table Queries.txt

