ID: BR-3  
Related Test Case: AUTH-06  
Related Bug Reports: BR-12  

Summary: 
- The system display incorrect validation message when entering invalid email format to the email field (e.g. test.com, test@, @test.com, test@test, test@test_test)
  
Environment:
- Windows 11 / Google Chrome

Expected Result:
- The email address field highlights, and the validation error "invalid email format" should appear.
  
Actual Result:
- The email address field highlights, an inappropriate validation message "Do not use spaces, Cyrillic characters, or special characters." appears.
  
Steps to reproduce:
1. Navigate to the "Sign in or Sign up" page -> <BASE_URL>/auth
2. Click the "Sign in by email" button
3. Enter an invalid email address to the email field (one of the following՝ test.com, test@, @test.com, test@test, test@test_test)
4. Click the "Sign in" button or press Enter
   
Comments: 
- Test data doesn't contain spaces, Cyrillic characters, or special characters, so the validation error message is inappropriate. 
- "Sign in or Sign up" page is on Russian language due to related bug (BR-12).

Severity: Minor

