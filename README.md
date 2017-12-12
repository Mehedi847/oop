# ooop


			
				

 
OBJECT ORIENTED SOFTWARE DEVELOPMENT


University Registration System
	NAME:Mehedi Hasan 		ID: 151-35-847	
	Supervisor Name	：	Alamgir kabir	
	Department:	：	Software Engineering	
	Faculty of Science and Information Technology	
				
December 2017
 
Table of Contents
Chapter 1	1
1.	Introduction	2
1.1	About the System	2
1.2	Purpose	2
1.3	Scope	2
1.4	Vision	2
1.5	Why this system is necessary?	3
1.6	Proposed Solution	3
Chapter 2	4
2.	System Analysis	5
2.1	Use Case Model	5

2.2	Actor Goal List	6
2.3	Use Case Description (Brief)	6
2.3.1	Register cours	6
          2.3.2 Select course------------------------------------------------------------------ 7
          2.3.3 Manage registration-----------------------------------------------------------8
2.4	Use Case Description (Detailed)	9
         2.4.1 Register course-----------------------------------------------------------------9
         2.4.2 select course--------------------------------------------------------------------10
        2.4.3 Manage registration------------------------------------------------------------11
2.5	System Sequence Diagrams	------12
          2.5.1 Register course---------------------------------------------------------------12
          2.5.2 Select course------------------------------------------------------------------13
         2.5.3 Manage Registration-----------------------------------------------------------14
2.6	Domain/Conceptual Model	15
2.7	Activity diagram	16
Chapter 3	17
3.	System Design	18
      3.1.1 Register course-------------------------------------------------------------------18
       3.1.2 select course----------------------------------------------------------------------19
       3.1.3 manage registration--------------------------------------------------------------20
3.2	Class Diagram	21
Chapter 4	22
4.	Implementation	22

 









Chapter 1
Introduction 
1.	Introduction
The name of the system is university registration system.  A course catalog containing list of course offering. using course catalog student can easily know Information about each course, such as professor, department, and prerequisites. They can select  courses or change  schedule time. professors also know which course they will be teaching.

1.1	About the System
The university management system. Student can select  courses, cancel courses, change schedule time .The professor also select courses, Deselect courses. The register offer courses, assign teacher ,change courses and close registration.

1.2	Purpose
The purpose of the system is student can easily know upcoming semester courses and each courses professor and prerequisites. They can easily register courses ,select courses and changes schedule time also professor knows their teaching courses.

1.3	Scope
It is university registration system which helps the student .They don't need to asked anyone to know upcoming semester courses and teacher. They easily select courses and deselect also change their schedule time. Professor  can also know their teaching courses.

1.4	Vision
The vision of the system is to Students can know their courses and professor. They can select the courses and change the schedule time also professor select the courses.

1.5	Why this system is necessary?
The system is necessary for course registration, select course,  de-select course ,change schedule, assign teacher ,close registration.

1.6	Proposed Solution

Student can easily select courses, de-select courses, change schedule, assign teacher ,close registration. 





Chapter 2
System Analysis











2.	System Analysis
2.1	Use Case Model

 

2.2	Actor Goal List

Actor	 
Goal
 
Student	 
Student can  register  courses. They can select the course. They  can also change the course. They  also change   schedule time.
professor	Professors can select  subject also they can deselect the subject.
 
Register
 	Register mange registration management.  Maintainers  the course offer, Assign teacher, change course, cancel course, close registration.
 
 

	

2.3	Use Case Description (Brief)
2.3.1	Register course

 Student can  register  courses. They can select the courses. They  also change   schedule time.
 

2.3.2  Select course:
Student can  change  the courses and deselect the courses. Teacher can change course   also they can deselect the course.
 

2.3.3 Manage registration
Register mange registration management.  Maintainers  the course offer, Assign teacher, change course , cancel course, close registration.


 

2.4	Use Case Description (Detailed)
2.4.1 Register course
Use Case Name:	Register course
Scenario :	Student are register  courses .
Brief Description:	Student can  register  courses. They can select the courses. They  can also change the courses. They  also change schedule time.

Actor:	 Student
Precondition:	Must need to login the system.
Post condition:	Register the courses. 
Flow of events:	
student	
System
	1.1	User must have an account for become a register user or login.
1.2	 select the courses by id
1.3	 change the schedule	1.1	Confirm the valid login

1.2	Confirm selection


1.3	Confirm the change
Exception Condition:	1.1	If  student can't enter the valid user name or password can't enter the system .
1.2	They enter the system but they enter the wrong course id.
1.3	They can't change the schedule time.










2.4.2 Select course
Use Case Name:	Select course
Scenario :	Student and professor select or change course.
Brief Description:	
Student can  change  the courses and de-select the courses. Teacher can change course   also they can de-select the course.

Actor:	 Student, professor
Precondition:	Must need to login the system.
Post condition:	Change course, De-select.
Flow of events:	
Student ,professor	
System
	1.4	User must have an account for become a register user or login.
1.5	 Change  the courses by id
1.6	 De-selection the course	1.4	Confirm the valid login

1.5	Confirm change


1.6	Confirm De-selection.
Exception Condition:	1.4	If  student and professor can't enter the valid user name or password can't enter the system .
1.5	They enter the system but they enter the wrong course id.
1.6	They can't change the courses.








2.4.3: Registration management
Use Case Name:	Registration management
Scenario :	Manage the registration system.
Brief Description:	
Register mange registration management.  Maintainers  the course offer, Assign teacher, change course , cancel course, close registration.

Actor:	 Register
Precondition:	Must need to login the system.
Post condition:	course offer, Assign teacher, change course , cancel course, close registration.
Flow of events:	
Register	
System
	1.7	User must have an account for become a register user or login.
1.8	 Assign professor
1.9change course by id
1.10 cancel course
1.11 close registration by id
	1.7	Confirm the valid login

1.8	Confirm assign


1.9	Confirm cancel.
1.10	conform cancel
1.11	conform close by id
Exception Condition:	1.7	If   can't enter the valid user name or password can't enter the system .
1.8	They enter the system but they enter the wrong course id.
1.9	They can't cancel curse
1.10	 can't close registration





2.5	System Sequence Diagrams
2.5.1 Register course
 











2.5.2 Select course

 
 



2.5.3 Manage Registration
 









2.6	Domain/Conceptual Model
 
 
 

 



2.7	Activity diagram

 














Chapter 3
System Design







 
3.	System Design
3.1	Sequence Diagrams
3.1.1 Register course
 

3.1.2 select course 
 




3.1.3 Manage Registration
 

3.2	Class Diagram
 



Chapter 4
Implementation
 
4.	Implementation
4.1 Tools & Technologies
For developing this system what tools and technologies will be used are given below:
Programming Language: PHP 
Server: XAMPP



















