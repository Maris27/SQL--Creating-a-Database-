# TASK 1 (CREATING A DATABASE)

A database is a structured collection of data that is organized and stored in a way that allows efficient retrieval,management and manipulation of information.After the sesion we were given some task which are stated below

# QUESTION

1. Create a database
2. Create Tables (STUDENT RECORD,HEALTH RECORD, PERFORMANCE ) and also insert values
3. Adding constraints not null to Subject and Student_ID
4. Change the cloumn name subject to course
5. Drop the Age column from the student info table

# ACTIVITIES

![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/f232d83f-ff46-4e09-883f-e8a4e853a882)

**STEP 1** Above is the surface of our ssms , so to create a database i clicked on New query on the top part of the page then my next action was i entered the syntax which is =CREATE DATABASE database_name; then i highlighted and excute. below is the result 

![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/6d898951-f690-42d8-9513-06c617b6c2f6)



**STEP 2** was asked to create a table on the database i created, so i used the syntax CREATE TABLE STUDENT_INFO,then highlighted and executed,below is the result.

<img width="956" alt="image" src="https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/f986b0ce-0440-4c95-8ab0-fe0a2b003e89">

Inserting values into the tables i created using the syntax 

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



**STEP 3** Adding Constraints to our columns 
_ Constraints are used to specify rules for data in a table, we added the not null constraints to our column STUDENT_ID and SUBJECT


![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/941a644e-3f28-40c1-b529-edc2ee8a1918)



**STEP 4** Change column name

![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/997bde9e-552c-44be-8ec9-a8a0dd0356a5)




**STEP 5** Drop the Age column

![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/42be9629-db35-40b3-924d-b9290b0f9bc7)








# TASK 2
Using the employee data
The first thing i did was to  download the Employee data from the source and i cleaned the data using excel by adjusting the date format before importing it as a CSV file into the STUDENT RECORD DATEBASE.below is the Employee data after uploading  


![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/2c0cbdef-43bd-4515-b567-9e1fb18de813)


# QUESTIONS
1. Filter mumbai and delhi city
2. select employee name that begins with a and e
3. subset employee data to have employee with the date of birth above 1990
4. subset salary table to show salaries less than 1 million and sort in ascending order.



# ACTIVITIES

![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/1ef13f6a-c562-4359-9012-2ead403570cc)



![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/53282a5d-b27d-4d45-a11d-8286ca13341d)




![image](https://github.com/Maris27/SQL--Creating-a-Database-/assets/140453106/d071421f-bbfc-405b-88fa-3c878aa2ab72)


















