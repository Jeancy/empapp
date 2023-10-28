# empapp
Console based employee management project created with Netbeans, Maven, Java, JDBC and MySQL technologies
This project is good for learners to undersatand how java database connectivity works.
This project implementes the CRUDE operations in a very simple way.
You will understand how to connect your java project to mysql database and manipulate the database throug java program.
We have 5 java files:
Emapp class which is our main class that will run all the operations and display differents results for different scenarios like displayind and deletion of employee record.
Employee class which describes and defines the employee attributes and all the relevant methodes and constractors.
EmployeeDAOintrf interface that defines all the methods to be implemented in the project, this promote loose coupling and high cohesion.
EmployeeDAOimpl class which implentes and clarifies all the methods defined in the interface.
DBConnection class is the class we used to create the connection to the database by providing all the database credentials.
