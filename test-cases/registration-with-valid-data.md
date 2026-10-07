# TC-REG-001 — Register a New User with Valid Data

| Field | Value |
| --- | --- |
| Priority | Critical |
| Type | Positive / Functional |
| Module | Registration |
| Preconditions | The user is not logged in and the registration form is available. |

## Test data

- Username: a new, unique test username
- Password: a valid password containing at least 8 characters, one letter, and one digit

## Steps and expected results

| Step | Action | Expected result |
| --- | --- | --- |
| 1 | Open the registration form. | Username, password, and registration controls are displayed. |
| 2 | Enter a unique valid username. | The username is accepted without a validation error. |
| 3 | Enter a valid password. | The password is accepted without a validation error. |
| 4 | Submit the registration form. | A new account is created and the user becomes authorized. |
| 5 | Check the header controls. | The Logout control is available instead of Login. |

> This is a sanitized portfolio example. It contains no real account credentials or private application URL.
