# Grocery Store Management System

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Database Structure](#database-structure)

## Project Overview

The **Grocery Store Management System** is a Java-based desktop application designed to assist grocery shopkeepers in managing day-to-day store operations, such as inventory management, sales tracking, and purchases. The system is built using Java Swing for the front end and connects to a MySQL database for storing and retrieving data. It streamlines the process of managing grocery stock, updating purchases, and processing sales, making it more efficient and accurate for store owners.

## Features

- **Inventory Management**: Add, update, and delete grocery items from the system.
- **Sales Module**: Process sales and track daily, weekly, and monthly sales data.
- **Purchases Module**: Record and track purchases made to restock the inventory.
- **Search Functionality**: Quickly search for items by name or category.
- **Database Connectivity**: Persistent data storage with MySQL, ensuring reliable data handling and retrieval.

## Technologies Used

- **Frontend**: Java Swing for building the graphical user interface.
- **Backend**: Java for business logic and application functions.
- **Database**: MySQL for data storage and retrieval.
- **Development Environment**: NetBeans IDE for building and managing the project.

## Database Structure

The application uses a MySQL database with the following tables:

- **Items Table**: Stores information about grocery items (item ID, name, category, price, quantity).
- **Sales Table**: Stores data about sales transactions (sale ID, date, item ID, quantity sold, total amount).
- **Purchases Table**: Stores data about purchases made to restock inventory (purchase ID, date, item ID, quantity purchased, supplier).

The tables are connected using foreign keys, where `item_id` in the **Sales** and **Purchases** tables refers to the `item_id` in the **Items** table.

