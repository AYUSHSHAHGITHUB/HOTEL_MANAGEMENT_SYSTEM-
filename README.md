# HOTEL MANAGEMENT SYSTEM

## Overview

The HOTEL MANAGEMENT SYSTEM is a Python-based project that utilizes the SQLite3 database to provide efficient management of hotel operations.
It is designed to streamline key tasks such as managing room bookings, customer information, and payment processing. 
This project is ideal for small to medium-sized hotels looking for a robust and user-friendly solution.



## Features

1. User-Friendly Interface:

   - Simple and intuitive command-line interface.

2. Customer Management:

   - Add, update, view, and delete customer information.

3. Room Management:

   - View available rooms.
   - Allocate and deallocate rooms.

4. Reservation System:

   - Book and cancel reservations.
   - Check-in and check-out functionality.

5. Billing System:

   - Generate detailed bills.
   - Support for multiple payment methods.

6. Database Integration:

   - Stores all data in an SQLite3 database for persistence and security.

-------------------------------------------------------------------------------------------------------

## Installation

### Prerequisites:

- Python 3.x
- SQLite3 (pre-installed with Python)

### Steps:

1. Clone or download the repository:

  
   git clone <repository_url>
   cd hotel-management-system
   

2. Install required Python libraries:

      pip install -r requirements.txt
   
----------------------------------------------------------------------------------------------------

3. Initialize the database:

     python setup_database.py


4. Run the application:

   python main.py
   

-------------------------------------------------------------------------------------------------------

## Project Structure

```
project_folder/
|-- main.py               # Entry point for the application
|-- setup_database.py     # Script to initialize the SQLite3 database
|-- database.db           # SQLite3 database file
|-- modules/
|   |-- customer.py       # Customer management module
|   |-- room.py           # Room management module
|   |-- billing.py        # Billing module
|-- utils/
|   |-- helpers.py        # Utility functions
|-- README.md             # Project documentation (this file)

```


-------------------------------------------------------------------------------------------------------

## Usage

1. Starting the Application:
   Run `main.py` to start the system. Navigate through the menu options to perform operations like booking rooms, managing customers, and generating bills.

2. Database Setup:
   Use `setup_database.py` for initializing or resetting the database.

-------------------------------------------------------------------------------------------------------

## SQLite3 Database Schema

### Tables:

1. Customers:

   - id: Integer (Primary Key)
   - name: Text
   - phone: Text
   - email: Text

----------------------------------------------------------------------------------------------------

2. Rooms:

   - room_number: Integer (Primary Key)
   - room_type: Text
   - status: Text (Available/Occupied)

----------------------------------------------------------------------------------------------------

3. Bookings:

   - booking_id: Integer (Primary Key)
   - customer_id: Integer (Foreign Key)
   - room_number: Integer (Foreign Key)
   - check_in: Date
   - check_out: Date

----------------------------------------------------------------------------------------------------

4. Payments:

   - payment_id: Integer (Primary Key)
   - booking_id: Integer (Foreign Key)
   - amount  : Float
   - payment_date: Date

-------------------------------------------------------------------------------------------------------

## Future Enhancements

- Integration of a graphical user interface (GUI) using Tkinter or PyQt.
- Advanced reporting features.
- Cloud-based database support for scalability.
- Mobile application support.

----------------------------------------------------------------------------------------------------

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

----------------------------------------------------------------------------------------------------

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

-----------------------------------------------------------------------------------------

## Contact

AYUSH SHAH
Email: [[ayushs1904@gmail.com](mailto\:ayushs1904@gmail.com)]\
LinkedIn: ( https\://www\.linkedin.com/in/ayush-shah-937937265?utm\_source=share&utm\_campaign=share\_via&utm\_content=profile&utm\_medium=android\_app )

Feel free to reach out for any questions, suggestions, or collaboration opportunities!

---------------------------------------------------------------------------------------------------------------------------------------------------------------------
# THANKS , 
AYUSH SHAH 