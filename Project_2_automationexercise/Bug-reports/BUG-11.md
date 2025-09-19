**ID:** BUG-11\
**Severity:** Minor\
**Priority:** Low
## Core Information
*   **Bug Type:** Functional
*   **Build Version:** N/A
*   **Environment:** Laptop / Windows 11 home 24H2 / Google Chrome 140.0.7339.128 / Screen resolution 1920x1080
## Description
\[Products\] Review form Name field accepts space as valid input
## Preconditions
N/A
## Steps To Reproduce (STR)
1.  Navigatate to Products page (https://automationexercise.com/products)
2.  Choose any product, click View Product
3.  In the *Review form*:
    a. Enter a whitespace character (" ") in the *Name* field.
    b. Enter valid characters (e.g., abc) in the *Review* field.
    c. Enter a valid email (e.g., test@gmail.com) in the *Email* field.
4.  Click Submit or press Enter
## Expected Result (ER)
Form should not accept whitespace-only input in the Name field. An error message (e.g., “Invalid value”) should appear.
## Actual Result (AR)
Form accepts whitespace-only input in the Name field. A success message (“Thank you for your review.”) is displayed.
## Attachments
![bug-screenshot](https://github.com/KhachatryanRafayel/qa-portfolio/blob/main/assets/BUG-11.gif)
## Responsibility
-   **Reporter:** Rafayel Khachatryan
-   **Assigned To:** Unassigned
-   **Date Created:** 2025-09-17
