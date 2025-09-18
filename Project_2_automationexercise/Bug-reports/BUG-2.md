**ID:** BUG-2\
**Severity:** Major\
**Priority:** High
## Core Information
*   **Bug Type:** Functional
*   **Build Version:** N/A
*   **Environment:** Laptop / Windows 11 home 24H2 / Google Chrome 140.0.7339.128
## Description
\[Homepage\] The email validation on the subscription form is not working correctly, allowing invalid email formats to be submitted. This leads to incorrect data collection and a confusing user experience.
## Preconditions
User is not subscribed
## Steps To Reproduce (STR)
1.  Navigate to homepage (https://automationexercise.com/)
2.  Scroll all the way down the page
3.  In subscription form enter “a@a“
4.  Press “enter” button or click the subscribe button
## Expected Result (ER)
Error message “Invalid email format” appears.
## Actual Result (AR)
Subscription accepted, message “You have been successfully subscribed!“ appears.
## Attachments
![bug-photo](https://github.com/KhachatryanRafayel/qa-portfolio/blob/main/assets/BUG-2.gif)
## Responsibility
-   **Reporter:** Rafayel Khachatryan
-   **Assigned To:** Unassigned
-   **Date Created:** 2025-09-13
