# The Summary Report

**Project:** ArmTypingTest  
**Tester:** Rafayel Khachatryan  
**Date:** 03.09.2025

---
## 1. Introduction / Scope
- **Scope:** The core functionality of the game was tested, including launch, gameplay (text input, validation, controls), statistics calculation and display (WPM/CPM), end-of-game screen, and settings functionality.
- **Objective:** Verify the stability and correctness of the game's core functionality.
---
## 2. Test Approach
- **Methodology:** Positive and Negative Testing, Boundary Value Analysis.
- **Types of Testing:** Functional, UI/UX.
---
## 3. Test Environment
- **Operating System:** Windows 11
- **Browser:** Google Chrome
- **Screen Resolution:** 1920x1080
---
## 4. Test Results
- **Total Test Cases Executed:** 28
- **Total Bugs Found:** 8
- **Severity Distribution:**
    - Critical: 0 (0%)
    - Major: 3 (37.5%)
    - Minor: 2 (25%)
    - Trivial: 3 (37.5%)
---
## 5. Conclusions
- **Overall Product Status:** The application core is stable. The game launches successfully, basic text input and navigation work. However, defects affecting user experience and some key functions were found, such as key repeat, game reset, and lack of planned settings.
- **Key Issues Identified:**
    - **Gameplay:** No character repeat on key hold or full deletion with held Backspace. Lack of visual feedback for errors and handling of long words.
    - **Functionality:** Hotkey (R) for restarting the game during a session does not work.
    - **Settings:** The advertised settings functionality (difficulty and session duration) is completely missing.
- **Recommendations / Next Steps:**
    1. Fix bugs related to held key handling (BUG-1, BUG-2).
    2. Implement visual feedback for incorrectly entered words (BUG-4).
    3. Fix input field overflow handling (BUG-3).
    4. Enable the restart hotkey functionality (R) (BUG-5).
    5. Implement or remove the settings menu from requirements (BUG-6, BUG-7).
- **Release Recommendation:** Due to the presence of defects directly impacting the user experience (Major) and the absence of advertised functionality, the release of the current version is **not recommended**. It is advised to fix the mentioned major bugs and conduct a new round of testing.
