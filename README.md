# TASK 1 (CREATING A DATABASE)

A database is a structured collection of data that is organized and stored in a way that allows efficient retrieval,management and manipulation of information.After the sesion we were given some task which are stated below

# QUESTION

1. Create a database
2. Create Tables (STUDENT RECORD,HEALTH RECORD, PERFORMANCE ) and also insert values
3. Adding constraints not null to Subject and Student_ID

# ACTIVITIES

![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/f232d83f-ff46-4e09-883f-e8a4e853a882)

Above is the surface of our ssms , so to create a database i clicked on New query on the top part of the page then my next action was i entered the syntax which is =CREATE DATABASE database_name; then i highlighted and excute. below is the result 

![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/6d898951-f690-42d8-9513-06c617b6c2f6)


STEP 2 was asked to create a table on the database i created, so i used the syntax CREATE TABLE STUDENT_INFO,then highlighted and executed,below is the result.

<img width="956" alt="image" src="https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/f986b0ce-0440-4c95-8ab0-fe0a2b003e89">

Step 3 Inserting values into the tables i created using the syntax 

INSERT INTO STUDENT_INFO(STUDENT_ID, GENDER, NAME, AGE, SUBJECT) 
VALUES (1, 'MALE', 'ROBINSON', 34, 'MATHS'),
      (2, 'FEMALE', 'MARIS', 24, 'ENGLISH'),
	    (3, 'MALE', 'CHARLES', 26, 'MATHS'),
	    (4, 'FEMALE', 'KATE', 30, 'ENGLISH'),
	    (5, 'MALE', 'KUNLE', 28, 'MATHS'),
	    (6, 'FEMALE', 'MARY', 32, 'ENGLISH');

![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/5c6b51e2-66af-4777-839e-7643df38792a)



<img width="954" alt="image" src="https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/06818b8b-1f76-4a68-8aa2-a92ab1d74082">



![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/4239735e-14cd-4424-a0b9-338161d5d594)



![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/4039a68f-be8f-4ac1-abab-c803483327cd)



Adding Constraints to our columns 
_ Constraints are used to specify rules for data in a table, we added the not null constraints to our column STUDENT_ID and SUBJECT


![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/941a644e-3f28-40c1-b529-edc2ee8a1918)





