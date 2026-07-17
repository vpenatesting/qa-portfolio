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
