# Bookstore-Application

**Note**: Source Code not included to preserve academic integrity.

## Overview

This project is a GUI-based bookstore management application system developed using **JavaFX**.
This application was developed as part of a group assignment at Toronto Metropolitan University.
The application simulates an online bookstore environment with two user roles - **Owner** and **Customer**
and emphasizes good design practices, including the use of the **UML modeling and State Design Patterns**.

## Objectives

- Apply object oriented design principles to a real world prroblem.
- Use **JavaFX** to build a single-window GUI experience.
- Implement the **State Design Pattern** to manage customer status (Silver/Gold).

## Features

### Customer Functions

- Login using customer username and password
- View books that are available
- Customers have a choice of purchasing books with money or points
- Customers earn 10 points for every dollar spent
- Status is automatically updated: 
  - **Silver**: < 1000 points
  - **Gold**: ≥ 1000 points
- Redeem points: Every 100 points used = $1

### Owner Functions
- Login using owner username and password
- View, add or delete books
- Register or remove customers into the system
- Save all changes to 'books.txt' and 'customers.txt' on exit


## Tools and Technologies

- **Coding Language**: Java
- **IDE**: Netbeans
- **GUI**: JavaFX
- **UML Modeling**: Visual Paradigm

## My Role

- File Handling:
  - Implemented logic for reading/writing 'books.txt' and 'customers.txt'
  - Handled serialization and formatting of book/customer data
  - Ensured proper data persistence on application statup and exit
 
- Modeling & Documentation:
  - Created **Use Case Diagrams** using Visual Paradigm
  - Identified and marked State Design Pattern components in UML
  - Wrote and formatted the final **project rerport**, included the explaination for the use case diagram and        design rationale
 
## Disclaimer

This project was completed as part of a university course and is subject to academic integrity rules. Code has been withheld to prevent misuse. This repository is intended for demonstration and portfolio purposes only.



