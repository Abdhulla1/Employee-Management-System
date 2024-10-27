# Employee Management System (EMS)

A web application developed using Agile methodologies to manage employee records and project data, created by Genze Align Technologies.

## Overview

The EMS enables efficient management of employee and project details, providing role-based access for admins and employees, with additional features for finance management and secure email notifications.

## Key Features

- **Admin Dashboard**: Complete control over employee data, projects, and roles.
- **Employee Dashboard**: Access to personal, project, and finance information.
- **Role-Based Access**: Customized views and permissions for admins and employees.
- **Finance Management**: Includes CTC breakdown and downloadable payslips.
- **Automated Email Notifications**: Sends login credentials and updates using JavaMail.

## Technologies Used

- **Frontend**: React
- **Backend**: Spring Boot
- **Database**: MySQL
- **Authentication**: Spring Security with JWT
- **Email Notifications**: JavaMail Sender
- **Lombok**: Used to reduce boilerplate code in Java.

## Lombok

This project utilizes Lombok to simplify code. To use Lombok, add the following dependency to your `pom.xml`:

```xml
<dependency>
    <groupId>org.projectlombok</groupId>
    <artifactId>lombok</artifactId>
    <version>1.18.24</version> <!-- Use the latest version -->
    <scope>provided</scope>
</dependency>

Using Lombok

To enable Lombok in your IDE:

    IntelliJ IDEA: Install the Lombok plugin and restart your IDE.
    Eclipse: Download the Lombok jar from the Lombok website and run it to set up.

Installation
Clone Repository:

bash

git clone https://github.com/yourusername/ems-project.git

Backend Setup:

    Configure email and app password in the application.properties file:

properties

spring.mail.username=your-email@example.com
spring.mail.password=your-app-password

    Start the backend:

bash

mvn spring-boot:run

Frontend Setup:

    Navigate to the frontend directory, then run:

bash

npm install
npm start

Usage

    Admin Login: Manage all employee records and projects.
    Employee Login: Access to individual details, project information, and finance documents.

Development Process

This project followed Agile development practices, focusing on iterative progress and collaboration, allowing for regular updates and improvements based on feedback.
Screenshots

    Login Page: Shared for both Admin and Employee roles.
    Admin Dashboard: Full access to manage all aspects of employee data.
    Employee Dashboard: Displays personal, project, and financial details.

License

This project is open-source, released under the MIT License.
GitHub Project Link

Click here to view the GitHub repository

markdown


### Notes:
- Replace `yourusername` in the GitHub Project Link with your actual GitHub username.
- You can also include actual screenshots if you have them, or add any other sections that might be relevant to your project. Let me know if you need any further modifications!


