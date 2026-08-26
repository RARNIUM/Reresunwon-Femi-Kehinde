## TC-011 – Verify if valid information is stored

*Test Scenario:*
Verify that a registered user can see their information in overview.

*Precondition:*
User is on the CheckOut: Your Information page.

*Test Data:*
1. First name :JAMES
2. Last name : BOND
3. Postal Code : 007

*Test Steps:*

1. Open the SauceDemo website.
2. Click ON THE CHECKOUT BUTTON.
3. Input the Test DATA in the required fields

*Expected Result:*
The user should be taken to the "Checkout: Overview" page to view product and shipping information .

*Actual Result:*
The user is taken to the "Checkout: Overview" page to view product and shipping information  .

*Status:* PASS

## TC-012 – Verify if an error message is displayed when First Name is empty

*Test Scenario:*
Verify that a registered user can see an error message displayed when First Name is empty.

*Precondition:*
User is on the CheckOut: Your Information page.

*Test Data:*
1. First name : 
2. Last name : BOND
3. Postal Code : 007

*Test Steps:*

1. Open the SauceDemo website.
2. Click ON THE CHECKOUT BUTTON.
3. Input the Test DATA in the required fields and leave the first name field empty 

*Expected Result:*
The user should see an error message is displayed when Last Name is empty .

*Actual Result:*
The user sees an error message is displayed when Last Name is empty .

*Status:* PASS

## TC-013 – Verify if an error message is displayed when Last Name is empty

*Test Scenario:*
Verify that a registered user can see an error message is displayed when Last Name is empty.

*Precondition:*
User is on the CheckOut: Your Information page.

*Test Data:*
1. First name :JAMES
2. Last name : 
3. Postal Code : 007

*Test Steps:*

1. Open the SauceDemo website.
2. Click ON THE CHECKOUT BUTTON.
3. Input the Test DATA in the required fields and leave last name field empty

*Expected Result:*
The user should see an error message is displayed when Last Name is empty.

*Actual Result:*
The user sees an error message is displayed when Last Name is empty.

*Status:* PASS
