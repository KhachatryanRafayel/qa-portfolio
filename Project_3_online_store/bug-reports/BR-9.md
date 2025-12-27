ID: BR-9  
Related Test Case: SEARCH-19  
Related Bug Reports: BR-8  

Summary: 
- Searching for special characters returns some results.
  
Environment:
- Windows 11 / Google Chrome
  
Expected Result:
- Search results contain no products. The message “Nothing found” is displayed.
  
Actual Result:
- Search results contain a lot of products.
  
Steps to reproduce:
1. Navigate to the "Homepage" -> <BASE_URL>
2. Enter the special characters strings (one of the following "@!+=?", "@#$%"
, "\$%&^", "!@#$%^&*("  ) into the "search" field.
3. Click the "search" button or press Enter
   
Severity: Minor

