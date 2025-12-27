# Test Result Report 📄

### 1. Summary  
Functional and UI testing of the e-commerce platform was conducted based on predefined checklists and test cases. During the testing cycle, 13 defects were identified, two of which require urgent attention before release. The focus was on core user flows: authentication, search, filtering, cart, favorites, and pickup point selection.
### 2. Testing Process Description  
Manual functional and UI testing was performed in the Google Chrome browser on Windows OS All test cases within the defined scope were executed, and identified issues were documented as bug reports. Authentication testing covered both email and phone-based sign-in scenarios.
### 3. Defects Statistics  
**Total defects found:** 13  

Defects by Severity:

| Severity   | Count  | Percentage |
| ---------- | ------ | ---------- |
| **Major**  | 2      | 15.4%      |
| **Medium** | 5      | 38.5%      |
| **Minor**  | 6      | 46.1%      |
| **Total**  | **13** | **100%**   |

![chart](https://github.com/KhachatryanRafayel/qa-portfolio/blob/main/assets/online-store/chart1_severity.png)

Defects by Functional Area:

| Area                       | Count  | Percentage |
| -------------------------- | ------ | ---------- |
| **Authentication**         | 5      | 38.5%      |
| **Search & Filtering**     | 4      | 30.8%      |
| **Pickup Point Selection** | 2      | 15.4%      |
| **Language**               | 1      | 7.7%       |
| **Navigation / UX**        | 1      | 7.7%       |
| **Total**                  | **13** | **100%**   |

![chart](https://github.com/KhachatryanRafayel/qa-portfolio/blob/main/assets/online-store/chart2_func.png)

### 4. Defects
[Bug Reports](https://github.com/KhachatryanRafayel/qa-portfolio/tree/main/Project_3_online_store/bug-reports)
### 5. Conclusion  
Testing revealed several functional and UI issues across core user flows. Two defects are considered high-priority and must be resolved before release:

- **BR-1 (Major):** “Sign in by email” redirects to phone verification — critical for user authentication.  
- **BR-13 (Medium):** “Orders”, “Favorites”, and “Cart” open in new tabs — a serious UX inconsistency.

The remaining defects, while affecting user experience, can be addressed in subsequent iterations. It is recommended to postpone the release until BR-1 and BR-13 are fixed to ensure that the product is usable and reliable at release.
