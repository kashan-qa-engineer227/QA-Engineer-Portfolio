Login Module — Manual Test Cases

Project Information

- Website: https://practicesoftwaretesting.com/
- Module: Login
- Testing Type: Manual Testing
- Test Cases Executed: 5
- Execution Result: 5 Passed, 0 Failed

Test Cases

TC_LOGIN_001 — Login with Valid Credentials

- Objective: Verify that a user can log in using valid credentials.
- Test Steps:
  1. Open the login page.
  2. Enter a valid email address.
  3. Enter the correct password.
  4. Click the Login button.
- Expected Result: User should successfully log in.
- Actual Result: User successfully logged in.
- Status: PASS

TC_LOGIN_002 — Login with Invalid Password

- Objective: Verify that login is rejected when an incorrect password is entered.
- Test Steps:
  1. Open the login page.
  2. Enter a valid email address.
  3. Enter an incorrect password.
  4. Click the Login button.
- Expected Result: An appropriate invalid credentials error should appear.
- Actual Result: "Invalid email or password" message appeared.
- Status: PASS

TC_LOGIN_003 — Login with Both Fields Empty

- Objective: Verify required-field validation.
- Test Steps:
  1. Open the login page.
  2. Leave the email field empty.
  3. Leave the password field empty.
  4. Click the Login button.
- Expected Result: Required-field validation messages should appear.
- Actual Result: "Email is required" and "Password is required" messages appeared.
- Status: PASS

TC_LOGIN_004 — Login with Invalid Email Format

- Objective: Verify email format validation.
- Test Steps:
  1. Open the login page.
  2. Enter an invalid email format (abc123).
  3. Enter a password.
  4. Click the Login button.
- Expected Result: An email format validation message should appear.
- Actual Result: "Email format is invalid" message appeared.
- Status: PASS

TC_LOGIN_005 — Login with Empty Email

- Objective: Verify that login is rejected when the email field is empty.
- Test Steps:
  1. Open the login page.
  2. Leave the email field empty.
  3. Enter a password.
  4. Click the Login button.
- Expected Result: An email-required validation message should appear.
- Actual Result: "Email is Required" message appeared.
- Status: PASS

Test Execution Summary

Metric| Result
Total Test Cases| 5
Passed| 5
Failed| 0
Blocked| 0
Pass Rate| 100%

Conclusion

All five executed login test cases passed based on the observed application behavior. Required-field validation, invalid email format validation, invalid credentials handling, and successful login were tested.
