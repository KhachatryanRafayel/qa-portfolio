ID: BR-2  
Related Test Case: AUTH-05  
Related Bug Reports: [BR-12](BR-12.md)  

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

Comments: "Sign in or Sign up" page is on Russian language due to related bug (BR-12).

Severity: Minor

Attachments:

![gif](https://github.com/KhachatryanRafayel/qa-portfolio/blob/main/assets/online-store/bug-2.gif)
