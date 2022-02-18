# ADVANCED-SQL

Exercise 1, Question 1: 
Write and execute a SQL query to list the school names, community names and average attendance for communities with a hardship index of 98. 

Exercise 1, Question 2: 
Write and execute a SQL query to list all crimes that took place at a school. Include case number, crime type and community name.

Exercise 2, Question 1: 
Write and execute a SQL statement that returns just the school name and leaders’ icon from the view. 

Exercise 3, Question 1: 
Write the structure of a query to create or replace a stored procedure called UPDATE_LEADERS_SCORE that takes a in_School_ID parameter as an integer and a in_Leader_Score parameter as an integer. Don't forget to use the #SET TERMINATOR statement to use the @ for the CREATE statement terminator. 

Exercise 3, Question 2: 
Inside your stored procedure, write a SQL statement to update the Leaders_Score field in the CHICAGO_PUBLIC_SCHOOLS table for the school identified by in_School_ID to the value in the in_Leader_Score parameter. 

Exercise 3, Question 3: 
Inside your stored procedure, write a SQL IF statement to update the Leaders_Icon field in the CHICAGO_PUBLIC_SCHOOLS table for the school identified by in_School_ID using the following information. 

Exercise 3, Question 4: 
Run your code to create the stored procedure.

Exercise 4, Question 1: 
Update your stored procedure definition. Add a generic ELSE clause to the IF statement that rolls back the current work if the score did not fit any of the preceding categories. 

Exercise 4, Question 2: 
Update your stored procedure definition again. Add a statement to commit the current unit of work at the end of the procedure. 
