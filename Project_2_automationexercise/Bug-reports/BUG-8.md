**ID:** BUG-8
**Severity:** Critical
**Priority:** Highest
## Core Information
*   **Bug Type:** Functional
*   **Build Version:** N/A
*   **Environment:** Laptop / Windows 11 home 24H2 / Google Chrome 140.0.7339.128 / Screen resolution 1920x1080
## Description
\[Cart\] Adding zero or negative items is possible.
## Preconditions
N/A
## Steps To Reproduce (STR)
1.  Navigatate to product page (https://automationexercise.com/products)
2.  Choose any product, click View Product
3.  In quantity field input negative number (e.g.-10) or zero.
4.  Click Add to cart button
5.  In the modal that appears click View cart
## Expected Result (ER)
System should prevent adding zero or negative quantity of items and display a warning message. The ‘Add to Cart’ button should be disabled in this case.
## Actual Result (AR)
User can add to cart non positive items.
## Attachments
-  Screenshot 2025-09-17 175902.png
## Responsibility
-   **Reporter:** Rafayel Khachatryan
-   **Assigned To:** Unassigned
-   **Date Created:** 2025-09-17