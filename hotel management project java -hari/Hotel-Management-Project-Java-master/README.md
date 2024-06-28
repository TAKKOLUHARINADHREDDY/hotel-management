# Hotel Booking System

This Java application provides a simple hotel booking system with functionalities for booking rooms, ordering food, checking room availability, and generating bills. It supports both single and double rooms with different levels of luxury.

Features
Display Room Details: View details of different room types.
Display Room Availability: Check the availability of rooms.
Book a Room: Book a luxury or deluxe room, either single or double.
Order Food: Order food to the booked room.
Checkout: Generate a bill and checkout from the room.
Persistence: Save and load the hotel state using serialization.
Room Types
Luxury Double Room
Deluxe Double Room
Luxury Single Room
Deluxe Single Room
Menu
Sandwich: Rs. 50
Pasta: Rs. 60
Noodles: Rs. 70
Coke: Rs. 30
Getting Started
Prerequisites
Java Development Kit (JDK) 8 or above


Code Structure
Food: Represents food items ordered by customers.
Singleroom: Represents a single room.
Doubleroom: Represents a double room.
NotAvailable: Custom exception for handling room unavailability.
Holder: Holds the hotel room objects.
Hotel: Contains static methods for hotel operations like booking, deallocating, ordering food, and generating bills.
Write: Implements Runnable for writing the hotel state to a file.
Main: Entry point of the application, containing the main menu and user interaction logic.


