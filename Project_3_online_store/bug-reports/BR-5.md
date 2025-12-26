ID: BR-5
Related Test Case: AUTH-08
Related Bug Reports: BR-12
Summary: 
- The system display incorrect validation message when entering too long email address (>255 characters) to the email field
Environment:
- Windows 11 / Google Chrome
Expected Result:
- The "email address" form does not accept too long email addresses (>255 characters). A validation message 'Too long email address" appears
Actual Result:
- The "email address" form does not accept too long email addresses (>255 characters). An inappropriate validation message "Do not use spaces, Cyrillic characters, or special characters." appears.
Steps to reproduce:
1. Navigate to the "Sign in or Sign up" page -> <BASE_URL>/auth
2. Click the "Sign in by email" button
3. Enter a valid email value with a length over 255 characters into the email field.
4. Click the "Sign in" button or press Enter
Severity: Minor
Comments: "Sign in or Sign up" page is on Russian language due to related bug (BR-12).
