create table Employee_Record (EmpID VARCHAR2(3) Check (EmpId LIKE 'E%') primary key ,
Ename VARCHAR2(25) not null ,
DOB date not null,
DOJ date not null,
salary number(7) not null)
 
insert into Employee_Record VALUES ('E01','John','10-Oct-1998','01-Apr-2015',8000)
insert into Employee_Record VALUES ('E02','Alex','05-Jan-1998','01-Jul-2016',8000)
insert into Employee_Record VALUES ('E03','Jenny','11-Oct-1999','01-Apr-2016',8000)
insert into Employee_Record VALUES ('E04','Max','25-Dec-2000','03-Jan-2017',8000)

--0
select * from Employee_Record

--1
select * FROM Employee_Record where DOJ = '01-Jul-2016';  

--2
SELECT EmpId, Ename, salary,to_char(DOJ,'MONTH DD,YYYY') FROM Employee_Record;

--3
SELECT *FROM Employee_Record WHERE DOJ<('01-Jan-2018');

--4
SELECT * FROM Employee_Record where to_char(DOJ,'mon')='jan';

--5
SELECT * FROM Employee_Record where to_char(DOJ,'mon')='jan';


--6
SELECT * FROM Employee_Record order by DOJ desc;

--7
SELECT * FROM Employee_Record where to_char(DOJ,'yyyy')='2017';

--8
SELECT * FROM Employee_Record where mod(salary,2)=0;

--9
SELECT * FROM Employee_Record WHERE to_char(DOJ,'YYYY') = '1991' AND (EmpId ='E01' OR EmpId ='E10') ;

--10
SELECT * FROM Employee_Record WHERE to_char(DOJ,'MON') NOT IN ('FEB');

--11
SELECT * FROM employee_Record WHERE dob<('11-dec-1998');
