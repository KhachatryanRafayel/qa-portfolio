ID: BR-8  
Related Test Case: SEARCH-18  
Related Bug Reports: [BR-9](BR-9.md) 

Summary: 
- Search for a non-existent product returns some results.
  
Environment:
- Windows 11 / Google Chrome
  
Expected Result:
- Search results contain no products. The message “Nothing found” is displayed.
  
Actual Result:
- Search results contain a lot of products.
  
Steps to reproduce:
1. Navigate to the "Homepage" -> <BASE_URL>
2. Enter an invalid product name "tuttuuuuu" into the "search" field.
3. Click the "search" button or press Enter
   
Severity: Minor
