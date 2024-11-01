# Inventory Management System for Drone Club

This project implements a robust **Inventory Management System** designed for managing and optimizing the inventory of a drone club. The application is built in Python and provides a user-friendly interface for tracking essential items and equipment used in drone operations.

## Key Features

- **Add New Items**: 
  - Input essential details for each item, including:
    - **Item ID**: Unique identifier for each item.
    - **Item Name**: Descriptive name of the item.
    - **Category**: Classification of the item (e.g., batteries, tools, drones).
    - **Quantity**: The number of items available in stock.
    - **Condition**: Current state of the item (e.g., new, used, needs repair).
    - **Location**: Physical storage location of the item.
    - **Date Acquired**: Date when the item was added to the inventory.
    - **Last Used Date**: Most recent date the item was utilized.
    - **Assigned To**: The individual responsible for the item.
    - **Usage Purpose**: Description of how the item is used within the club.
    - **Pricing**: Cost of the item for budgeting purposes.

- **View Inventory**: 
  - Display a comprehensive list of all items in the inventory, including detailed information for each entry. This allows club members to quickly assess available resources.

- **View Individual Item**: 
  - Retrieve and display detailed information about a specific item by entering its unique ID. This feature is useful for tracking specific items and understanding their status and usage.

## Technical Specifications

- **Language**: Python
- **Date and Time Handling**: Utilizes Python's `datetime` module for accurate date management, enabling users to track acquisition and usage dates effectively.
- **Data Structure**: 
  - Uses a dictionary to store inventory data, allowing for quick lookups and efficient data management.
  - Each item is stored as a nested dictionary under its unique Item ID, ensuring easy access to all associated attributes.

- **User Interaction**: 
  - Command-line interface (CLI) for user input and navigation, providing an intuitive experience for managing inventory operations.
  - Menu-driven structure allows users to select actions easily, making the system accessible for all users, regardless of technical expertise.

## Purpose and Benefits

The primary goal of this inventory management system is to enhance the organizational capabilities of the drone club. By maintaining accurate records of all equipment and supplies, club members can:

- **Optimize Resource Utilization**: Identify available items and prevent over-purchasing or waste of resources.
- **Improve Accountability**: Track who is using what equipment, aiding in responsibility and care for club assets.
- **Facilitate Planning and Budgeting**: Keep accurate records of item pricing and usage to better plan future purchases and budget allocations.

## Usage Instructions

1. Clone or download this repository to your local machine.
2. Ensure you have Python installed (Python 3.x recommended).
3. Run the `inventory_management.py` file in your preferred Python environment.
4. Follow the on-screen menu to add items, view the inventory, or retrieve individual item details.
