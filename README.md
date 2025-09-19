# Cab Booking System (Suhani Cab Services)

A console-based cab booking application built in Java that provides a complete taxi service management system with separate interfaces for drivers, customers, and administrators.

## Features

### 🚗 Multi-User Interface
- **Driver Portal**: Manage driver profiles, view bookings, and update availability
- **Customer Portal**: Book rides, view ride history, and manage customer profile
- **Administration Portal**: Oversee operations, manage users, and system administration

### 🎯 Core Functionality
- Real-time cab booking system
- Driver and customer management
- Ride history tracking
- User authentication and profiles
- Administrative controls and oversight

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Command line interface (Terminal/Command Prompt)

## Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Suhani1234-5/Cab-Book.git
   cd Cab-Book
   ```

2. **Compile the Java files**
   ```bash
   javac -cp bin *.java -d bin/
   ```
   
   Or if source files are in src directory:
   ```bash
   javac -cp . src/*.java -d bin/
   ```

3. **Run the application**
   ```bash
   java -cp bin Main
   ```

## Usage

Upon launching the application, you'll see the main menu:

```
Welcome to Suhani Cab Services
Main Menu:
1. Driver
2. Customer  
3. Administration
4. Exit
```

### Driver Interface
- Register as a new driver or login with existing credentials
- Update availability status
- View assigned bookings
- Manage driver profile information

### Customer Interface
- Register as a new customer or login
- Search and book available cabs
- View booking history
- Update customer profile

### Administration Interface
- System administrator login
- Manage drivers and customers
- View system statistics
- Handle administrative tasks

## Project Structure

```
Cab-Book/
├── src/
│   ├── Main.java          # Main application entry point
│   ├── Driver.java        # Driver class and functionality
│   ├── Customer.java      # Customer class and functionality
│   ├── Admin.java         # Administration functionality
│   └── [Other Java files]
├── bin/                   # Compiled class files
└── README.md
```

## Technology Stack

- **Language**: Java
- **Architecture**: Console-based application
- **Design Pattern**: Object-Oriented Programming (OOP)


## Key Components

### Classes Overview
- `Main.java`: Entry point with main menu navigation
- `Driver.java`: Driver management and operations
- `Customer.java`: Customer booking and profile management
- `Admin.java`: Administrative functions and system management




## Contact

**Developer**: Suhani  
**GitHub**: [@Suhani1234-5](https://github.com/Suhani1234-5)  
**Project Link**: [https://github.com/Suhani1234-5/Cab-Book](https://github.com/Suhani1234-5/Cab-Book)

## Acknowledgments

- Built as a learning project to demonstrate OOP concepts in Java

---

⭐ If you find this project helpful, please consider giving it a star on GitHub!
