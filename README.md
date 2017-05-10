# BasicInfo
Concept:
To start doing any basic activity in many businesses, there must be a profile for the one who is doing the job. Like when you start shopping online, you must have a name and an address. Or in an organization, employers must have a profile to indicate who they are and in which department they work.
These profiles are not part of the business of the system. They just provide information that the application needs to perform its job.
So for many applications there is a “module” just to collect and maintain basic information about the business. This module can be a .jar file or a web service, etc.
For this project you must create an application that contains the information needed.

About:
Suppose we are going to develop a software for a company for its internal use. In this company, we have employees (with different roles such as junior employee, senior employee and manager).

Requirements:
-	There must be a system admin to start with
-	Admin should be able to define employees
-	Admin must be able to define departments
-	Each employee works for one and only one department
-	Employees can be active, suspended, in a vacation leave and left the company
-	Employees can move from one department to another
-	Admin must be able to edit and delete employees
-	Admin must be able to edit and delete departments
-	History of an employee’s changing departments is not recorded
-	Managers can change employees’ status who:
o	Are in the departments that the manager is the head of
o	Are not managers
o	If employee has left the company, its status cannot change anymore

Entities:
Employee:
-	Name
-	Family
-	Date of birth
-	Date of start in the company
-	Date of status change
-	Status
-	Department
-	Employee type (manager, …)
-	Employment type (part time, hourly, permanent, …)
-	Title (engineer, operator, …)

Department:
-	Name
-	Manager
-	Section (engineering, research, hr, …)
-	Description

Duty:
Design an application from UI to DB that meets the requirements with having in mind that requirements may be added in future)

Note:
-	You can add properties to entities to have a better design.
-	You must include all properties that are mentioned
-	You can design your database with your desire. That is, it is not mandatory that “employee” table must have a “department id”

Enjoy!
