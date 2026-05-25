# Parking-System
This is a command-line Parking Management System built in Python for three KwaZulu-Natal shopping malls:

  - Gateway Theatre of Shopping (Umhlanga)
  - Pavilion Shopping Centre (Westville)
  - La Lucia Mall (La Lucia)
    
The system supports three user roles (Customer, Admin,
Owner) and stores all data in JSON files so information
is retained between program runs.

HOW TO RUN
----------
-Requirements: Python 3.x (no extra libraries needed)
-Unzip the project folder
-vscode or pycharm


1. Make sure all files are in the same folder:
     Main.py
     users.json
     parking.json
     payments.json

2. Open a terminal in that folder and run:
     python Main.py
   or on some systems:
     python3 Main.py


DATA FILES
----------
users.json    : All registered user accounts
parking.json  : All vehicle entry/exit/fee records
payments.json : All confirmed payment records

These files are created automatically if they do not
exist. Do not delete them during a session or parking
records will be lost.

