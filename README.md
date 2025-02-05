Matrix Airline Reservation System-

Overview

The Matrix Airline Reservation System is a C-based console application that allows users to manage airline reservations, routes, and staffing. It provides functionalities for both customers and employees, enabling seamless booking, modification, and management of flights.

Features

Customer Features:

Book a flight – Customers can search available flights and book a seat.

Modify a reservation – Modify seat selection for existing reservations.

Cancel a reservation – Cancel an existing reservation and free up the seat.

Employee Features:

Add or delete a route – Modify available flight destinations.

Add or remove a plane – Update the airline's fleet information.

Manage staffing – Assign pilots to flights.

Data Structures

The system utilizes structured data types for better management of flight details:

ROUTE – Holds departure and destination information.

SEAT – Contains seat number, ticket number, and reservation status.

FLIGHT – Stores flight details including seat reservations, aircraft details, and assigned pilot.

How It Works

The program initializes 4 default flights with 50 seats each.

Users interact via a menu-driven system:

Customers can book, modify, or cancel their reservations.

Employees can add/remove routes, planes, and manage staffing.

The system maintains data for seat assignments and flight routes dynamically.

