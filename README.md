# Swag Labs Manual Testing Documentation



<p>This repository contains comprehensive manual testing documentation for the Swag Labs eCommerce platform (https://www.saucedemo.com/). The documents included in this repository demonstrate complete end-to-end manual testing skills including test planning, test case design, test execution, defect reporting, and requirement traceability.</p>



---



## 📋 Project Overview



<p>This project demonstrates professional manual testing practices on the Swag Labs Demo E-Commerce Application. It covers all phases of the Software Testing Life Cycle (STLC) and includes detailed documentation suitable for a QA portfolio.</p>



**Key Highlights:**

- **122 Test Cases** designed and executed

- **18 Bugs** identified and documented

- **4 Modules** tested (Login, Dashboard, Cart, Checkout)

- **85.2%** overall pass rate

- **8 Critical Bugs** requiring immediate attention



---



## 📂 Repository Contents



<ul>

    <li><strong><a href="SWAG LABS COMPLETE TESTING PROJECT.docx">Swag Labs Testing Full.docx</a></strong> - Master test plan outlining scope, objectives, approach, resources, schedule, risks, and mitigation strategies</li>

    <li><strong><a href="Test Cases.xlsx">Test Cases Swag Labs.xlsx</a></strong> - Complete test case suite with 122 test cases covering Login, Dashboard, Cart, and Checkout modules</li>

    <li><strong><a href="Bug Report.xlsx">Swag Labs Bug Report.xlsx</a></strong> - Detailed bug report documenting 18 defects with severity, priority, steps to reproduce, and screenshots</li>

    <li><strong><a href="RTM.xlsx">Requirement Traceability Matrix.xlsx</strong> - Requirement Traceability Matrix mapping 18 requirements to identified bugs</li>

</ul>



---



## 📊 Module-wise Breakdown



| Module | Test Cases | Passed | Failed | Pass % |

|--------|------------|--------|--------|--------|

| **Login** | 32 | 29 | 3 | 90.6% |

| **Dashboard** | 20 | 15 | 5 | 75.0% |

| **Cart** | 24 | 20 | 4 | 83.3% |

| **Checkout** | 46 | 40 | 6 | 87.0% |

| **TOTAL** | **122** | **104** | **18** | **85.2%** |



---



## 🐞 Bug Summary



<p>Total of <strong>18 bugs</strong> were identified during testing across all modules.</p>



### By Severity



| Severity | Count | Percentage |

|----------|-------|------------|

| **Major** | 8 | 44.4% |

| **Minor** | 10 | 55.6% |



### By Priority



| Priority | Count | Percentage |

|----------|-------|------------|

| **High** | 8 | 44.4% |

| **Medium** | 10 | 55.6% |



### By Module



| Module | Major | Minor | Total |

|--------|-------|-------|-------|

| Login | 1 | 2 | 3 |

| Dashboard | 4 | 1 | 5 |

| Cart | 2 | 2 | 4 |

| Checkout | 2 | 4 | 6 |



---



## 🚨 Critical Bugs Found



<p>The following 8 critical bugs must be fixed before production release:</p>



<ul>

    <li><strong>BUG_LG_003</strong> - User can access Products page using browser back button after logout (Session Vulnerability)</li>

    <li><strong>BUG_DASH_001</strong> - "All Items" menu link is broken and unresponsive</li>

    <li><strong>BUG_DASH_002</strong> - Logout option unresponsive for some users (problem_user)</li>

    <li><strong>BUG_DASH_005</strong> - "Reset App State" only partially resets application state</li>

    <li><strong>BUG_CART_001</strong> - Cart contents do not persist after logout</li>

    <li><strong>BUG_CART_003</strong> - problem_user cart display issues - Items missing or incorrect</li>

    <li><strong>BUG_CHK_001</strong> - Checkout allowed with empty cart</li>

    <li><strong>BUG_CHK_006</strong> - Checkout process broken for problem_user</li>

</ul>



---



## 🛠️ Test Environment



### Hardware



| Component | Specification |

|-----------|---------------|

| **Processor** | Intel Core i3 or equivalent |

| **RAM** | 4 GB or higher |

| **Storage** | 10 GB free space |

| **Network** | Stable Internet Connection (10 Mbps+) |



### Software



| Component | Specification |

|-----------|---------------|

| **Operating Systems** | Windows 11, macOS, Linux |

| **Browsers** | Google Chrome 120+, Firefox 120+, Microsoft Edge 120+ |

| **Tools** | Microsoft Excel, Microsoft Word |



---



## 📝 Test Data



### User Credentials



| Username | Password | Purpose |

|----------|----------|---------|

| `standard_user` | `secret_sauce` | Standard valid user for positive testing |

| `locked_out_user` | `secret_sauce` | Locked out user for negative testing |

| `problem_user` | `secret_sauce` | User with image/functionality issues |

| `performance_glitch_user` | `secret_sauce` | User with slow performance |

| `error_user` | `secret_sauce` | User with error scenarios |

| `visual_user` | `secret_sauce` | User with visual issues |



### Checkout Test Data



| Field | Valid Data | Invalid Data |

|-------|------------|--------------|

| **First Name** | John, Mary, Ahmed | John123, @#$%, (empty) |

| **Last Name** | Doe, Smith, Hasan | Doe123, @#$%, (empty) |

| **Zip/Postal Code** | 90210, 63511, 10001 | 90210@#, ABCDE, (empty) |



---



## 📋 RTM Summary



<p>The Requirement Traceability Matrix (RTM) maps 18 functional requirements to identified bugs.</p>



| Module | Requirements | Violated | Critical Violations |

|--------|--------------|----------|---------------------|

| Login | 3 | 3 (100%) | 1 |

| Dashboard | 5 | 5 (100%) | 2 |

| Cart | 4 | 4 (100%) | 2 |

| Checkout | 6 | 6 (100%) | 2 |

| **TOTAL** | **18** | **18 (100%)** | **8** |



---



## 🚀 Release Readiness



<h3>Overall Status: ⚠️ NOT READY FOR PRODUCTION</h3>



| Criteria | Status |

|----------|--------|

| Test Cases Executed | ✅ 100% (122/122) |

| Pass Rate > 95% | ❌ 85.2% |

| Critical Bugs Fixed | ❌ 8 Open |

| High Priority Bugs Fixed | ❌ 8 Open |



<p><strong>Recommendation:</strong> BLOCK RELEASE until all 8 critical bugs are fixed.</p>



---



## 📚 Key Documents



<ul>

    <li><strong><a href="SWAG LAB COMPLETE TESTING PROJECT.docx">Swag Labs Testing Full.docx</a></strong> - Complete test plan with scope, objectives, approach, schedule, risks, and mitigation</li>

    <li><strong><a href="Test Cases.xlsx">Test Cases Swag Labs.xlsx</a></strong> - 122 test cases across 4 modules with detailed steps and expected results</li>

    <li><strong><a href="Bug Report.xlsx">Swag Labs Bug Report.xlsx</a></strong> - 18 bugs with severity, priority, steps, screenshots, and test data</li>
    
    <li><strong><a href="RTM.xlsx">Requirement Traceability Matrix.xlsx</strong> - Requirement Traceability Matrix mapping 18 requirements to identified bugs</li>

</ul>



---



## 💡 Skills Demonstrated



<ul>

    <li>✅ <strong>Test Planning</strong> - Created comprehensive test plan with scope, objectives, approach, and risk assessment</li>

    <li>✅ <strong>Test Case Design</strong> - Designed 122 test cases using Black Box, Boundary Value, and Equivalence Partitioning techniques</li>

    <li>✅ <strong>Test Execution</strong> - Executed all test cases and documented results with clear pass/fail status</li>

    <li>✅ <strong>Defect Reporting</strong> - Identified and documented 18 bugs with detailed steps and severity/priority</li>

    <li>✅ <strong>RTM Creation</strong> - Developed Requirement Traceability Matrix mapping requirements to bugs</li>

    <li>✅ <strong>Professional Documentation</strong> - Produced industry-standard testing documentation</li>

</ul>



---





---


## 📄 License



<p>This project is for <strong>educational and portfolio purposes only</strong>.</p>



---


<div align="center">



### ⭐ If you find this project helpful, please give it a star!



</div>

