# 🚖 My Taxi Service 🚕
## Description
Welcome to My Taxi Service! This project is a simple imitation of a taxi service application for drivers.
<br>With this app, you can easily manage various tasks related to drivers, manufacturers, and cars:
- Register new drivers, log in as already registered driver, and log out from the system
- Display all registered drivers or delete a specific driver
- Create manufacturers, delete or display all existing manufacturers
- Create new cars based on manufacturers, delete or display all existing cars
- Add drivers to cars (one driver can have multiple cars, and one car can have multiple drivers)
- Each driver can display all of their current cars
## Getting Started
- Clone this repository: `git clone https://github.com/Deschna/my-taxi-service.git`
- Initialize DB with script located in `src/main/resources/init_db.sql`
- Replace `URL`, `USERNAME`, `PASSWORD` and `JDBC_DRIVER` values in `src/main/java/taxi/util/ConnectionUtil.java` with suitable for your database
- Build the project using Maven (write `mvn clean package` command in your terminal)
- Deploy the WAR file to a servlet container (Tomcat for example)
- Navigate to http://localhost:8080 in your browser
## Used Technologies
- Java `17.0.6`
- Apache Maven `3.8.7`
- MySQL `8.0.22`
- Javax Servlets `4.0.1`
- Tomcat `9.0.73`
## Authors
[Déschna (Ditkovskyi Pasha)](https://github.com/Deschna)