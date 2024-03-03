# CS253_C-_Assignment
Use Cases:
Customer, Employee
View cars: They can view the details of all the cars present in the store.
View Records: They can view their personal details and records like:
The cars they have rented
Customer/Employee record value
Maximum number of cars rentable at a time
Due Fine
Rent a Car: They can rent the available cars.
    2) Manager
Add and Delete customer, employee, car records.
Update details of customers and employees, like name and password. Manager is the one to change the due fine and record value on a customer/employee’s profile whenever they return a car.
View and update all the details of any car in the database.

Assumptions and guide to use the code:
Manager’s code: 148235
Customers, Employees, Cars have ID’s same as their index.
Initial record value for any new account is 10 for customers and 15 for employees.
Return Car is not done by users but by manager as he/she has to note the conditions of the car.
Password for customer/employee ‘i’ is passwordi, example password0 for customer/employee at index 0.
The parameter fine_due stores the sum of all the fines as well as the amount payable, i.e. rent.
Initial database is of 10 employees, 10 customers, 10 cars, 1 manager.
Initially rented cars in the database:
Customer6 => Car with ID = 6
Customer8 => Car with ID = 8
Employee1 => Car with ID = 1
Employee3 => Car with ID = 3
Customer6 and Employee1 cannot rent any more cars according to their initial record value.
Today’s date is assumed to be 04/03/2024 for renting cars.
