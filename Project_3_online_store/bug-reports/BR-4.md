ID: BR-4
Related Test Case: AUTH-07
Summary: 
- The system doesn't display a validation message when entering too long phone numbers (>15 digits) to the phone number field during sign in
Environment:
- Windows 11 / Google Chrome
Expected Result:
- The phone number field doesn't accept too long phone numbers (>15 digits) and highlights (e.g. a red outline appears). A validation error message (e.g. "Too long phone number") appears 
Actual Result:
- The phone number field doesn't accept too long phone numbers (>15 digits) and doesn't highlight. A validation error message doesn't appear. 
Steps to reproduce:
1. Navigate to the "Sign in or Sign up" page -> <BASE_URL>/auth
2. Enter too long phone number (>15 digits)
Severity: Minor