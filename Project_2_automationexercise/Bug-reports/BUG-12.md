**ID:** BUG-12
**Severity:** Major
**Priority:** High
## Core Information
*   **Bug Type:** Functional
*   **Build Version:** N/A
*   **Environment:** Laptop / Windows 11 home 24H2 / Google Chrome 140.0.7339.128 / Screen resolution 1920x1080
## Description
\[Login\] Date of Birth fields accept placeholder values ("Day", "Month", "Year").
## Preconditions
N/A
## Steps To Reproduce (STR)
1.  Navigate to registration form page (https://automationexercise.com/login)
2.  In form New User signup input valid name and email
3.  Click Signup or press enter
4.  In date of birth field
    a. From *Day* dropdown, leave the default value "Day".
    b. From *Month* dropdown, leave the default value "Month".
    c. From *Year* dropdown, leave the default value "Year".
5.  Fill in all other mandatory fields with valid data.
6.  Click *Create account* or press Enter.
## Expected Result (ER)
Account isn’t created, Placeholders "Day", "Month", "Year" must not be accepted as valid values. An error message should appear (e.g. “Please select Day / Month / Year”).
## Actual Result (AR)
The system allows submitting the form with placeholder values "Day", "Month", "Year". No error message is displayed. “Account Created!“ message is dispayed.
## Attachments
-  N/A
## Responsibility
-   **Reporter:** Rafayel Khachatryan
-   **Assigned To:** Unassigned
-   **Date Created:** 2025-09-17