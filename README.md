CREATE DATABASE hr_database ;

CREATE TABLE employee (
         
         EMPLOYEE_ID int NOT NULL, 
         FIRST_NAME varchar(255),
         LAST_NAME varchar(255) NOT NULL,	
         EMAIL varchar(255)
         PHONE_NUMBER int,
         HIRE_DATE date
         MIN_SALARY INT,
         MAX_SALARY INT,
         PRIMARY KEY (EMPLOYEE_ID)

);

CREATE TABLE jobs (
          
         JOB_ID int NOT NULL,
         SALARY int,
          JOB_TITLE varchar (255)
          PRIMARY LEY (JOB_ID)
);
