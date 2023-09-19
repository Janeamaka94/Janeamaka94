
### INTRODUCTION

USE STAFF;

SELECT * FROM employee_info;

-- RUNNING CODE THE RETURNED ONLY THE DAYNAME IN THE DATE OF ENTRY

SELECT DAYNAME(Date_of_Entry) FROM Employee_Info;

![DAY OF ENTRY](https://github.com/Janeamaka94/Janeamaka94/assets/144977337/6ff70477-93f7-40b9-901f-81d6eae228f1)


USE STAFF;

SELECT * FROM Employee_Info;

-- CODE RETURNING ONLY NAME AND ADDING 10 YEARS INTERVAL TO THE DATE OF ENTRY OF EACH STAFF

SELECT NAME, DATE_ADD(DATE_OF_ENTRY, INTERVAL 10 YEAR) FROM Employee_Info;

ALTER TABLE Employee_Info ADD COLUMN Date_of_Exit Varchar(50);


![UPDATED TABLE SQL TASK 2](https://github.com/Janeamaka94/Janeamaka94/assets/144977337/66d42178-c0b2-4ad1-9e2f-a3575baea827)


USE STAFF;

SELECT * FROM employee_info;

-- Code for adding a column name Date_of_Exit to the table ALTER TABLE Employee_Info ADD COLUMN Date_of_Exit Varchar(50);


![CODE FOR ALTERING TABLES SQL TASK 2](https://github.com/Janeamaka94/Janeamaka94/assets/144977337/d1db6b59-953f-43c4-a44a-7b8a5b27b9fd)![CHANGING DATA TYPE TO VARCHAR TASK 2]


(https://github.com/Janeamaka94/Janeamaka94/assets/144977337/cdea724b-d6d0-45f4-80fd-e2dd7ff6bcc3)

CODE RETURNING ONLY THE NAME AND AGE OF STAFF


![SQL TASK 1 A](https://github.com/Janeamaka94/Janeamaka94/assets/144977337/5a0c309b-752a-47f9-8d71-55e59b002b5a)

CODE RETURNING THE ID AND SALARY OF STAFF
![CHANGING DATA TYPE TO VARCHAR TASK 2](https://github.com/Janeamaka94/Janeamaka94/assets/144977337/18d1a11b-c830-4906-8300-ed4ffa97d247)
![SQL TASK 1 B](https://github.com/Janeamaka94/Janeamaka94/assets/144977337/b7ede0ba-e56c-4e52-90e9-ee906caaef2b)



