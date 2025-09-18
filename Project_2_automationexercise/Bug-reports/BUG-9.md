**ID:** BUG-9
**Severity:** Minor
**Priority:** Low
## Core Information
*   **Bug Type:** Functional
*   **Build Version:** N/A
*   **Environment:** Laptop / Windows 11 home 24H2 / Google Chrome 140.0.7339.128 / Screen resolution 1920x1080
## Description
\[Cart\] User can enter non-numeric characters in quantity field.
## Preconditions
N/A
## Steps To Reproduce (STR)
1.  Navigatate to product page (https://automationexercise.com/products)
2.  Choose any product, click View Product
3.  In quantity field input one of this invalid values (e; E; -; --; ,)
4.  Click Add to cart button
## Expected Result (ER)
System should prevent entering non-numeric characters in the quantity field and display a warning message. The ‘Add to Cart’ button should be disabled in this case.
## Actual Result (AR)
User can enter invalid characters (e, E, -, --, ,) in the quantity field and still click the ‘Add to Cart’ button. No warning message appears.
## Attachments
-  N/A
## Responsibility
-   **Reporter:** Rafayel Khachatryan
-   **Assigned To:** Unassigned
-   **Date Created:** 2025-09-17