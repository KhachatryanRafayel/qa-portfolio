ID: BR-1  
Related Test Case: AUTH-02  
Related Bug Reports: [BR-12](BR-12.md)  
Summary:   
- "Sign in by email" button redirects user to phone number verification page instead of email verification page during sign in

Environment:  
- Windows 11 / Google Chrome

Expected Result:  
- After clicking "Sign in by email" button the system redirects user to email verification page

Actual Result:  
- After clicking "Sign in by email" button the system redirects user to phone number verification page

Steps to reproduce:
1. Navigate to the "Sign in or Sign up" page -> <BASE_URL>/auth
2. Click the "Sign in by email" button
3. Enter a valid email address to the email field (email should be linked to any account)
4. Click the "Sign in" button or press Enter

Comments: "Sign in or Sign up" page is on Russian language due to related bug (BR-12).

Severity: Major  

Workaround: Yes  

Attachments:

![gif](https://github.com/KhachatryanRafayel/qa-portfolio/blob/main/assets/online-store/bug-1.gif)

