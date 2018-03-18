# ProperyManagementApp
Application for adding Buildings having some Rooms in database.

## Language & Tools Used
Java,  MySQL,  Netbeans IDE, QuickDBD

## Library 
 [mysql-connector-java-5.1.46-bin](https://dev.mysql.com/downloads/connector/j/5.1.html) It  is the official JDBC driver for MySQL.
 
## Setting up database

+ Firstly,  create database using this [sql file](https://bitbucket.org/rkj2096/propertyapp/src/master/database/property_app.sql).
+ Then, create a user for this database.
+ Then in [HomePage.java file line number 70](https://bitbucket.org/rkj2096/propertyapp/src/8907a7967af5161ce4454dc2f7e68cf50715243b/src/guiPage/HomePage.java#HomePage.java-70) change host, username and password values with yours. 
+ Done!
## How to Run?
>Compile

    javac -cp <mysql-connector-java-5.1.46-bin path>; <src/propertyapp/PropertyApp.java path>
>Run

    java -cp <mysql-connector-java-5.1.46-bin path>; <src/propertyapp/PropertyApp path>
    
**OR**
   >Make jar file and run as follows 
   
    java -jar <propertyApp.jar path>
    
 [Creating a jar file](https://docs.oracle.com/javase/tutorial/deployment/jar/build.html)
 
## Preview
![Summary](https://lh3.googleusercontent.com/_6wovrQKmbOnMNu6SmWo0BWGqvFrnLy-QEoC5tDR76BABO2NJAWkp6ntpLTo56aqm6nkvofhOUVU "Summary Page")


----------
![Building](https://lh3.googleusercontent.com/dkK5z2gWuWCGbECQtt6aWWgHbIaSQIhkGKySwgLoCI8SC2nh0kNtwcs1cJcRBo9_Hrnhggi1ebEx)


----------
![Rooms](https://lh3.googleusercontent.com/zSVpbQiWJ5eC1mj7nDpE8rrRu3O5aNIV7iNkXecyc0fSKPGaKX15VLRbebHLy-Uhd3U5h6jlFwI9)



