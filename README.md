# OpenCart Manual Testing Project 

## Project Overview
This project contains manual testing documentation for the demo e-commerce website of OpenCart.  
The objective of this project is to perform manual testing on major functionalities of the application such as login, registration, product search, cart management, and checkout process.

Testing Type: Manual Testing  
Test Environment: Web Application  
Browser Used: Google Chrome  

---

## Application Under Test
Application Name: OpenCart Demo Store  
Application Type: E-commerce Web Application  
Website: https://demo.opencart.com  

---

## Testing Scope
The following modules were tested:

- Login Functionality
- User Registration
- Product Search
- Add to Cart
- Checkout Process
- Logout and Session Management

---

## Test Deliverables
This repository contains the following testing documents:

- Test Plan
- Test Senario
- Bug Reports 
- Screenshots of identified bugs

---

## Test Case Summary

| Total Test Cases | Passed | Failed |
|------------------|--------|--------|
| 30               | 28     | 2      |

---

## Bug Summary

| Severity | Number of Bugs |
|----------|----------------|
| High     | 4              |
| Medium   | 4              |
| Low      | 2              |

Total Bugs Identified: 10

---

## Repository Structure

```
OpenCart-Manual-Testing
│
├── Test_Senario
│   └── TestCases.xlsx
│
├── Bug_report
│   └── BugReport.xlsx
│
├── TestPlan
│   └── TestPlan.docx
│
├── Screenshots
│
└── README.md
```


---

## Environment Setup (Somke Testing)
- Operating System: Windows 10
- Server: XAMPP
- Application: OpenCart
- Browser: Google Chrome
- Database: MySQL

## Installation Steps

1. Download OpenCart from the official website.
2. Extract the zip file.
3. Copy the contents of the `upload` folder to:
   C:\xampp\htdocs\opencart
4. Start Apache and MySQL from XAMPP Control Panel.
5. Create a database named `opencart_db` using phpMyAdmin.
6. Open the browser and navigate to:
   http://localhost/opencart
7. Complete the installation wizard.

## Configuration Fixes

During installation, the following issues were identified and resolved:

### Missing PHP Extensions
The following extensions were disabled:
- GD
- ZIP

Solution:
Enabled them in `php.ini`:

extension=gd  
extension=zip

### Missing Configuration Files
The installer reported missing files:
- config.php
- admin/config.php

Solution:
Renamed the following files:

config-dist.php → config.php  
admin/config-dist.php → config.php

## Testing Scope
Manual testing was conducted on the following modules:
- User Login
- Product Search
- Add to Cart
- Checkout Process
- Admin Login

## Tools Used
- Jira (Bug tracking)
- Postman (API testing)
- Zephyr (Test case management)
- Microsoft Excel
- Google Chrome
- GitHub (documentation and version control)

## What I Have Done?
*Agile Scrum Activities*
- Project creation and environment selection in Jira
- Invite people and made a team ,distribute roles
- Create Backlog properties (version,epic)
- Create story,story point,sprint,proirity
- Adding subtask and create sprint life cycle

*Test Management Activities(Zephyr)*
- Test Case
- Test Cycle
- Update TestCase
- Report Bugs
- Report
- Traceability Matrix

---


## Author

Name: Umme Jami
---
Role: QA Manual Testing Practice Project
