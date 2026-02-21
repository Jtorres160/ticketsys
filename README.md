# ticketsys
IT Ticketing System

A lightweight IT ticketing system built in Python that allows users to create, track, update, and resolve support tickets. This project simulates a real-world help desk workflow and is designed to demonstrate core programming concepts, data handling, and system logic.

Features

Create new IT support tickets

View all existing tickets

Update ticket status (Open, In Progress, Resolved, Closed)

Assign tickets to technicians

Add notes and updates to tickets

Delete tickets

Persistent data storage (file or database based, depending on implementation)

Simple and intuitive interface (CLI or GUI)

Technologies Used

Python 3

Standard Python libraries

Optional: SQLite (if database is used)

Project Structure
it-ticketing-system/
│
├── main.py
├── ticket.py
├── database.py        # if applicable
├── utils.py
├── README.md
└── requirements.txt
Installation
1. Clone the repository
git clone https://github.com/yourusername/it-ticketing-system.git
cd it-ticketing-system
2. Create a virtual environment (recommended)
python -m venv venv

Activate it:

Windows:

venv\Scripts\activate

Mac / Linux:

source venv/bin/activate
3. Install dependencies
pip install -r requirements.txt
Usage

Run the application using:

python main.py

Follow the on-screen menu to:

Create tickets

View and manage tickets

Update statuses

Assign technicians

Add notes

Example Workflow

User submits a ticket

Ticket is logged with status Open

Technician assigns themselves

Status changes to In Progress

Issue is resolved → Status becomes Resolved

Ticket is archived or closed

Learning Objectives

This project demonstrates:

Object-Oriented Programming (OOP)

File handling / database management

Data structures

CLI-based UI design

Real-world system modeling

Clean coding practices

Future Improvements

Web-based interface (Flask or Django)

User authentication system

Role-based permissions (Admin, Technician, User)

Ticket priority system

Email notifications

REST API integration

Screenshots (Optional)

Add screenshots of the application interface here.

License

This project is licensed under the MIT License.

Author

Jose Torres
Python Developer
