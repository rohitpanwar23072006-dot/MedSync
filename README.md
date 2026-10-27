# MedSync
### Smart Medicine Management Platform

MedSync is a web-based medicine management platform designed to connect patients, doctors, pharmacists, and administrators in one place. It simplifies prescription management, appointment booking, medicine ordering, pharmacy inventory tracking, and health reminders.

## Features

### Patient
- Secure registration and login.
- Search for doctors by specialization.
- Request and manage appointments.
- View prescriptions and medical records.
- Search medicines and compare pharmacy prices.
- Order medicines from pharmacies.
- Receive medicine reminders and stock alerts.

### Doctor
- Manage doctor profiles and availability.
- View and respond to consultation requests.
- Access patient consultation details.
- Create and manage prescriptions.
- Record diagnoses and medicine instructions.

### Pharmacist
- Manage pharmacy medicine inventory.
- Add and update medicine stock and prices.
- Track medicine expiry dates.
- Monitor low-stock medicines.
- Manage and update medicine orders.

### Administrator
- Manage users and platform access.
- Verify doctors and pharmacists.
- Monitor platform activity.
- Handle complaints and user management.

## Tech Stack

**Frontend**
- HTML
- CSS
- JavaScript

**Backend**
- Java
- Spring Boot
- Spring Data JPA
- Spring Security

**Database**
- MySQL

**Tools**
- IntelliJ IDEA / VS Code
- MySQL Workbench
- Maven
- Git and GitHub

## Architecture

MedSync follows a layered backend architecture:

- **Model:** Represents application data and database entities.
- **Repository:** Handles database operations.
- **Service:** Contains application business logic.
- **Controller:** Handles HTTP requests and API responses.
- **Configuration:** Manages security and application settings.

## Installation and Setup

### Prerequisites
- Java 17 or compatible version.
- MySQL Server.
- Maven.
- Git.

### 1. Clone the Repository

```bash
git clone https://github.com/rohitpanwar23072006-dot/MedSync/edit/main/README.md
cd MedSync
```

### 2. Configure the Database

Create a MySQL database:

```sql
CREATE DATABASE medsync;
```

Update `src/main/resources/application.properties` with your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/medsync?createDatabaseIfNotExist=true
spring.datasource.username=YOUR_MYSQL_USERNAME
spring.datasource.password=YOUR_MYSQL_PASSWORD
```

Replace the username and password with your own local MySQL credentials.

### 3. Run the Application

Using Maven:

```bash
mvn spring-boot:run
```

Alternatively, run the `MedSyncApplication.java` file from your IDE.

### 4. Open the Application

Once the application starts, open:

http://localhost:8080

## Security

- Role-based access for patients, doctors, pharmacists, and administrators.
- Password encryption using BCrypt.
- Session-based authentication.
- Verification requirements for healthcare providers.
- Restricted access to protected application features.

## Project Objective

The objective of MedSync is to reduce the difficulties associated with managing medicines, prescriptions, appointments, and pharmacy inventory by providing a centralized digital platform.

## Future Enhancements

- SMS and email notifications.
- Medicine interaction checks.
- Online payment integration.
- Enhanced medical report management.
- Improved appointment scheduling.
- Detailed medication adherence reports and analytics.

## Project Status

MedSync is an ongoing full-stack web application project focused on practical healthcare management and role-based system design.

## License

This project is intended for educational and demonstration purposes.


### Extract the ZIP File

1. Download the MedSync project ZIP file to your computer.
2. Locate the downloaded ZIP file in File Explorer.
3. Right-click the ZIP file and select **Extract All**.
4. Choose a destination folder and click **Extract**.
5. Open the extracted `medsync` project folder in VS Code or your preferred IDE.
6. Follow the installation and setup instructions below to configure the database and run the application.

---



**MedSync — Simplifying Medicine Management, Connecting Healthcare.**
