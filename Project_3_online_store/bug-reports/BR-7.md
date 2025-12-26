ID: BR-7
Related Test Cases: SEARCH-14, SEARCH-016
Summary: 
- Some search results price filters show product prices above the selected price filter range.
Environment:
- Windows 11 / Google Chrome
Expected Result:
- Search result on the first pagination page shows only products with the selected price filter range.
Actual Result:
- Search result on the first pagination page contains products above the selected price filter range.
Steps to reproduce:
1. Navigate to the "Homepage" -> <BASE_URL>
2. Enter "t-shirt" into the search field
3. Click the "search" button or press Enter
4. Apply the price filter in range 2000-3000.
5. Scroll down and find products above the price filter range. (e.g. 3100)
Severity: Major
Workaround: Yes
