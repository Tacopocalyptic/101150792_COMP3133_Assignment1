# COMP3133 - Assignment 1
### Josephine Snyder - 101150792
---


This is a GraphQL backend is built in Node.js.
Endpoints include:
- User Sign-up
- User Login
- Add Employee
- Update Employee (by ID)
- Delete Employee (by ID)
- Get all Employees
- Search employee by ID
- Search Employee by designation or department

To run, first navigate to the GraphQL folder and run `npm install`.
With Docker Desktop running and from the root folder of this repository, Run the command located in the docker-compose.yml file to launch a database with appropriate setup.

Current features: Validation for all fields in the User and Employee models is in place, so that data is consistent and appropriate. Password encryption is applied before saving user passwords to the database. User login returns a JWT with an expiry of 30 minutes

Planned implementation: Use of the JWT for validation before accessing any potentially sensitive employee information. Refined error returns for failed validation (currently feels very simplistic)

---
Note: Data samples have been removed from this repository to save space and time with downloads/uploads. You will have to supply data.
