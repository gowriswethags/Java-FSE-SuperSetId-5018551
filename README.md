
# WEEK 1

## Overview

This repository contains multiple Java projects designed to demonstrate different aspects of programming, including inventory management, search algorithms, sorting, employee management, and task management systems. The projects also explore recursive algorithms for financial forecasting in week 1.

## Projects Included

1. **Inventory Management System**
   - **Description**: Manages product inventory with functionalities to add, update, delete, display, and sort products.
   - **Key Classes**:
     - `Product`: Represents individual products.
     - `Inventory`: Manages a collection of products, supporting CRUD operations and sorting.
   - **Algorithms**: Bubble Sort and Quick Sort for product sorting.

2. **E-commerce Platform Search Function**
   - **Description**: Implements search functionality for an e-commerce platform using linear and binary search algorithms.
   - **Key Classes**:
     - `Book`: Represents book information with attributes like `bookId`, `title`, and `author`.
     - `BookSearchSystem`: Handles search operations (linear and binary search) and user interaction.
   - **Algorithms**: Linear Search and Binary Search for finding books.

3. **Order Sorting System**
   - **Description**: Manages customer orders and sorts them by total price using Bubble Sort and Quick Sort algorithms.
   - **Key Classes**:
     - `Order`: Represents individual orders with attributes like `orderId`, `customerName`, and `totalPrice`.
     - `OrderManagementSystem`: Handles order management and sorting operations.
   - **Algorithms**: Bubble Sort and Quick Sort for sorting orders by price.

4. **Employee Management System**
   - **Description**: Manages employee records with functionalities to add, search, traverse, and delete employees.
   - **Key Classes**:
     - `Employee`: Represents employee information with attributes like `employeeId`, `name`, `position`, and `salary`.
     - `EmployeeManagementSystem`: Handles employee record management and operations.
   - **Data Structure**: Array for storing employee records.

5. **Task Management System**
   - **Description**: Manages tasks using a singly linked list with functionalities to add, search, traverse, and delete tasks.
   - **Key Classes**:
     - `Task`: Represents individual tasks with attributes like `taskId`, `taskName`, and `status`.
     - `TaskLinkedList`: Implements a singly linked list for managing tasks.
   - **Data Structure**: Singly Linked List for dynamic task management.

6. **Financial Forecasting Tool**
   - **Description**: Predicts future values based on past data using a recursive approach to calculate future value.
   - **Key Classes**:
     - `FinancialForecastingTool`: Provides methods for calculating future values using recursion and iterative approaches.
   - **Algorithm**: Recursive algorithm for future value calculation.

## Running the Projects

1. **Compile the Java Files**: Use the following command to compile the Java files:
   ```bash
   javac *.java
   ```

2. **Run the Main Class**: Execute the main class for each project using the following command:
   ```bash
   java MainClassName
   ```
   Replace `MainClassName` with the appropriate main class for the project you want to run (e.g., `Inventory`, `BookSearchSystem`, `OrderManagementSystem`, `EmployeeManagementSystem`, `TaskManagementSystem`, `FinancialForecastingTool`).

## Instructions

- Ensure you have the Java Development Kit (JDK) installed on your system.
- Extract the ZIP file and navigate to the project directory.
- Follow the compilation and execution steps provided above.

## Analysis and Results

**Inventory Management System**: Compares sorting algorithms and discusses performance.
**Search Algorithms**: Analyzes linear and binary search algorithms.
**Order Sorting System**: Compares sorting algorithms for performance.
**Employee Management System**: Discusses array usage and performance.
**Task Management System**: Explains linked lists and their advantages over arrays.
**Financial Forecasting Tool**: Analyzes recursion and optimization strategies.
