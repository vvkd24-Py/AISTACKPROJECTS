## Test Plan
The test plan for 'Login Functionality' ensures that we are able to validate if the user entering their correct login credentials (email and password) is redirected correctly to the Dashboard And the system displays relevant error message if the entered login credentials are incorrect.

**Objectives**
- Verify that the system asks for user's Email and Password for logging in.
- Confirm that the system verifies the entered credentials and only logs in the user when the credentials are correct.
- Verify that the user is redirected to the Dashboard page after a successful login.
- Confirm that the system displays an error message when incorrect credentials are entered.

**Scope**
This plan covers the login functionality and its behavior in response to correct and incorrect login credentials.

**Responsibilities**
- Test Engineers: Prepare test cases and execute them.
- Developers: Fix any issues identified.
- Project Manager: Track progress and ensure timelines are met.

## User Scenarios
**Scenario 1: Successful Login**
1. User navigates to the login page.
2. User enters their valid email and password.
3. User clicks 'Log In'.
4. System verifies the credentials are correct.
5. System redirects the user to the Dashboard.

**Scenario 2: Unsuccessful Login**
1. User navigates to the login page.
2. User enters an invalid email and password.
3. User clicks 'Log In'.
4. System verifies the credentials are incorrect.
5. System displays an error message to the user.

## Test Data
**Data for Successful Login**
- Email: testuser@mail.com
- Password: Test@123

**Data for Unsuccessful Login**
- Email: nonexistinguser@mail.com
- Password: somepassword
