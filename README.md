# AJIO Manual Testing Project

## Project Overview

This repository contains a manual testing project carried out on the **AJIO e-commerce web application**.

The project focuses on testing customer-facing functionality from a manual QA perspective, documenting test cases, recording execution results, identifying defects, and preparing supporting QA documentation.

## Application Details

- **Application:** AJIO
- **Application Type:** Web Application
- **Domain:** E-Commerce
- **Testing Type:** Manual Testing
- **Browser Used:** Brave Browser
- **Operating System:** Windows
- **Test Environment:** Desktop/Laptop
- **Browser Zoom:** 100% where applicable

## Modules Tested

The following modules were covered during testing:

- Home
- Login
- Search
- Filters & Sorting
- Product
- Cart
- Checkout
- UI / Responsive

## Test Execution Summary

A total of **85 test cases** were executed.

| Result | Count |
|---|---:|
| Total Test Cases | 85 |
| Passed | 79 |
| Failed | 6 |
| Not Executed | 0 |

The failed test cases were reviewed to identify unique defects. Similar failures were consolidated before preparing the bug report.

## Defects Identified

The following unique defects were documented:

1. **Invalid 10-digit mobile number is accepted**
   - A 10-digit number starting with `1` was accepted without a validation message.

2. **Special-character validation is inconsistent across address fields**
   - The Landmark field rejected special characters, while values such as `@@@@@` were accepted in some other address fields.

3. **Horizontal scrollbar appears on the listing/product page**
   - A horizontal scrollbar was observed at the bottom of the listing/product page at the tested viewport.

4. **Visit AJIOLUXE button is partially cut off at a reduced desktop viewport**
   - The button was partly cut off on the right side of the header at the tested reduced viewport.

## QA Documents

The repository contains the following supporting documents:

### Project Documentation
- Project Overview
- Software Requirements Specification (SRS)
- Test Plan
- Test Summary Report

### Test Artifacts
- Manual Test Cases
- Bug Report
- Future Enhancements

## Testing Approach

The project followed a basic manual QA workflow:

```text
Requirement Understanding
        ↓
Test Planning
        ↓
Test Case Preparation
        ↓
Test Execution
        ↓
Pass / Fail Recording
        ↓
Failed Test Review
        ↓
Bug Identification
        ↓
Bug Reporting
        ↓
Retesting / Closure
```

Testing was performed from a customer-facing perspective by comparing the observed actual behavior with the expected behavior documented in the test cases.

## Future Enhancements

Some observations were recorded separately as future enhancements rather than defects because they were not treated as confirmed requirement violations:

- Product details page layout could use screen space more effectively.
- Written customer reviews could be provided in addition to ratings and rating distribution.
- The product-page sidebar could be considered for sticky behavior to improve usability.

## Tools Used

- Microsoft Excel
- Microsoft Word
- Brave Browser
- GitHub

## Project Purpose

This project was created as a **Manual QA portfolio project** to demonstrate practical understanding of:

- Test case design
- Functional testing
- UI testing
- Responsive testing
- Test execution
- Defect identification
- Bug reporting using Excel
- QA documentation
- Traceability between test cases and defects

## Disclaimer

This is an independent manual testing portfolio project created for learning and demonstration purposes. It is not an official QA report or employment experience for AJIO.

## Author

**Fizza Fathima A.**
