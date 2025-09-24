# Hotel Reservation System

## Description
A console-based hotel management application designed to help hotel owners efficiently manage room bookings and customer records, while providing customers with an easy way to order food. This system features separate login portals for owners and customers, enabling secure access to relevant functionalities.

## Features
- **Owner Login:**
  - Access a main menu to book rooms, view customer records, show allocated rooms, and edit or delete records.
  - Manage room types and their associated charges.
  
- **Customer Login:**
  - Login securely using username and password.
  - Order food from a categorized menu (Desi, Fast Food, Chinese).
  - View food charges and complete payment.

- **Room Booking:**
  - Book single, double, and AC double rooms with dynamic pricing.
  - Prevent double booking by checking room availability.

- **Record Management:**
  - View detailed customer booking records.
  - Modify or delete customer records by room number.
  - All records are stored persistently in binary files.

## Technologies Used
- C++ programming language
- File handling for persistent storage
- Console-based user interface

## How to Use
1. Compile the program using a C++ compiler (e.g., visual studio ,  Dev C++).
2. Run the executable.
3. Choose whether you are an owner or customer.
4. For owners, enter the admin credentials (username: `admin`, password: `123`) to access management features.
5. For customers, login with your username and password to order food.
6. Follow on-screen instructions to navigate the system.

## File Structure
- `Record.txt` — Stores all customer booking records in binary format.
- `users.txt` — Stores registered user credentials for login.
- `temp.txt` — Temporary file used for editing or deleting records.

## Future Enhancements
- Add GUI support for better user experience.
- Implement password encryption for user security.
- Expand food menu and integrate payment gateway.

## Author
Muneeb Ali
---
Thank you 
