# Bus_mangement_system
The Bus Management System is a Java-based application designed to streamline bus operations, including seat booking, bus and employee management, and administrative controls. Built with a modular architecture, it provides a user-friendly interface for passengers and operators to manage accounts, book tickets, and access bus details efficiently.

#Features:
User Management: Passengers and operators can create accounts, log in, and access personalized features.
Booking System: Users can book tickets, check seat availability, and search by date or destination.
Bus Management: Operators can add buses, routes, fares, and assign employees to trips.
Administrative Controls: Secure admin panel for managing system operations.
Database Integration: Stores and retrieves data seamlessly using MySQL.
Responsive UI: Enhanced graphical interface for intuitive navigation.

#Technologies Used
Java: Core programming language for the application.
MySQL Connector: Facilitates database connectivity for data storage and retrieval.
SwingX: Enhances the Swing-based GUI with advanced components for a better user experience.

#System Architecture
The system is built with a modular design, utilizing the following key classes:

AddBooking: Manages seat reservations.
AddBusDetails: Adds bus details (route, capacity, departure times).
AddEmployee: Handles employee data (drivers, conductors, etc.).
AdminControlPanel: Provides admin access to system management.
AdminLogin: Secures admin login.
AllBusDetails: Displays comprehensive bus information.
AssignBus: Allocates buses to routes.
BusBooking: Manages the booking process.
BusDetails: Stores bus-specific data (ID, type, status).
BusManagement: Orchestrates system interactions.
DBUtils: Facilitates database operations.
DialogEg: Enhances UI with dialog boxes.
EmployeeDetails: Manages employee roles and schedules.
MainScreen: Displays the main application interface.
NewUser: Creates new user accounts.
UserControlPanel: Provides user-specific functionalities
UserLogin: Manages user login.
departDateDP: Handles departure date selection.


#Prerequisites:
Java Development Kit (JDK) 8 or higher.
MySQL Server for database management.
MySQL Connector/J library.
SwingX library for GUI components.

#Installation:
Clone the repository: git clone https: //github.com/sifat-bhuiyan/bus-management-system.git
Import the project into your preferred IDE (e.g., IntelliJ IDEA, Eclipse).
Add mysql-connector-java and swingx libraries to the project dependencies.
Configure the MySQL database by running the provided SQL scripts in the database folder.

#Database Setup:
Create a MySQL database named bus_management.
Update the database connection settings in DBUtils.java with your MySQL credentials.

#Run the Application:
Execute the MainScreen.java class to launch the application.
Log in as an admin or user to access respective features.
Challenges Faced
Database Connectivity: Issues with establishing a stable connection to the MySQL localhost.
UI Components: Difficulties integrating jxDatepicker for date selection.

#Future Enhancements
Implement real-time bus tracking and predictive maintenance.
Optimize performance with caching and cloud-based solutions.
Add a user feedback system to enhance user experience.

#License
This project is licensed under the MIT License. See the LICENSE file for details.
