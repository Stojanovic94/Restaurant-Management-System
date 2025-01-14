# Restaurant Management System - Use Case & Class Diagrams

This repository contains the solution for designing a software system to manage a restaurant. The system provides functionalities for waiters to input orders, manage tables, handle the menu, and generate bills. Administrators can manage staff, assign shifts, bonuses, reduce salaries for violations, and hire/fire employees.

## Overview

The system is designed to streamline restaurant operations and improve efficiency. It offers key features for waiters, administrators, chefs, and customers, enabling them to interact with the system for various restaurant tasks.

The design consists of:
1. **Use Case Diagram** - Illustrates how users interact with the system and the system's functionalities.
2. **Class Diagram** - Represents the structure of the system, showing classes, their attributes, methods, and relationships.

## Features

### 1. **Waiters**:
- **Input Orders**: Waiters can select menu items, assign available tables, and submit customer orders.
- **Manage Tables**: Waiters can assign customers to tables based on availability.
- **Generate Bills**: Waiters can generate bills based on the customer’s order, calculating the total amount.

### 2. **Administrators**:
- **Manage Menu**: Admins can add, update, or remove items from the menu.
- **Manage Staff**: Admins can hire or fire employees, assign work shifts, and manage salary bonuses or reductions.

### 3. **Chefs**:
- **Receive Orders**: Chefs can view the orders placed by waiters and begin preparing the meals.
- **Mark Food as Ready**: Once the food is ready, the chef can mark it as prepared for delivery.

### 4. **Customers**:
- **View Menu**: Customers can browse available menu items.
- **Place Orders**: Customers can place orders through interaction with the waiter.

## Diagrams

### 1. Use Case Diagram

The Use Case Diagram shows the functionalities of the system and how different users (actors) interact with it. Key actors include:

- **Waiter**
- **Administrator**
- **Chef**
- **Customer**

The diagram visually represents actions like entering orders, managing tables, generating bills, managing the menu, and managing employees.

### 2. Class Diagram

The Class Diagram represents the structure of the system, detailing the various classes, their attributes, methods, and relationships. The main classes involved are:

- **Order**
- **Table**
- **Menu**
- **Bill**
- **Employee (Waiter, Chef, Administrator)**
- **Customer**
