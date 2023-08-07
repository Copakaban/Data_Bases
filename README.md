# Data_Bases  

**Задание 1.**  
Employees:  
  - id_employee, smallint, not null, primary key;  
  - last name, varchar, not null;  
  - first name, varchar, not null;  
  - surname, varchar;  
  - rank, foreign key;  
  - salary, foreign key;  
  - subdivision, foreign key;  
  - office, foreign key;  
  - project, foreign key;  
  - date of employment, date, not null.  

Subdivision:  
  - id subdivision, tinyint, not null, auto increment, primary key;  
  - subdivision, varchar, not null;  
  - type of subdivision, foreign key;    
  - office, foreign key.  

Type of subdivision:  
  - id of type, tinyint, not null, auto increment, primary key;  
  - type.  

Offices:  
  - id office, tinyint, not null, auto increment, primary key;  
  - office, varchar, not null.  

Projects:  
  - id project, int, not null, auto increment, primary key;  
  - project, varchar, not null.  

Ranks:  
  - id rank, int, not null, auto increment, primary key;  
  - rank, varchar, not null.  

Salary:  
  - id salary, int, not null, auto increment, primary key;  
  - salary, real, not null.  
