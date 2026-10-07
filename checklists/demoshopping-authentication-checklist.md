# Authentication Checklist — Training E-commerce Application

**Type:** Test design artifact  
**Scope:** Registration, login, logout, and authorization  
**Execution status:** Not executed in this published version

## Registration

| ID | Check |
| --- | --- |
| REG-001 | Registration form contains a username field, password field, and registration action. |
| REG-002 | A new user can register with valid data. |
| REG-003 | A username shorter than 3 characters is rejected. |
| REG-004 | A username containing exactly 3 characters is accepted. |
| REG-005 | A username containing exactly 15 characters is accepted. |
| REG-006 | A username containing 16 characters is rejected. |
| REG-007 | Letters, digits, and underscore are accepted in a username. |
| REG-008 | A forbidden special character in a username is rejected. |
| REG-009 | An empty username is rejected. |
| REG-010 | A password shorter than 8 characters is rejected. |
| REG-011 | An 8-character password containing a letter and a digit is accepted. |
| REG-012 | A password without digits is rejected. |
| REG-013 | A password without letters is rejected. |
| REG-014 | An empty password is rejected. |
| REG-015 | Registration with an existing username is rejected. |
| REG-016 | Validation messages explain the username and password rules. |
| REG-017 | The Login control is replaced by Logout after successful registration. |

## Login

| ID | Check |
| --- | --- |
| LOGIN-001 | Login form contains username, password, and login action. |
| LOGIN-002 | A registered user can log in with valid credentials. |
| LOGIN-003 | A successful login redirects the user to the homepage. |
| LOGIN-004 | Invalid login data displays a validation error. |
| LOGIN-005 | An incorrect username or password displays an informative error. |
| LOGIN-006 | Empty username and password values are rejected. |

## Logout and authorization

| ID | Check |
| --- | --- |
| LOGOUT-001 | Clicking Logout ends the authorized session. |
| LOGOUT-002 | After logout, the unauthorized UI is displayed. |
| AUTH-001 | An unauthorized user cannot open Cart. |
| AUTH-002 | An unauthorized user cannot open Payment. |
| AUTH-003 | An unauthorized user cannot open Order History. |
| AUTH-004 | The authorization-required message contains a login link. |
| AUTH-005 | The login link opens the login page. |
| AUTH-006 | An authorized user can open all protected pages. |

## Techniques used

- Positive and negative testing
- Boundary value analysis
- Validation testing
- Access-control testing
- UI and navigation testing
