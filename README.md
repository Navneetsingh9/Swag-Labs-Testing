# 🧪 Swag Labs Manual Testing Documentation

This repository contains manual testing documentation for the **Swag Labs** e-commerce application (https://www.saucedemo.com/).

The project demonstrates end-to-end manual testing activities, including test planning, test case design, test execution, defect reporting, and requirement traceability.

---

## 📋 Project Overview

This project showcases professional QA testing practices by covering the complete Software Testing Life Cycle (STLC).

### Project Highlights

- ✅ 122 Test Cases Designed & Executed
- 🐞 18 Bugs Identified
- 📦 4 Modules Tested
- 📈 85.2% Test Pass Rate
- 🚨 8 High Priority Bugs Found

---

# 📂 Repository Contents

| Document | Description |
|----------|-------------|
| 📄 **[Swag Labs Testing Project](SWAG%20LABS%20COMPLETE%20TESTING%20PROJECT.docx)** | Complete Test Plan including scope, objectives, testing approach, schedule, risks, and mitigation. |
| 📊 **[Test Cases](Test%20Cases.xlsx)** | Contains 122 manual test cases covering Login, Dashboard, Cart, and Checkout modules. |
| 🐞 **[Bug Report](Bug%20Report.xlsx)** | Detailed bug report with severity, priority, steps to reproduce, expected and actual results. |
| 📑 **[Requirement Traceability Matrix](RTM.xlsx)** | Maps project requirements with corresponding test cases and reported defects. |

---

# 📊 Module Summary

| Module | Test Cases | Passed | Failed | Pass Rate |
|---------|-----------:|--------:|--------:|----------:|
| Login | 32 | 29 | 3 | 90.6% |
| Dashboard | 20 | 15 | 5 | 75.0% |
| Cart | 24 | 20 | 4 | 83.3% |
| Checkout | 46 | 40 | 6 | 87.0% |
| **Total** | **122** | **104** | **18** | **85.2%** |

---

# 🐞 Bug Summary

### By Severity

| Severity | Count |
|----------|------:|
| Major | 8 |
| Minor | 10 |

### By Priority

| Priority | Count |
|----------|------:|
| High | 8 |
| Medium | 10 |

---

# 🚨 Major Issues Identified

The following high-priority defects were discovered during testing:

- User can access the Products page after logout using the browser Back button.
- "All Items" menu option is unresponsive.
- Logout fails for **problem_user**.
- "Reset App State" does not fully reset the application.
- Cart items are lost after logout.
- Cart behaves incorrectly for **problem_user**.
- Checkout is allowed even when the cart is empty.
- Checkout process fails for **problem_user**.

---

# 🖥️ Test Environment

| Category | Details |
|----------|---------|
| Operating System | Windows 11 |
| Browsers | Chrome, Firefox, Microsoft Edge |
| Testing Type | Manual Testing |
| Documentation | Microsoft Excel & Microsoft Word |

---

# 🔑 Test Data

### Login Credentials

| Username | Password | Purpose |
|----------|----------|---------|
| standard_user | secret_sauce | Positive Testing |
| locked_out_user | secret_sauce | Negative Testing |
| problem_user | secret_sauce | Functional Testing |
| performance_glitch_user | secret_sauce | Performance Testing |
| error_user | secret_sauce | Error Validation |
| visual_user | secret_sauce | UI Testing |

---

# 📈 Release Status

## ⚠️ Not Ready for Production

| Criteria | Status |
|----------|--------|
| Test Cases Executed | ✅ Yes |
| Pass Rate Above 95% | ❌ No |
| Critical Bugs Fixed | ❌ No |
| High Priority Bugs Fixed | ❌ No |

**Recommendation:** The application should not be released until all high-priority defects are resolved.

---

# 🛠 Skills Demonstrated

- Test Planning
- Test Case Design
- Test Execution
- Defect Reporting
- Requirement Traceability Matrix (RTM)
- Functional Testing
- Positive & Negative Testing
- Boundary Value Analysis
- Equivalence Partitioning
- QA Documentation

---

# 📄 License

This project is intended for **educational and portfolio purposes only**.

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

</div>
