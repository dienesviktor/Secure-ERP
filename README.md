# Secure-ERP

Python-based ERP system, using MVC pattern and modular design.

Enterprise resource planning (ERP) is the integrated management of main business processes, often in real time and mediated by software and technology.
ERP provides an integrated and continuously updated view of core business processes using common databases maintained by a database management system.

ERP systems track business resources—cash, raw materials, production capacity—and the status of business commitments: orders, purchase orders, and payroll.
The ERP system integrates varied organizational systems and facilitates error-free transactions and production, thereby enhancing the organization's efficiency.

### Modules and Operations

1. CRM module with basic and special operations.
    - Once the CRM module is selected, choosing option 1 asks the user to type the name, email, and subscription status for a new customer. When the last field is filled in, a new customer is introduced with an random ID.
    - Once the CRM module is selected, choosing option 2 prints all the customers.
    - Once the CRM module is selected, choosing option 3 asks the user for the ID of a customer. If the ID belongs to an existing customer, the user enters new values for the name, email, and subscription status. When the last field is filled in, the customer fields are updated with the given values.
    - Once the CRM module is selected, choosing option 4 asks the user for the ID of a customer. If the ID belongs to an existing customer, the customer is deleted from the database.
    - (5) Get the emails of subscribed customers.

2. Sales module with basic and special operations.
    - (1-4) Provide basic CRUD operations.
    - (5) Get the transaction that made the biggest revenue.
    - (6) Get the product that made the biggest revenue altogether.
    - (7) Count the number of transactions between two dates.
    - (8) Sum the price of transactions between two dates.

3. HR module with basic and special operations.
    - Provide basic CRUD operations.
    - (5) Return the names of the oldest and the youngest employees as a tuple.
    - (6) Return the average age of employees.
    - (7) Return the names of employees who have birthdays within two weeks from the input date.
    - (8) Return the number of employees who have at least the input clearance level.
    - (9) Return the number of employees per department in a dictionary (like `{'dep1': 5, 'dep2': 11}`).

### Instruction:

To start:
```
python ERP.py
```

To choose an option:
```
(1) Customer Relationship Management (CRM)
(2) Sales
(3) Human Resources
(0) Exit program
```
