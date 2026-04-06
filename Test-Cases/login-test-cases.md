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
