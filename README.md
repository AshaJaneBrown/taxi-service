![Logo](https://img.freepik.com/premium-vector/retro-car-taxi-classic-taxi-vintage-style_719918-7.jpg?w=360)

# Taxi Service

This app is a simplified version of the taxi service

## :orange_circle: Features

- Registration of new drivers
- Adding new cars and manufacturers
- Assigning cars to drivers
- Displaying info about cars, drivers and manufacturers

## :orange_circle: Project Structure

The project has N-Tier Architecture with the following tiers:

- DAO. Storing and retrieving data from a database
- Service. Logical part of the application
- Controller. Interaction with a user

## :orange_circle: Technologies

Java 17, Maven, MySQL, JDBC, Tomcat, JSP 

## :orange_circle: Quickstart 

To launch the project:

- Fork this repository
- Clone the repository to PC
- Create necessary database tables using init_db.sql
- Configure ConnectionUtil class
```
  private static final String URL = "URL";
  private static final String USERNAME = "USER NAME";
  private static final String PASSWORD = "PASSWORD";
  private static final String JDBC_DRIVER = "JDBC DRIVER";
```
- Install Tomcat (9.0.50)
- Add Tomcat server to configuration
- Run the project
