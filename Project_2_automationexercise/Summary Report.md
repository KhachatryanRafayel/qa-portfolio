**Project:** automationexercise.com
**Tester:** Rafayel Khachatryan
**Date:** 17.09.2025

---
## 1. Introduction / Scope
- **Scope:** The main functionality was tested, including homepage, products catalog, autharization, cart, 
- **Objective:** training bug report writing skills
---
## 2. Test Approach

- **Methodology:**  Error Guessing, Boundary Value Analysis
- **Types of Testing:** Positive, Negative, Functional, UI/UX
---

## 3. Test Environment

- **Operating System:** Windows 11 home 24H2
- **Browser:** Google Chrome 140.0.7339.128
- **Screen Resolution:** 1920x1080
---
## 4. Test Results
- **Total Bugs Found:**  11
- **Severity Distribution:**
    - Critical: 2 (18%)
    - Major: 4 (36%)
    - Minor: 4 (36%)
    - Trivial: 1 (10%)
---
## 5. Conclusions
- **Overall Product Status:** The website demonstrates functional usability in general, but several critical and major defects affect core functionality, user experience, and data validation.
- **Critical Issues Identified:**
    - BUG-2: Invalid email format allowed in subscription could cause database issues.
    - BUG-7: No limit on product quantity could impact inventory management and order processing.
- **Recommendations / Next Steps:**
    - Immediately fix critical defects (BUG-7, BUG-8).
    - Address major UX and functional bugs (BUG-4, BUG-5, BUG-6, BUG-10) to prevent user frustration.
    - Minor and trivial defects should be scheduled for regular maintenance and future updates.
-  **Release Recommendation:** Due to the presence of critical defects impacting core functionality (cart and data integrity), it is **not recommended** to release the product to production in its current state. A new round of regression testing is advised after the critical and major bugs are fixed.