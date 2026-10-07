# DemoShopping Checklist — Test Design

This checklist covers the registration, login, logout, and authorization flows of a training e-commerce application.

It is a **test-design artifact**. The original checklist currently contains `Not Run` statuses, so this repository does not present it as completed test execution.

## Coverage

| Area | Example coverage |
| --- | --- |
| Registration | Valid registration, required fields, duplicate username, allowed characters, password rules |
| Login | Valid credentials, invalid credentials, validation messages, empty fields |
| Logout | Session termination and return to unauthorized state |
| Authorization | Access restrictions for Cart, Payment, and Order History |

## Test Design Techniques Used

- Positive and negative testing
- Boundary value analysis
- Input validation
- Access-control testing
- UI and navigation testing

The cleaned spreadsheet export will be stored in this folder after its test data has been checked.
