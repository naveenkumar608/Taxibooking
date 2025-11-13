# Car Rental System

## Description
This project is a simple Car Rental System implemented in Java. It allows users to rent and return cars, manage customer information, and calculate rental prices based on the number of rental days.

## Features
- **Rent a Car:** Users can view available cars and rent one by providing their name and the number of rental days.
- **Return a Car:** Users can return a rented car and receive confirmation.
- **Car Management:** Admin can add cars to the system with details such as brand, model, and rental price.
- **Customer Management:** The system automatically generates customer IDs for new customers.

## Technologies Used
- Java 8 or higher
- Standard Java libraries (`java.util`)

## Classes
1. **Car**
   - Represents a car with properties such as ID, brand, model, base price per day, and availability status.
   - Methods include:
     - `calculatePrice(int rentalDays)`: Calculates the total rental price.
     - `rent()`: Marks the car as rented.
     - `returnCar()`: Marks the car as available.

2. **Customer**
   - Represents a customer with a unique ID and name.

3. **Rental**
   - Represents a rental transaction that links a car to a customer and tracks the number of rental days.

4. **CarRentalSystem**
   - Manages cars, customers, and rentals.
   - Provides a menu-driven interface for users to interact with the system.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/naveentk10/TaxiGit.git
