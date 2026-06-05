Class Scheduler Tool

C# MySQL Visual Studio

A robust desktop application designed to automate and streamline the process of
academic scheduling. This tool helps educational institutions manage teacher
workloads, room assignments, and time slots while ensuring data integrity
through a centralized database.

🚀 Features

  - Teacher Management: Create, update, and manage teacher profiles and their
    respective subject specializations.
  - Automated Scheduling: Efficiently assign time slots and rooms to avoid
    manual errors.
  - Conflict Detection: Built-in logic to prevent double-booking of teachers or
    classrooms.
  - Database Integration: Seamlessly save and load scheduling data using MySQL,
    allowing for persistent storage and easy retrieval.
  - User-Friendly Interface: Intuitive UI built with Windows Forms for ease of
    use by administrative staff.

🛠️ Tech Stack

  - Language: C# (.NET Framework)
  - Database: MySQL
  - IDE: Visual Studio
  - Database Connector: MySQL Data Connector for .NET

📋 Prerequisites

Before running the project, ensure you have the following installed:

  - .NET Framework (Version used in project)
  - MySQL Server
  - MySQL Workbench (Optional, for database management)
  - Visual Studio 2022 or later

⚙️ Installation & Setup

1.  Clone the Repository:

    git clone https://github.com/Shotic/ClassSchedulerTool.git

2.  Database Configuration:

      - Open MySQL Workbench and create a new database named scheduler_db.
      - Import the provided .sql file (if available) or create tables for
        Teachers, Schedules, and Rooms.
      - Update the Connection String in the source code (usually in App.config
        or the Database Helper class):

    string connString = "server=localhost;user=root;database=scheduler_db;port=3306;password=YOUR_PASSWORD;";

3.  Build the Project:

      - Open the .sln file in Visual Studio.
      - Restore NuGet packages if prompted.
      - Press F5 to build and run the application.

📸 Screenshots

(Optional: I recommend adding a "Screenshots" folder to your repo and linking an
image here to show off the UI)

🛠️ Future Enhancements

  - Add an "Export to PDF/Excel" feature for printing schedules.
  - Implement a Drag-and-Drop UI for easier schedule adjustments.
  - Multi-user authentication for different administrative levels.

👤 Author

Ju-Ben Jacob C. Aquino

  - BSIT Student at Bulacan State University
  - GitHub: @Shotic
  - Email: jubenjacob49@gmail.com

This project was developed as part of my focus on Software Development and
Database Management.
