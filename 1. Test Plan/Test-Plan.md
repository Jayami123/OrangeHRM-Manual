# Test Plan for OrangeHRM Manual Testing

## 1. Introduction

This test plan outlines the strategy, scope, objectives, and approach for the manual testing of selected modules in OrangeHRM. The purpose of this testing is to verify the functional correctness of key HRM features, ensure compliance with expected business requirements, and identify usability concerns. The testing will be performed manually using a structured test case-based approach, supplemented by exploratory testing to uncover hidden defects.

## 2. Test Objectives

The primary objectives of this test are:

* To validate the functional correctness of the login page
* To ensure that employees can apply for leave through the Leave module
* To verify that an employee can be successfully added through the PIM module
* To identify and document defects and usability issues within these functionalities

## 3. Scope of Testing

### In-Scope:

* **Login Page**: Verifying user authentication, error handling, and UI elements
* **Applying a Leave (Leave Module)**: Ensuring users can select leave types, dates, and submit requests
* **Adding an Employee (PIM Module)**: Checking if new employee details can be entered and saved correctly

### Out-of-Scope:

* Performance testing, security testing, and API testing
* Other HRM modules such as Recruitment, Time Tracking, and Payroll

## 4. Testing Approach

* **Testing Type:** Functional Testing
* **Testing Methodology:** Manual black-box testing focusing on user interactions and expected system behavior
* **Test Case Design:** Test cases are designed based on functional requirements and exploratory testing

## 5. Test Environment

* **Platform:** Web-based application (Orange HRM Demo Site)
* **Browser:** Google Chrome
* **Operating System:** Windows (Laptop)
* **Defect Tracking Tool:** Microsoft Excel

## 6. Test Deliverables

The following documents will be created and maintained as part of this test:

* Test Cases Document
* Bug Reports
* Test Summary Report

## 7. Entry & Exit Criteria

### Entry Criteria:

* Access to the OrangeHRM demo site is available
* Test cases are prepared
* Test environment is set up (browser and system ready)

### Exit Criteria:

* All planned test cases are executed
* Major functional defects are reported and documented
* A test summary report is prepared

## 8. Test Schedule

* **Testing Duration:** 1 week
* **Execution Timeline:** Includes test case execution, defect reporting, and test summary preparation

## 9. Risks & Mitigation

* **Risk:** The OrangeHRM demo site may experience downtime or unexpected changes
    * **Mitigation:** Test execution will be scheduled flexibly, and alternative test scenarios will be considered if the site is inaccessible
* **Risk:** Limited access to advanced testing tools
    * **Mitigation:** Excel is used for test management and bug reporting

## 10. Roles & Responsibilities

* **Tester:** Jayami Hettigoda
    * Responsible for test case creation, execution, defect reporting, and documentation
