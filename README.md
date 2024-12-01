# HRAdminSystem-for-Tech-Genius
This repository is for a HRAdminSystem for a company named Tech Genius.

This HR Administration System is designed to manage employee details and their associated departments efficiently. This project was developed as part of a tech test for Tech Genius, demonstrating capabilities in handling secure login systems and CRUD operations within a .NET environment using Entity Framework.

#Features
User Login: Secure authentication for different roles.
Employees List View: Display all employees with options to edit or add new entries.
Employee Create/Edit View: Allows for the creation and modification of employee details.
Departments List View: View all departments with edit and create capabilities.
Departments Create/Edit View: Manage department details.

#Prerequisites
Before you begin, ensure you have met the following requirements:
.NET SDK (.NET 6.0)
Entity Framework
A compatible SQL server (I used sqlite3)


#Installation
Clone the repository to your local machine:
git clone https://github.com/MOARBEE/HRAdminSystem.git
Navigate to the project directory:
cd HRAdminSystem


#Configuration
Update the appsettings.json with your SQL server connection string.
Apply migrations to set up your database:
dotnet ef database update


#Running the Project
To run the project locally, use the following command in the root directory:
dotnet run
This will start the application on http://localhost:5000 (or a different port configured in your settings).

#Usage
Log in using the provided super user credentials:
Username: hradmin@test.com
Password: TestPass1234!
Navigate through the application to manage employees and departments as per your role privileges.

You can also log in as the employee with the following credentials:
username of the employee:
Password: Password123#


#Best Practices
This project adheres to best coding practices, focusing on readability, maintainability, and secure coding standards. Ensure you follow these principles when modifying or extending the project.
