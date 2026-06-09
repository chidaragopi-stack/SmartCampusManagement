Step 1: Install Required Software

        Install Java JDK 17 or above
        Install IntelliJ IDEA Community Edition
        Install MySQL Server
        Install MySQL Workbench
        Download MySQL Connector/J (JDBC Driver) 
Step 2: Create Database

        Open MySQL Workbench
			  Create all tables from the document
        After creating tables, insert login data

Step 3: Create IntelliJ Project

        Open IntelliJ IDEA
        Click New Project
        Select Java
        Select JDK
        Click Create
Step 4: Create Package

        Inside src
        Right Click → New → Package

Step 5: Add MySQL Connector

        Download MySQL Connector/J
        Open IntelliJ
        File → Project Structure → Libraries

Step 6: Create Java Files

        Inside package com.smartcampus

Step 7: Configure Database Connection

        In DBConnection.java
				to your MySQL username and password
step 8: Verify data in MySQL Workbench

		    SELECT * FROM students;
        SELECT * FROM faculty;
        SELECT * FROM attendance;
        SELECT * FROM complaints;
        SELECT * FROM events;

step 9:Project completed successfully when

       Database connects successfully.
       Login works.
       Student data is inserted and displayed.
       Faculty data is stored.
       Attendance is recorded.
       Complaints are saved.
       Events are added.
       No compilation errors occur

step 10:Run the project and verify all modules are working correctly.

      Execute MainMenu.java.
      Login with valid credentials.
      Test Student, Faculty, Attendance, Complaint, and Event modules.
      Verify data is stored in the MySQL database.
      Exit the application.
Project Status: Successfully Executed and Tested.			 
				
        
