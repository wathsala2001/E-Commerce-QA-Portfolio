# E-Commerce QA Testing Portfolio

## Project Overview

This project demonstrates my practical skills in **Manual Software Testing** using the Automation Exercise e-commerce website.

The project covers the complete manual testing process, including requirement analysis, test scenario creation, test case design and execution, defect reporting, test summary reporting, and test evidence.

## Application Under Test

**Automation Exercise** — E-commerce practice website

## Testing Type

- Manual Testing
- Functional Testing
- Negative Testing
- UI Testing
- Validation Testing
- Regression Testing considerations

## Project Structure

| Folder | Description |
|---|---|
| `01-Requirement-Analysis` | Analysis of the application requirements and testable functionality |
| `02-Test-Scenarios` | High-level test scenarios for major application features |
| `03-Test-Cases` | Detailed manual test cases with expected and actual results |
| `04-Bug-Reports` | Documented defects identified during negative testing |
| `05-Test-Summary-Report` | Summary of testing activities, results, defects, and recommendations |
| `06-Screenshots-Evidence` | Screenshot evidence for passed tests and identified defects |

## Features Tested

The testing covered major e-commerce functions including:

- Product browsing and product details
- Product search
- Category and brand filtering
- Shopping cart functionality
- User registration
- Login validation
- Contact form submission
- Product review functionality

## Test Execution Summary

| Metric | Result |
|---|---:|
| Documented Test Cases | 35 |
| Passed | 35 |
| Failed | 0 |
| Not Executed | 0 |
| Pass Percentage | 100% |
| Additional Defects Found | 2 |

The two defects were discovered during **additional negative testing** and were documented separately from the 35 executed test cases.

## Defects Identified

### BUG-001 — Product Can Be Added to Cart with Quantity 0

**Severity:** Medium  
**Priority:** High  
**Status:** Open

The application allows a product with quantity `0` to be added to the shopping cart instead of preventing the action or displaying a validation message.

### BUG-002 — Product Can Be Added to Cart with Negative Quantity

**Severity:** High  
**Priority:** High  
**Status:** Open

The application accepts a negative product quantity and adds the product to the cart instead of validating that the quantity must be greater than zero.

## Tools Used

- Automation Exercise
- Microsoft Excel
- Microsoft Word
- Visual Studio Code
- Git
- GitHub

## Skills Demonstrated

- Requirement Analysis
- Test Scenario Design
- Test Case Design
- Test Execution
- Positive and Negative Testing
- Defect Identification
- Bug Reporting
- Test Evidence Documentation
- Test Summary Reporting
- Git and GitHub

## Key Learning

This project provided hands-on experience with a structured manual QA workflow, from understanding requirements and designing tests to executing test cases, identifying defects, documenting evidence, and preparing a final test summary.

## Author

**Wathsala Kithulgala**

QA / Software Testing Portfolio Project
