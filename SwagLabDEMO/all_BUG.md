### BUG-001 – Reset App State does not reset product button ###

Title: Add to Cart button remains as "Remove" after resetting app state

Severity: Medium
Priority: Medium

## Environment: ##

Website: SauceDemo
Browser: Chrome
OS: Windows

Precondition:
User is logged in and has added a product to the cart.

**Steps to Reproduce:**

Log in to SauceDemo.
Add any product to the cart.
Confirm that the button changes from Add to Cart to Remove.
Open the hamburger menu (☰).
Click Reset App State.
Return to the Products page.

*Expected Result:*
The application should reset completely. The product button should change from Remove back to Add to Cart.

*Actual Result:*
The product is reset from the cart, but the button still displays Remove instead of Add to Cart.

