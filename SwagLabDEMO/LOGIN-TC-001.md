## TC-001 – Verify Login with Valid Credentials

*Test Scenario:*
Verify that a registered user can log in successfully.

*Precondition:*
User is on the SauceDemo login page.

*Test Data:*
Username: `standard_user`
Password: `secret_sauce`

*Test Steps:*

1. Open the SauceDemo website.
2. Enter `standard_user` in the Username field.
3. Enter `secret_sauce` in the Password field.
4. Click the **Login** button.

*Expected Result:*
The user should be successfully logged in and redirected to the Products page.

*Actual Result:*
The user was successfully logged in and the Products page was displayed.

*Status:* PASS


# TC-002 – Verify Login with Invalid Password
*Test Scenario:*
Verify that the user cannot log in with an incorrect password.

*Precondition:*
User is on the SauceDemo login page.

**Test Data:**
Username: `standard_user`
Password: `wrongpassword`

*Test Steps:*

1. Open the SauceDemo website.
2. Enter `standard_user` in the Username field.
3. Enter `wrongpassword` in the Password field.
4. Click the **Login** button.

*Expected Result:*
An error message should be displayed and the user should remain on the login page
Error message: Username and password do not match any user in this service

*Actual Result:*
An error message was displayed and the user remained on the login page.
Error message: Username and password do not match any user in this service

*Status:* PASS
