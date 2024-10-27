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
