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
