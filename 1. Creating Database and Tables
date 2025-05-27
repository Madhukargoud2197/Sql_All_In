CREATE database Employee_demographics;
use Employee_demographics ;

CREATE TABLE Employee_details(
Employee_id INT NOT NULL PRIMARY KEY,
First_Name VARCHAR(50),
Last_Name VARCHAR(50),
Age int,
Gender VARCHAR(10),
Birth_data DATE
);

select * from Employee_details;

CREATE TABLE Employee_Salary (
employee_id INT NOT NULL,
First_Name VARCHAR(50),
Last_Name VARCHAR(50),
Occupation varchar(50),
Salary int,
dept_id int) ;

INSERT INTO Employee_details(
Employee_id, First_Name, Last_Name, Age, Gender, Birth_data)
VALUES
(1, 'Madhukar', 'Goud', 27, 'Male', '1997-11-21'),
(2, 'Sagar', 'Aaka', 28, 'Male', '1997-06-01'),
(3, 'Sai', 'Dhagad', 29, 'Male', '1997-02-21'),
(4, 'Madhurima', 'Goud', 26, 'Female', '2000-02-08') ;

select * from Employee_details ;

SELECT * FROM Employee_details
WHERE Last_Name = 'Goud' ;

INSERT INTO Employee_Salary (
employee_id, First_Name, Last_Name, Occupation, Salary, dept_id)
Values
(1, 'Madhukar', 'Goud', 'Data_scientist', 240000, 1),
(2, 'Sagar', 'Aaka', 'Data_Engineer', 200000, 2),
(3, 'Sai', 'Dhagad', 'Clerk', 150000, 3),
(4, 'Madhurima', 'Goud', 'Medical_Coder', 300000, 4) ;


select * from Employee_Salary ;
