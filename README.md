# Car Rental Management System (Java Swing)

## Overview
This is a desktop-based **Car Rental Management System** built using **Java Swing**. It allows an admin to manage cars and customers to book available cars. The application uses **local text files** (`cars.txt` and `bookings.txt`) to store data persistently.

### Admin Panel
- Add new cars with details: Model, Brand, Price per Day, and Availability.
- View all added cars in a table.
- Cars are saved to `cars.txt` for persistent storage.

### Customer Panel
- Book an available car.
- Enter customer name, select car, and number of rental days.
- Automatically calculates total price.
- Updates car availability after booking.
- Bookings are saved to `bookings.txt` for persistence.
- View all bookings in a table.

## Requirements
- **Java JDK 8** or higher
- Any IDE supporting Java Swing (Eclipse, IntelliJ IDEA, NetBeans)
- Basic knowledge of running Java applications

## How to Run
1. Clone or download this repository.
2. Compile the Java file:
   ```bash
   javac CarRentalManagement.java

**Screenshot**
**Admin Panel – Manage Cars**  
<img src="Screenshot/Screenshot (22).png" width="100" height="200">
<img src="Screenshot/Screenshot (25).png" width="100" height="200">

**Customer Panel – Book Car**  
<img src="Screenshot/Screenshot (23).png" width="100" height="200">
<img src="Screenshot/Screenshot (24).png" width="100" height="200">

**Usage**
-Admin can add cars using the top form in the Admin tab.
-Customer can book a car from the available list in the Customer tab.
-After booking, the car becomes unavailable and the booking is recorded.
-Both cars and bookings are stored in text files for persistence.

**Future Enhancements**
-Add Update/Delete Car functionality for Admin.
-Add search and filter options for cars and bookings.
-Include GUI improvements for better user experience.
-Use a database instead of text files for more robust data handling.

**Author**
Developed by Sharwari Ajay Rahangdale
Email: sharwarirahandale@gmail.com

