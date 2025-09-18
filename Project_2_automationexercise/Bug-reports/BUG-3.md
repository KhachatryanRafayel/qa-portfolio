**ID:** BUG-3\
**Severity:** Major\
**Priority:** High
## Core Information
*   **Bug Type:** Functional
*   **Build Version:** N/A
*   **Environment:** Laptop / Windows 11 home 24H2 / Google Chrome 140.0.7339.128
## Description
\[Homepage\] Subscription form allows duplicate email submissions.
## Preconditions
User is not subscribed
## Steps To Reproduce (STR)
1.  Navigate to homepage (https://automationexercise.com/)
2.  Scroll all the way down the page
3.  In subscription form enter “example@gmail.com“
4.  Press “enter” button or click the subscribe button
5.  In subscription form enter second time “example@gmail.com“
6.  Press “enter” button or click the subscribe button
## Expected Result (ER)
Error message “You are already subscribed” appears.
## Actual Result (AR)
Subscription accepted second time with the same email, message “You have been successfully subscribed!“ appears.
## Attachments
![bug-image](https://github.com/KhachatryanRafayel/qa-portfolio/blob/main/assets/BUG-3.gif)
## Responsibility
-   **Reporter:** Rafayel Khachatryan
-   **Assigned To:** Unassigned
-   **Date Created:** 2025-09-15
