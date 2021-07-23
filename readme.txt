create table students(
	id serial primary key,
	fname varchar(40) not null,
	lname varchar(40) not null,
	email varchar(100) not null	
);

select * from students;