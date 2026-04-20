# Test Cases - Login Functionality

## TC001 - Verify login with valid credentials

Precondition:
User is on the login page  

Steps:
1. Navigate to the login page  
2. Enter a valid email address  
3. Enter the correct password  
4. Click the login button  

Expected Result:
User is successfully logged into the system
---

## TC002 - Verify login with invalid password

Precondition:
User is on the login page  

Steps:
1. Navigate to the login page  
2. Enter a valid email address  
3. Enter an incorrect password  
4. Click the login button  

Expected Result:
The system should display an error message and prevent login  

---

## TC003 - Verify login with empty fields

Precondition:
User is on the login page  

Steps:
1. Leave the email field empty  
2. Leave the password field empty  
3. Click the login button  

Expected Result:
The system should display validation messages and prevent login  

---

## TC004 - Verify login with invalid email format

Precondition:
User is on the login page  

Steps:
1. Navigate to the login page  
2. Enter an email with invalid format (e.g., xyz#gmail.com)  
3. Enter a valid password  
4. Click the login button  

Expected Result:
The system should display a validation error message for invalid email format and prevent login  

---

## TC005 - Verify login with excessively long email address

Precondition:
User is on the login page  

Steps:
1. Enter an email address exceeding the allowed length (e.g., 100+ characters)  
2. Enter a valid password  
3. Click the login button  

Expected Result:
The system should display a validation error message and prevent login  

---

## TC006 - Verify login with empty password field

Precondition:
User is on the login page  

Steps:
1. Enter a valid email address  
2. Leave the password field empty  
3. Click the login button  

Expected Result:
The system should display a validation error message for the password field and prevent login  

---

## TC007 - Verify login with password containing only whitespace

Precondition:
User is on the login page  

Steps:
1. Enter a valid email address  
2. Enter a password containing only whitespace characters (e.g., 8 spaces)  
3. Click the login button  

Expected Result:
The system should display a validation error message indicating an invalid password and prevent login  

---

## TC008 - Verify login with uppercase email address

Precondition:
User is on the login page  

Steps:
1. Enter a valid email address in uppercase (e.g., TEST@GMAIL.COM)  
2. Enter a valid password  
3. Click the login button  

Expected Result:
The system should treat the email input as case-insensitive and allow the user to log in successfully  

## TC009 - Verify search with exact product name

Precondition:
User is on the home page  

Steps:
1. Click on the search bar  
2. Enter an exact product name (e.g., "iPhone 17")  
3. Click the search button  

Expected Result:
The system should display relevant products matching the entered product name  
## TC010 - Verify search using Enter key

Precondition:
User is on the home page  

Steps:
1. Click on the search bar  
2. Enter a valid keyword  
3. Press the Enter key  

Expected Result:
The system should initiate the search and display relevant results  
## TC011 - Verify adding a single product to the cart

Precondition:
User is on a product page  

Steps:
1. Click the "Add to Cart" button  
2. Click the cart icon  

Expected Result:
The selected product should be added to the cart and displayed correctly  
## TC012 - Verify adding multiple different products to the cart

Precondition:
User is on a product page  

Steps:
1. Click "Add to Cart" for Product A  
2. Navigate to another product page (Product B)  
3. Click "Add to Cart" for Product B  
4. Click the cart icon  

Expected Result:
Both products should be added to the cart with correct quantity and details  
## TC013 - Verify maximum quantity limit for a product

Precondition:
User is on a product page  

Steps:
1. Click "Add to Cart"  
2. Increase product quantity beyond allowed limit (e.g., 100)  
3. Click the cart icon  

Expected Result:
The system should limit the quantity to the maximum allowed (e.g., 20) and display a message such as "Maximum order quantity reached"  
## TC014 - Verify removing a product from the cart

Precondition:
User has at least one product in the cart  

Steps:
1. Click the cart icon  
2. Click the delete/remove (trash bin) icon next to the product  

Expected Result:
The selected product should be removed from the cart  
## TC015 - Verify checkout button initiates checkout process

Precondition:
User is on the cart page with at least one item  

Steps:
1. Click the "Checkout" button  

Expected Result:
The system should navigate to the checkout page and prompt for payment details  
## TC016 - Verify total price consistency between cart and checkout

Precondition:
User is on the cart page with at least one item  

Steps:
1. Note the total price in the cart  
2. Click the "Checkout" button  
3. Observe the total price on the checkout page  

Expected Result:
The total price on the checkout page should match the cart total (including taxes and delivery fees if applicable)  
## TC017 - Verify checkout behavior with empty cart

Precondition:
User is on the cart page with no items  

Steps:
1. Observe the checkout button  
2. Attempt to proceed to checkout  

Expected Result:
The system should display a message such as "Your cart is empty" and disable the checkout button  
## TC018 - Verify checkout with invalid card number

Precondition:
User is on the checkout page  

Steps:
1. Enter an invalid card number  
2. Enter valid details in other fields  
3. Click "Pay Now"  

Expected Result:
The system should reject the payment and display a message such as "Invalid card number"  
## TC019 - Verify checkout without cardholder name

Precondition:
User is on the checkout page  

Steps:
1. Enter a valid card number  
2. Leave the cardholder name field empty  
3. Enter valid details in other fields  
4. Click "Pay Now"  

Expected Result:
The system should prevent payment and display a message such as "Please enter cardholder name"  

## TC021 - Verify signup with valid email and password

Precondition:
User is on the signup page  

Steps:
1. Enter a valid email (e.g., xyz@abc.com)  
2. Enter a valid password  
3. Click "Sign Up"  

Expected Result:
User account is created and a confirmation email is sent  
## TC022 - Verify signup with password containing only whitespaces

Precondition:
User is on the signup page  

Steps:
1. Enter a valid email  
2. Enter a password with only spaces (e.g., 8 spaces)  
3. Click "Sign Up"  

Expected Result:
The system should reject the password and display a validation message such as "Invalid password"  
## TC022 - Verify signup with password containing only whitespaces

Precondition:
User is on the signup page  

Steps:
1. Enter a valid email  
2. Enter a password with only spaces (e.g., 8 spaces)  
3. Click "Sign Up"  

Expected Result:
The system should reject the password and display a validation message such as "Invalid password"  
