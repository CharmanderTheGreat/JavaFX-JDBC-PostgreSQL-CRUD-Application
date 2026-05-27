# Student Record Management System

A desktop application designed to manage student records through a graphical user interface. This project integrates JavaFX for the front-end layout and PostgreSQL for data persistence, utilizing JDBC for seamless database operations.

## System Features
* **Student Registration**: Inserts new student names, courses, and year levels into the system.
* **Data Display**: Automatically loads and lists all existing student records in a structured TableView.
* **Record Modification**: Selecting any row from the table loads the data back into the input fields for updating.
* **Record Deletion**: Permanently removes selected student profiles from the system database.
* **Form Reset**: Clears all active text fields and dropdown selections with a single action.

## Core Components
* **User Interface**: Built using JavaFX and SceneBuilder(FXML) for a clean, interactive design.
* **Database Integration**: Connected to a PostgreSQL instance via JDBC to handle CRUD transactions.
* **Data Mapping**: Uses dedicated model classes and Java Enums to ensure type-safe data handling and proper TableView binding.