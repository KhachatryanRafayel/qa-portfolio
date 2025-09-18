**ID:** BUG-7
**Severity:** Critical
**Priority:** Highest
## Core Information
*   **Bug Type:** Functional
*   **Build Version:** N/A
*   **Environment:** Laptop / Windows 11 home 24H2 / Google Chrome 140.0.7339.128 / Screen resolution 1920x1080
## Description
\[Cart\] No limit on product quantity selection.
## Preconditions
N/A
## Steps To Reproduce (STR)
1.  Navigatate to product page (https://automationexercise.com/products)
2.  Choose any product, click View Product
3.  In quantity field input big number (e.g. 9999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999999)
4.  Click Add to cart button
5.  In the modal that appears click View cart
## Expected Result (ER)
System should enforce a maximum quantity limit per order (e.g., stock availability or other rule).
## Actual Result (AR)
User can add to cart unlimited quantity of products.
## Attachments
-  Screenshot 2025-09-17 140717.png
## Responsibility
-   **Reporter:** Rafayel Khachatryan
-   **Assigned To:** Unassigned
-   **Date Created:** 2025-09-17