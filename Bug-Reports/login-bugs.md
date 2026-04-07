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



Actual Result:

The system prevents login but does not display any validation error message  
