# Course-Registration-System
The Course Registration System is a Java-based desktop application that allows students to register for courses and administrators to manage courses and student registrations efficiently. The system integrates with a MySQL database to store and retrieve all data.
Course Registration System.

Features

Student Module

View all available courses with details like title, instructor, description, duration, and course image.

Search for specific courses.

Register for one or multiple courses.

Logout after successful registration.


Admin Module

Add new courses with details (course name, description, instructor, duration, and image path).

Edit and delete existing courses.

View all student registrations.

Search for students and their registered courses.

Technologies Used

Programming Language: Java (Swing for GUI)

Database: MySQL

IDE: Apache NetBeans

Connector: MySQL JDBC Driver

Database Design

The system uses four tables:

Admin – Stores admin credentials.

Student – Stores student details.

Courses – Stores course details.

Student_Courses – Maps students to the courses they register for.

Installation Steps

1. Clone the Repository:

git clone https://github.com/your-username/Course-Registration-System.git


2. Set Up the Database:

Create a MySQL database named miniproject.

Import the tables and data from database.sql (if provided).



3. Configure Database Connection:

Open the DBConnection.java file.

Update your MySQL username and password in the connection string.



4. Run the Project:

Open the project in NetBeans.

Compile and run the AdminLogin.java or StudentLogin.java files.


Usage

Admins can log in to manage courses and view registrations.

Students can log in or directly view available courses, register, and logout.

Screenshots

Outputs are available in the Screenshots of output.zip file
Future Enhancements

Add email notifications for student registrations.

Enable password recovery and user profiles.

Add a web-based interface using JSP/Servlet or Spring Boot.

License

This project is open-source and free to use.

👨‍💻 Author

Developed by Keerthana K G
Contact: kgkeerthana693@gmail.com
