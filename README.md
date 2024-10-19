Attendance Management System
Overview

The Attendance Management System is a simple Python-based application that allows teachers to manage student attendance efficiently. It provides functionalities for adding teachers and students, marking attendance, and viewing attendance records. The system utilizes SQLite as its database to store user information and attendance records, ensuring that all data is persistent and easily retrievable.
Features

    Teacher Management:
        Add new teachers with a unique username and password.
        Login functionality for teachers to access their accounts.

    Student Management:
        Add multiple students associated with a specific teacher.

    Attendance Tracking:
        Mark attendance for students on a given date.
        Update attendance records if they already exist.

    Attendance Viewing:
        View attendance records for each student on a specified date.

Technologies Used

    Python
    SQLite
  Usage
Adding a Teacher

    When prompted, enter the teacher's name.
    Provide a unique username for the teacher.
    Set a password for the teacher.

Logging In

    Select "Login as Teacher" from the main menu.
    Enter the username and password to log in.

Adding Students

    After logging in, select the option to add students.
    Specify the number of students you want to add.
    Enter each student's name when prompted.

Marking Attendance

    Select the option to mark attendance after logging in.
    Enter the date for which you want to mark attendance.
    Indicate the presence (y/n) for each student.

Viewing Attendance

    Select the option to view attendance after logging in.
    Enter the date to see the attendance records for that day.

Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.
[10:21 pm, 19/10/2024] Varun: Railway Management System
Overview

The Railway Management System is a simple console-based application built in Python that allows administrators to manage train ticket bookings. It uses an SQLite database to store information about tickets, making it easy to create and cancel bookings while recording essential traveler details. The system aims to provide a basic yet functional interface for managing railway ticket operations.
Features

    Admin Login: Secure access to the system with default credentials.
    Create Ticket: Input traveler details including name, mobile, email, travel date, departure station, and destination station.
    Cancel Ticket: View and cancel existing tickets based on their unique IDs.
    View Tickets: Display all active tickets with detailed information.
    SQLite Database: Utilizes an SQLite database for persistent storage of ticket information.

Prerequisites

Before running the application, ensure you have Python installed on your system. This project uses only built-in Python libraries, so no additional installations are necessary.

    Python 3.x
    SQLite (included with Python)

Installation
Usage

    Admin Login: The default admin username is admin and the password is password. Enter these credentials to access the system.

    Creating a Ticket:
        Select the option to create a ticket.
        Input the traveler's name, mobile number, email, travel date (in YYYY-MM-DD format), departure station, and destination station.
        Confirm the creation of the ticket.

    Canceling a Ticket:
        Select the option to view tickets to see the available ones.
        Enter the ticket ID of the ticket you wish to cancel.
        Confirm the cancellation.

    Viewing Tickets:
        Select the option to view tickets to see all active bookings.

    Exiting: You can exit the system at any time by selecting the exit option.

Contribution

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

    Fork the repository.
    Create a new branch (git checkout -b feature/YourFeature).
    Make your changes and commit them (git commit -m 'Add some feature').
    Push to the branch (git push origin feature/YourFeature).
    Open a pull request.
