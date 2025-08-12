# Airline Management System

## Overview
The **Airline Management System** is a Java desktop application for managing basic airline operations—viewing flights, booking and canceling tickets, and administering passenger and flight data through a graphical user interface.

## Features
- Add, update, delete flight details
- Book and cancel tickets
- Manage passenger information
- Data persistence using a relational database
- Icon-based GUI enhancements
- Includes SQL database file for initializing the data model

## Technologies Used
- Java (Swing/AWT for GUI)
- JDBC for database connectivity
- Relational database (such as MySQL)
- GUI icons and assets included

## Project Structure

<img width="323" height="369" alt="image" src="https://github.com/user-attachments/assets/46459a8e-ee47-49c4-97d3-e66538b2c894" />

## Setup & Run Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Gaya3-hue/Airline-Management-System.git
   cd AirlineManagementSystem-master
   
2. Import the project into your IDE (Eclipse, IntelliJ, NetBeans).

3. Set up the database:

- Create a local database.
- Import the SQL file from the database/ folder.

4. Configure JDBC connection in your code:
   
String url = "jdbc:mysql://localhost:3306/your_database";
String user = "root";
String password = "your_password";

5. Run the application using your IDE's run functionality.

Downloadable Assets

- Icons & Database Files: Google Drive Link
- Complete Project Archive: Google Drive Link

License
This project is released under the MIT License.
