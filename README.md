# Programming-Fundamental-Project
# Blood Donor Management System (C++)
A console based management system developed in C++ to organize and maintain blood donor records efficiently. This application is designed for small-scale blood banks, clinics, or academic projects where quick access to donor information is essential.
It provides a structured way to store, retrieve, and manage donor data with validation and user-friendly interaction.

### Key Highlights:
#### Add Donor Records
Register new donors with complete details including personal info, blood group, and donation history.
#### Organized Data Display
View all donor records in a well-formatted tabular layout for easy readability.
#### Advanced Search Options
Quickly find donors using:
Blood Group
Donor ID
City
#### Update Information
Modify specific donor details such as:
Contact Number
Last Donation Date
#### Delete Records
Remove donor entries when no longer needed.
#### Automatic ID Assignment
Each donor is assigned a unique ID automatically.
### How It Works:
Uses a struct donor to store donor information.
Maintains records using a fixed-size array (capacity: 20 donors).
Implements a menu-driven interface for smooth navigation.
Includes input validation for:
Age eligibility
Unique contact numbers
Required fields
### Concepts Used:
Structures (struct)
Arrays
Functions
Input validation
Loops & conditionals
Formatted output (iomanip)
