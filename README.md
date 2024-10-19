# my-sql
my sql
create database aptechfornew;
use aptechfornew;
create table menu(
serial int primary key,
dishes varchar(30),
price int not null,
country varchar(30)
);
insert into menu
(serial,dishes,price,country)
values
(1,"biryani",400,"pakistan"),
(2,"pizza",1200,"italy"),
(3,"momos",400,"india");
select * from menu;
select dishes from menu;
select dishes,price from menu;
select dishes,price>500 from menu;
select dishes="pizza",price from menu;
