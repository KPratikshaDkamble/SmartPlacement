# SmartPlacement
# Placement Management System

## Introduction
The Placement Management System is a web application developed using PHP. It is designed to streamline the process of managing placements in an organization or educational institution. The system allows administrators to create job postings, track applications, and manage the overall placement process efficiently.

This readme file provides an overview of the system's features, installation instructions, and basic usage guidelines.

## Features
1. User Roles:
   - Administrator: Manages the entire placement process, including creating job postings, reviewing applications, and updating the status of placements.
   - Students: Can view and apply for available job postings, track the status of their applications, and receive notifications.
  
2. Authentication:
   - Users can register and log in using their email and password.
   - Passwords are stored securely using encryption.

3. Dashboard:
   - Provides an overview of the placement process, including the number of active job postings, pending applications, and completed placements.
   - Shows important notifications and updates.

4. Job Postings:
   - Administrators and Placement Cellcan create new job postings by providing details such as job title, description, requirements, and application deadline.
   - Job postings can be categorized based on industry, location, or other criteria.

5. Application Tracking:
   - Students can browse and apply for available job postings.
   - Administrators  can review applications, shortlist candidates, and schedule interviews.
   - The status of applications is tracked throughout the placement process.

6. Notifications:
   - Users receive email notifications for important events, such as application status updates and interview schedules.

7. Communication:
   - Placement Cell can communicate with students through the system to schedule interviews or provide additional information.
   - Students can ask questions or seek clarification regarding job postings.

## Installation
To set up the Placement Management System, follow these steps:

1. Requirements:
   - PHP (version 7.0 or later)
   - MySQL 
   - Web server (XAMPP)

2. Clone the repository:
   ```
   git clone https://github.com/your-username/placement-management-system.git
   ```

3. Configure the database:
   - Create a new database for the system.
   - Import the database schema using the provided SQL file (placement_portal.sql`).
   - Update the database connection details in the `db.php` file.

4. Set up the email configuration:
   - Update the email settings in the `email.php` file to enable email notifications.
   - Provide the SMTP server details, email address, and password for sending emails.

5. Deploy the application:
   - Move the cloned files to the web server's document root directory.
   - Ensure that the web server has appropriate read and write permissions on the application files.

6. Access the application:
   - Open a web browser and navigate to the URL where the system is deployed.
    link:http://placementkiet.000webhostapp.com/

## Usage
1. Registration:
   - Students, Placement Cell, and administrators can register as new users using the registration form.
   - Upon successful registration, users will receive a confirmation email.

2. Login:
   - Users can log in using their registered email and password.

3. User Interface:
   - The application provides an intuitive user interface to navigate through various features.
   - Users can access their respective dashboards and perform actions based on their roles.

4. Job Postings:
   - Administrators and Placement Cell  can create new job postings.
   - Students can browse the available job postings and apply for the ones they are interested in.

5. Application Tracking:
   - Students can track the status of their applications, view updates, and receive notifications.
   -
