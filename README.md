# sql-commands

<sql queries:
```json
ALTER TABLE public.example_data 
	ADD footbal_team varchar(100);
	
	
	
	
create table example_data( 
	id serial,
	"name" varchar(100),
	email varchar(100),
	country varchar(100),
	acc_number varchar(100),
	branch int,
	apply_date varchar(100)
);
  

SELECT id, "name", email, country, acc_number, branch, apply_date
FROM public.example_data;


INSERT INTO public.example_data
("name", email, country, acc_number, branch, apply_date)
VALUES('', '', '', '', 0, '');

UPDATE public.example_data
SET  "name"='bbb', email='up@date', country='updesh', acc_number='44', branch=7, apply_date='33-33-33' where id=6;

DELETE FROM public.example_data
where id=6;


create table demo_data( 
	id serial,
	"name" varchar(100),
	email varchar(100),
	acc_number varchar(100),
	branch int,
	apply_date varchar(100)
);

SELECT id, "name", email, country, acc_number, branch, apply_date
FROM public.example_data;


create table rm_branch (
	id serial,
	"name" varchar(64),
	created_on varchar(64),
	created_by varchar(64)
	
);

INSERT INTO public.rm_branch
("name", created_on, created_by)
VALUES('rm-three', '', '');

 ```
