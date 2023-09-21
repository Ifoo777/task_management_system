# task_management_system

## About The Project
The Task Management System is a simple project that can help manage task progress. The system has 3 types of system users which are the Admin, Brother , Sister and child for various roles or tasks.
The Admin user is those users that has an access to all of the data stored in the database of the system especially on creating and managing system users. 
The Brother or Sister are those users that manage the project details and progress under her/his management.
The Children will submit their work productivity in each task of the project
which makes the system requires the employee to submit their start and end time range of their work on a certain task and this data will be calculated in the report as project members' work duration.

How the System Works
The Task Management System users can be only created by admin users. The admin user or the other roles will create a new project at first along with some important details and references of the users. When creating a project, the admin or project managers must list all the users that will handle the project's tasks. After the creation of the project, the regular roles are limited only to adding their work progress for the task of the project that they are assigned. They are also allowed to edit the data of the progress that they only submitted.
Then, as they will regularly updating the system about the progress they have done the project managers will read or scan their activities so the project manager can check or decide if the certain task is done and need to update the task status in the system.
For the printable report of the system, only the admin users and project managers has an access to this function or feature of the system.

Features:
Login Page
Home Page
Project (CRUD Features)
Task List Page
Progress Form
Report Generation
User (CRUD Features)

## How To Run??
Above all, to run this project you must have installed a virtual server i.e XAMPP on your PC.

1st Step: Firstly, Extract the file
2nd Step: After that, Copy the main project folder
3rd Step: So, you need to Paste in xampp/htdocs/

Further, Now Connecting Database

4th Step: So, for now, Open a browser and go to URL “http://localhost/phpmyadmin/”
5th Step: After that, Click on the databases tab
6th Step: So, Create a database naming “tms_db” and then click on the import tab
7th Step: Certainly, Click on browse file and select “tms_db.sql” file which is inside the “db” folder
8th Step: Meanwhile, click on Go button.

After Creating Database,

9th Step: Moreover, Open a browser and go to URL “http://localhost/task_management_system”

Admin Access
Email: admin@admin.com
Password: admin123
