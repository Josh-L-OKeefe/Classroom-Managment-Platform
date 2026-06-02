# Classroom Resource Management Platform

A PHP, SQL, and CSS web application for managing classroom booking requests in an educational environment.

## Overview

The Classroom Resource Management Platform allows instructors to request classroom bookings based on room availability, classroom capacity, and available technology resources. Administrative users can review submitted bookings, view available rooms, and update the status of booking requests.

This project was developed as part of a database course project and demonstrates database-driven web application development using PHP, SQL, and CSS.

## Features

### User Role Selection

* Select between Instructor and Admin user roles
* Redirect users to the appropriate workflow based on selected role
* Maintain form data using PHP sessions

### Instructor Features

* Submit classroom booking requests
* View submitted bookings
* Review booking status
* Navigate through booking confirmation workflow

### Administrator Features

* View all submitted booking requests
* Filter booking records by room and status
* Review booking details including start time, end time, day of week, room ID, instructor ID, and course ID
* Edit booking status
* View available rooms
* Filter rooms by technology, capacity, and availability

### Room Management Features

* Display classroom information from the database
* Show room ID, capacity, location, technology features, and availability status
* Search rooms by available technology
* Filter rooms by capacity and availability

## Technologies Used

* PHP
* SQL
* CSS
* PHP sessions
* MySQLi database connection
* Prepared SQL statements

## Project Structure

```text
Project-root/
│
├── index.php          # User role selection page
├── page2.php          # Instructor workflow page
├── home.php           # Main application page
├── bookingspage.php   # Booking submission page
├── bookingView.php    # Booking viewing page
├── confirmation.php   # Booking confirmation page
├── adminView.php      # Admin booking review page
├── adminEdit.php      # Admin booking status update page
├── adminRoom.php      # Admin room viewing and filtering page
└── style.css          # Main stylesheet
```

## Database Functionality

The application connects to a SQL database and works with classroom booking data, room data, instructor information, course information, and booking status records.

The system uses SQL queries to:

* Retrieve available rooms
* Display booking records
* Update booking statuses
* Manage classroom and booking information
* Support administrator review workflows

## Application Workflow

1. The user opens the application and selects a role.
2. Instructors are directed to the booking workflow.
3. Instructors submit classroom booking requests.
4. Booking information is stored in the SQL database.
5. Admin users can view all submitted bookings.
6. Admin users can filter bookings and rooms.
7. Admin users can edit booking statuses.
8. Booking updates are saved back to the database.

## Skills Demonstrated

This project demonstrates experience with:

* PHP server-side development
* SQL database integration
* Database-driven web application design
* PHP session management
* Role-based application flow
* Prepared SQL statements
* Dynamic table generation
* Form handling
* Booking status management
* CSS styling
* Basic client-side filtering

## Future Improvements

Potential improvements include:

* Secure password-based login system
* Stronger user authentication and authorization
* Password hashing
* Input validation improvements
* Improved scheduling conflict prevention
* Email notifications for booking approvals or cancellations
* Calendar-style booking interface
* Mobile-responsive layout improvements
* Admin reporting dashboard
* Improved database configuration security

## Author

Joshua O'Keefe

GitHub: https://github.com/Josh-L-OKeefe

LinkedIn: https://www.linkedin.com/in/joshua-o-keefe-bb10522a4/
