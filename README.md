
# Bioinformatics Data Portal

A web-based application developed with PHP and MySQL for managing and analyzing bioinformatics data. The portal allows users to register, log in, and upload their bio data (such as gene sequences or other scientific data). It is designed to help researchers and bioinformaticians store and access biological data in an organized manner.

## Features

- **User Registration and Authentication**: Users can create an account and log in securely.
- **Dashboard**: A personalized dashboard where users can upload, view, and manage their bio data.
- **Data Upload**: Users can upload bio data in a structured format and view it on their dashboard.
- **Data Security**: Passwords are encrypted, and user information is stored securely in the database.

## Technologies Used

- **Frontend**:
  - HTML
  - CSS (Optional for future styling)

- **Backend**:
  - PHP (Server-side scripting)
  - MySQL (Database for storing user and data information)
  - XAMPP (Local server setup)

## Setup Instructions

### Prerequisites

1. **Install XAMPP**: 
   - Download and install XAMPP from [https://www.apachefriends.org](https://www.apachefriends.org).
   - Make sure the Apache and MySQL services are running.

2. **Create a Database**:
   - Open phpMyAdmin (usually accessible at `http://localhost/phpmyadmin/`).
   - Create a new database, e.g., `bio_data_portal`.
   - Run the following SQL query to create a table for users:

   ```sql
   CREATE TABLE users (
     id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY,
     username VARCHAR(50) NOT NULL,
     email VARCHAR(100) NOT NULL,
     password VARCHAR(255) NOT NULL
   );


**Installation**
Clone or download this repository.

Move the project files to the htdocs folder in your XAMPP installation directory (C:\xampp\htdocs on Windows).

Open localhost in your browser and navigate to the project folder (e.g., http://localhost/bio-portal).

Register an account or log in with existing credentials.
