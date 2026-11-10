# Login Page - Manual Test Cases

## Project Objective
To test the login functionality of a sample application.

## Test Cases

| Test ID | Test Scenario              | Test Data                   | Expected Result |
| TC001 | Login with valid credentials | Valid username and password | User should log in successfully |
| TC002 | Login with invalid password | Valid username, wrong password | Error message should appear |
| TC003 | Login with invalid username | Wrong username, valid password | Error message should appear |
| TC004 | Login with empty fields | Blank username and password | Validation message should appear |
| TC005 | Login with empty password | Valid username, blank password | Password required message should appear |
| TC006 | Login with empty username | Blank username, valid password | Username required message should appear |

### TC001 – Valid Login
- Enter a valid username.
- Enter a valid password.
- Click Login.
- Expected Result: User should log in successfully.

### TC002 – Invalid Password
- Enter a valid username.
- Enter an incorrect password.
- Click Login.
- Expected Result: An appropriate error message should appear.

### TC003 – Empty Username
- Leave the username field empty.
- Enter a valid password.
- Click Login.
- Expected Result: Username validation message should appear.

### TC004 – Empty Password
- Enter a valid username.
- Leave the password field empty.
- Click Login.
- Expected Result: Password validation message should appear.

### TC005 – Both Fields Empty
- Leave both fields empty.
- Click Login.
- Expected Result: Required field validation should appear.
## Conclusion
Basic positive and negative login scenarios have been identified.

### TC006 – Invalid Email Format
- Enter an invalid email address (example: malar@gmail).
- Enter a valid password.
- Click Login.
- Expected Result: Appropriate email validation message should appear.

### TC007 – Password Masking
- Open the login page.
- Enter a password.
- Observe the password field.
- Expected Result: Password characters should be hidden using dots or asterisks.
