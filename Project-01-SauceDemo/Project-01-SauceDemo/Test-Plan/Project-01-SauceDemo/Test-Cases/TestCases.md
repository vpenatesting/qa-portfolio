# Test Cases - SauceDemo E-Commerce Website

## Test Case 1: Verify Login With Valid Credentials

**Test Case ID:** TC001

**Test Scenario:** User should be able to log in with valid credentials.

**Preconditions:**
- User is on the SauceDemo login page.

**Test Steps:**
1. Enter username: standard_user
2. Enter password: secret_sauce
3. Click Login button

**Expected Result:**
User should successfully log in and see the Products page.

**Actual Result:**
User successfully logged in and Products page displayed.

**Status:**
Pass


---

# Test Case 2: Verify Login With Invalid Password

**Test Case ID:** TC002

**Test Scenario:** User should not be able to log in with an incorrect password.

**Preconditions:**
- User is on the SauceDemo login page.

**Test Steps:**
1. Enter valid username.
2. Enter incorrect password.
3. Click Login.

**Expected Result:**
An error message should display indicating login failure.

**Actual Result:**
An error message "Epic sadface: Username and password do not match any user in this service" was displayed. User was not able to log in and remained on the login page.

**Status:**
Pass

---

# Test Case 3: Verify User Cannot Login With Empty Fields

**Test Case ID:** TC003

**Test Scenario:** Verify validation when login fields are empty.

**Preconditions:**
- User is on the login page.

**Test Steps:**
1. Leave username empty.
2. Leave password empty.
3. Click Login.

**Expected Result:**
Required field validation message should appear.

**Actual Result:**

An error messae "Epic sadface: Username is required" was displayed. User was not able to log in and remained on the login page.

**Status:**
Pass


---

# Test Case 4: Verify User Can Add Product To Cart

**Test Case ID:** TC004

**Test Scenario:** User should be able to add a product to the shopping cart.

**Preconditions:**
- User is logged in.

**Test Steps:**
1. Select a product.
2. Click Add to Cart.
3. Open shopping cart.

**Expected Result:**
Selected product should appear in the cart.

**Actual Result:**
The selected product was successfully added to the shopping cart. The cart icon displayed the item count, and the product appeared in the cart with the correct name and details.

**Status:**
Pass


---

# Test Case 5: Verify User Can Remove Product From Cart

**Test Case ID:** TC005

**Test Scenario:** User should be able to remove an item from the cart.

**Preconditions:**
- User has added a product to the cart.

**Test Steps:**
1. Open shopping cart.
2. Click Remove.

**Expected Result:**
Product should be removed from the cart.

**Actual Result:**
The selected product was successfully removed from the shopping cart. The product was no longer displayed, and the cart item count was updated.

**Status:**
Pass


---

## Test Case 6: Verify product sorting

**Test Case ID:** TC006

**Test Scenario:** Verify that users can sort products using the sorting dropdown.

**Preconditions:**
- User is logged into SauceDemo.
- User is on the Products page.

**Test Steps:**
1. Click the product sorting dropdown.
2. Select "Price (low to high)".
3. Review the product list.

**Expected Result:**
Products should be displayed in ascending order based on price.

**Actual Result:**
The product list was successfully sorted from the lowest price to the highest price. Products displayed in the correct order.

**Status:**
Pass


---

## Test Case 7: Verify Checkout Page Opens

**Test Case ID:** TC007

**Test Scenario:** Verify that users can proceed from the cart to the checkout page.

**Preconditions:**
- User is logged in.
- User has at least one product added to the cart.

**Test Steps:**
1. Open the shopping cart.
2. Click the Checkout button.

**Expected Result:**
User should be redirected to the Checkout Information page.

**Actual Result:**
The Checkout Information page opened successfully after clicking the Checkout button.

**Status:**
Pass


---

## Test Case 8: Verify Checkout Required Fields Validation

**Test Case ID:** TC008

**Test Scenario:** Verify that checkout fields are required before completing an order.

**Preconditions:**
- User is logged in.
- Product is added to the cart.
- User is on the Checkout Information page.

**Test Steps:**
1. Leave First Name blank.
2. Leave Last Name blank.
3. Leave Zip/Postal Code blank.
4. Click Continue.

**Expected Result:**
A validation message should display requesting the required information.

**Actual Result:**
An error message "Error: First Name is required" was displayed, and the user was unable to continue without entering required information.

**Status:**
Pass


---

## Test Case 9: Verify Order Completion

**Test Case ID:** TC009

**Test Scenario:** Verify that users can successfully complete an order.

**Preconditions:**
- User is logged in.
- Product is added to the cart.
- Checkout information is completed.


**Test Steps:**
1. Enter valid checkout information.
2. Click Continue.
3. Review order summary.
4. Click Finish.

**Expected Result:**
Order should be completed and confirmation message should display.

**Actual Result:**
Order was successfully completed, and the confirmation message "Thank you for your order!" was displayed.

**Status:**
Pass


---

## Test Case 10: Verify Logout Functionality

**Test Case ID:** TC010

**Test Scenario:** Verify that users can successfully log out of the application.

**Preconditions:**
- User is logged into SauceDemo.

**Test Steps:**
1. Click the menu icon.
2. Click Logout.

**Expected Result:**
User should be logged out and redirected to the login page.

**Actual Result:**
User was successfully logged out and redirected to the login page.

**Status:**
Pass










---



