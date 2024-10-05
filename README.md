# Expense Tracker WebApp
## Overview
This Expense Tracker is a simple web application that allows users to track their daily expenses efficiently. The app helps users organize their spending habits by categorizing expenses and providing an overview of their financial activities.

The application is built using Java 17, Maven, and Spring Boot, with H2 Database for testing purposes.
## Features
Add, update, and delete expenses.
Categorize expenses (e.g., Food, Transport, Entertainment).
View expense history.
Search expenses by category or date.
Summary dashboard showing total expenses over time.

## Tech Stack
 - Java 17: The core programming language
 - Spring Boot: Framework for building the web application
 - Maven: Dependency management and project building
 - H2 Database: In-memory database used for testing
 - Spring Data JPA: For database interactions

## Steps
### Clone the repository:
git clone https://github.com/yourusername/expense-tracker.git
### Navigate to the project directory:
cd expense-tracker
### Run the application using Maven:
mvn spring-boot:run
### Access the app in your browser at http://localhost:8080
![webapp_java_springboot](https://github.com/user-attachments/assets/2f92e80c-c4d8-4484-922f-d8e435184629)


## Testing with H2 Database
The app is configured to use the H2 in-memory database for testing purposes. You can access the H2 console to view the database schema and data:

![webapp_h2_testing](https://github.com/user-attachments/assets/60b12c80-270a-4687-99dc-8d339430228d)

 - H2 Console: http://localhost:8080/h2-console
 - JDBC URL: jdbc:h2:mem:testdb
 - Username: sa
 - Password: (leave it empty) 

## Usage
- Launch the application.
- Add expenses by providing details like date, amount, and category.
- Use the dashboard to view summaries of your expenses.
- Edit or delete any expense as needed.

## Future Improvements
- Integration with a persistent database (e.g., MySQL, PostgreSQL)
- User authentication and authorization
- Expense analytics with charts
- API for mobile apps

## Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a feature branch: git checkout -b feature-name.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-name.
Open a pull request.

## License
This project is licensed under the Gnome license
