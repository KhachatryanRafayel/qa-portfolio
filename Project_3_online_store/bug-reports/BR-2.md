ID: BR-2  
Related Test Case: AUTH-05

Summary: 
- The system doesn't display a validation message when entering non-numeric characters to the phone number field during sign in

Environment: 
- Windows 11 / Google Chrome

Expected Result: 
- The phone number field doesn't accept non-numeric characters and highlights (e.g. a red outline appears). A validation error message (e.g. "invalid phone number format") appears

Actual Result: 
- The phone number field doesn't accept non-numeric characters and doesn't highlight․ A validation error message doesn't appear.

Steps to reproduce:
1. Navigate to the "Sign in or Sign up" page -> <BASE_URL>/auth
2. Enter special characters (e.g. !@#$%^&\*()) to the phone number field

Severity: Minor

