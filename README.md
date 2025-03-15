# Functional Testing of website -Arena School Enquiry Form & Hotel Booking website . 

## Overview

This project was done in my **cognizant internship program** where two dummy website was given to perform the **Functional Testing**. In this project **testing docs template** was provided by the **cognizant** along with website. There were some description of the **functionality** or the **test scenarion** which was supposed to be tested. 

The purpose of this project is to track, manage, and execute test cases stored in an Excel file and ensure the system's features work as expected in a given scenario.

## Table of Contents
1. [Project Structure](#project-structure)
2. [Test Case Design](#test-case-design)
3. [Excel Sheet Format](#excel-sheet-format)
4. [Functional Testing Process](#functional-testing-process)
5. [Test Execution](#test-execution)
6. [Reporting and Tracking](#reporting-and-tracking)
7. [Tools and Technologies](#tools-and-technologies)
8. [Conclusion](#conclusion)

---

## Project Structure

The project includes the following key components:

- **Test Case Excel Sheet**: Contains the test cases, expected results, and test status.
- **Test Environment Setup**: Includes the environment or application where the tests will be executed.
- **Test Logs**: A log to track the execution and results of test cases.

## Test Case Design

Test cases should be designed based on the application’s functional requirements. A good test case includes the following components:

- **Test Case ID**: Unique identifier for the test case.
- **Test Description**: A brief description of the test scenario.
- **Pre-conditions**: Conditions that must be met before the test can be executed.
- **Test Steps**: Detailed steps to follow during the execution.
- **Expected Results**: The expected behavior of the application.
- **Actual Results**: The actual behavior during the test execution.
- **Test Status**: Pass/Fail status of the test case.

## Excel Sheet Format

The **Excel Sheet** will contain a list of test cases with the following columns:

| Column Name        | Description                                             |
|--------------------|---------------------------------------------------------|
| **Test Case ID**    | Unique identifier for the test case.                    |
| **Test Description**| Description of the test case.                           |
| **Pre-conditions**  | Any prerequisites for running the test case.            |
| **Test Steps**      | Detailed steps involved in performing the test case.    |
| **Expected Result** | Expected outcome of the test case.                      |
| **Actual Result**   | Outcome of the test case execution (to be filled in).   |
| **Status**          | Pass or Fail (based on actual vs expected result).      |

### Example Test Case

| Test Case ID | Test Description                | Pre-conditions           | Test Steps                           | Expected Result             | Actual Result | Status |
|-------------|---------------------------------|--------------------------|--------------------------------------|-----------------------------|---------------|--------|
| TC001       | Verify login functionality      | User is on the login page | 1. Enter valid username and password | User successfully logs in    | User logged in | Pass   |
| TC002       | Verify login with incorrect password | User is on the login page | 1. Enter valid username and invalid password | Error message displayed      | Error message displayed | Pass   |

## Functional Testing Process

1. **Prepare Test Environment**:
   - Set up the application in the testing environment.
   - Ensure all necessary configurations are in place.
   
2. **Test Execution**:
   - Retrieve the list of test cases from the Excel sheet.
   - Execute each test case as per the test steps outlined.
   
3. **Capture Results**:
   - For each test case, record the actual results in the "Actual Result" column of the Excel sheet.
   - Mark the test case status as **Pass** or **Fail** based on the comparison between expected and actual results.

4. **Bug Reporting**:
   - For any failed test case, log the issue in the bug-tracking tool.
   - Provide a detailed description of the failure, including steps to reproduce and screenshots if applicable.

## Test Execution

1. Open the Excel test case sheet.
2. Follow the test steps listed in each test case.
3. Update the "Actual Result" and "Status" columns after each test case execution.
4. Ensure that all test cases are covered, including edge cases and boundary conditions.
5. Mark any failed test cases for further investigation and debugging.

## Reporting and Tracking

- Use the **Excel Sheet** as a source of truth to track test execution and outcomes.
- Regularly update the test status and report progress to the project manager or test lead.
- In case of any failed test cases, document the bug in the issue tracker, including:
  - Test Case ID
  - Description of the issue
  - Steps to reproduce
  - Severity of the bug
  - Screenshots (if applicable)

## Tools and Technologies

- **Excel**: For managing test cases, test execution, and tracking.
- **Bug Tracking Tools** (e.g., Jira, Bugzilla): To report and manage defects.
- **Test Environment**: The application or system being tested.

## Conclusion

This **manual testing** process using **Excel** was essential for the project to verifying the **functionality of the system** under test. By organizing test cases and tracking the results, we can ensure the system meets its requirements and works as expected. Regular updates and communication with the testing team will help in identifying and resolving issues promptly.


