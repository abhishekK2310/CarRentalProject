Car Rental System 🚗
This is a simple but complete command-line based Car Rental System built using Java. The project demonstrates core Object-Oriented Programming (OOP) principles to create a functional and easy-to-use application for managing car rentals. It allows users to view available cars, rent a car for a specified number of days, and return a car.

Features
Rent a Car: Users can select from a list of available cars and rent one for a specified number of days.

Return a Car: Marks a rented car as available again for the next customer.

View Available Cars: The menu displays a real-time list of all cars currently available for rent.

Price Calculation: The total rental cost is automatically calculated and displayed to the user before they confirm the rental.

Simple Menu Interface: An interactive and easy-to-use console menu guides the user through the rental process.

Technologies Used
Language: Java

Core Concepts: Object-Oriented Programming (OOP), Data Structures (ArrayList)

Getting Started
Follow these instructions to get the project running on your local machine.

Prerequisites
Make sure you have a Java Development Kit (JDK) installed on your system.

How to Run
Compile the Code:
Open your terminal or command prompt, navigate to the directory where you saved the Main.java file, and compile it using the following command:

Bash

javac Main.java
Run the Program:
After the code compiles successfully, run the program using the following command:

Bash

java Main
Interact with the System:
The car rental system menu will now appear in your terminal. Follow the on-screen prompts to rent or return a car.

Code Overview
The project is structured into several classes, each with a specific responsibility:

Car: Represents a car with attributes like carId, brand, model, basePricePerDay, and its availability status.

Customer: Represents a customer with a unique customerId and name.

Rental: Links a Car with a Customer and stores the rental duration in days.

CarRentalSystem: This is the main engine of the application. It manages the lists of cars, customers, and active rentals, and contains the core logic for renting and returning cars.

Main: The entry point of the application. It initializes the CarRentalSystem, adds some sample cars to the inventory, and starts the user menu.

Example Usage
Here is a sample interaction with the running application:

===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==

Enter your name: John Doe

Available Cars:
C001 - Toyota Camry
C002 - Honda Accord
C003 - Mahindra Thar

Enter the car ID you want to rent: C001
Enter the number of days for rental: 5

== Rental Information ==

Customer ID: CUS1
Customer Name: John Doe
Car: Toyota Camry
Rental Days: 5
Total Price: $300.00

Confirm rental (Y/N): Y

Car rented successfully.

===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 2

== Return a Car ==

Enter the car ID you want to return: C001
Car returned successfully by John Doe
