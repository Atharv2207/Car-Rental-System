# Car Rental System

## Use Cases

### Customer, Employee

- **View Cars:** Users can view the details of all the cars present in the store.
- **View Records:** Users can view their personal details and records, including:
  - The cars they have rented
  - Customer/Employee record value
  - Maximum number of cars rentable at a time
  - Due Fine
- **Rent a Car:** Users can rent available cars.

### Manager

- **Add and Delete Records:** Manager can add and delete customer, employee, and car records.
- **Update Details:** Manager can update details of customers and employees, such as name and password. Manager is responsible for changing the due fine and record value on a customer/employee’s profile whenever they return a car.
- **View and Update Car Details:** Manager can view and update all the details of any car in the database.

## Assumptions and Usage Guide

- Manager’s code: 148235
- IDs for Customers, Employees, Cars are the same as their index.
- Initial record value for new accounts is 10 for customers and 15 for employees.
- Return Car is done by the manager to note the conditions of the car.
- Password for customer/employee ‘i’ is passwordi (e.g., password0 for the customer/employee at index 0).
- The parameter `fine_due` stores the sum of all the fines as well as the amount payable (i.e., rent).
- Initial database is of 10 employees, 10 customers, 10 cars, 1 manager.
- Initially rented cars in the database:
  - Customer6 => Car with ID = 6
  - Customer8 => Car with ID = 8
  - Employee1 => Car with ID = 1
  - Employee3 => Car with ID = 3
- Customers6 and Employee1 cannot rent any more cars according to their initial record value.
- Today’s date is assumed to be 04/03/2024 for renting cars.
