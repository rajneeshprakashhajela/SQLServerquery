create table employee(id int, name varchar(20))
insert into employee values(1,'A')
insert into employee values(2,'B')
insert into employee values(3,'C')
insert into employee values(4,'D')
insert into employee values(5,'E')
select * from employee


create table dept(id int, name varchar(20),empid int)
insert into dept values(101,'IT',1)
insert into dept values(101,'IT',2)
insert into dept values(102,'IT',3)
insert into dept values(103,'IT',4)
insert into dept values(104,'IT',null)
update dept set name='HR' where id=102
select * from employee
select * from dept
select  e.name, d.name from dept d inner join employee e on d.empid=e.id

![image](https://github.com/rajneeshprakashhajela/SQLServerquery/assets/43515480/30340921-8c2d-40ef-9d09-c3bb073ee713)
