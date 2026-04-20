# Bug Reports - Login Module

## BUG001 - Login page reloads instead of logging the user in

Steps to Reproduce:
1. Navigate to the login page  
2. Enter a valid email address  
3. Enter the correct password  
4. Click the login button  

Expected Result:
The user should be successfully logged into the system  

Actual Result:
The login page reloads and the user remains on the login page  

Environment:
iPhone 15, iOS 17, Safari browser  

Priority:
High

BUG002 - No validation error message displayed for invalid email input

Precondition:

User is on the login page  



Steps to Reproduce:

Enter an invalid email address (e.g., abc#gmail.com)  

Enter a valid password  

Click the login button  



Expected Result:

The system should display a validation error message for invalid email and prevent login  
## BUG003 - Search is not triggered when pressing Enter key

Precondition:
User is on the home page  

Steps to Reproduce:
1. Click on the search bar  
2. Enter a valid keyword  
3. Press the Enter key  

Expected Result:
The system should initiate the search and display relevant results  

Actual Result:
The system does not respond when the Enter key is pressed  

Priority: Medium

## BUG005 - Product price differs between product page and cart

Precondition:
User is on a product page  

Steps to Reproduce:
1. Note the product price on the product page  
2. Click "Add to Cart"  
3. Navigate to the cart page  
4. Compare the product price  

Expected Result:
The product price in the cart should match the price on the product page  

Actual Result:
The product price in the cart does not match the price on the product page  

Priority: High
## BUG006 - Order is confirmed despite failed payment

Precondition:
User is on the checkout page  

Steps to Reproduce:
1. Enter invalid payment details  
2. Click "Pay Now"  

Expected Result:
The system should reject the payment and should NOT confirm the order  

Actual Result:
The system rejects the payment but still confirms the order  

Priority: High



## BUG007 - Payment successful but order is not confirmed

Precondition:
User is on the checkout page with valid payment details  

Steps to Reproduce:
1. Enter valid payment details  
2. Click "Pay Now"  

Expected Result:
The system should confirm the order  

Actual Result:
Payment is successful but the order is set to "on hold"  

Priority: High
## BUG008 - Wishlist is not updated despite successful API response

Request:
POST /wishlist/add  
{
  "product_id": 123
}

Expected Response:
- Status Code: 200 OK  
- Wishlist count should increase  

Actual Response:
- Status Code: 200 OK  
- Wishlist count remains 0  

Priority: High
## BUG009 - System allows registration with an existing email

Precondition:
User is on the signup page  

Steps to Reproduce:
1. Enter an already registered email  
2. Enter a valid password  
3. Click "Sign Up"  

Expected Result:
The system should prevent registration and display a message such as "Email already exists"  

Actual Result:
The system allows registration with the existing email  

Priority: High

