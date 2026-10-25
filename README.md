# SauceDemo — Manual QA Testing Portfolio

Project Overview
This project demonstrates manual software testing skills through functional testing of the SauceDemo web application.
The project focuses on validating key e-commerce user flows, including authentication, product browsing, sorting, shopping cart operations, and checkout.
Application Under Test: https://www.saucedemo.com/
Testing Type: Manual Functional Testing

Objectives

- Design and execute manual test cases.
- Validate positive and negative scenarios.
- Verify form validation and error messages.
- Test shopping cart and checkout functionality.
- Document test results and potential defects.
- Maintain clear and structured QA documentation.

Scope of Testing

The following areas were tested:

- Login with valid and invalid credentials.
- Login validation for empty fields.
- Login behavior for a locked-out user.
- Product listing and product information.
- Product sorting by name and price.
- Adding and removing products from the cart.
- Cart contents and navigation.
- Checkout form validation.
- Checkout overview and price calculations.
- Order completion and confirmation.

Test Deliverables

| Deliverable                                 | Description                                                       |
|---------------------------------------------|-------------------------------------------------------------------|
| [Test Plan](saucedemo-manual-qa/test-plan.md)         | Testing scope, objectives, approach, and limitations              |
| [Test Cases](saucedemo-manual-qa/test-cases.md)      | 22 manual functional test cases with execution results            |
| [Bug Reports](saucedemo-manual-qa/bug-reports.md)   | Documentation of two observations requiring further investigation |

Test Execution Summary

A total of 22 test cases were executed.

| Status       | Count |
|--------------|-------|
| Pass         | 21    |
| Fail         | 1     |
| Blocked      | 0     |
| Not Executed | 0     |
| Total        | 22    |

TC-007 is marked as Failed because of observations concerning product text on the Products page. The observations are documented in the Bug Reports file and require confirmation against the expected product content before they can be classified as confirmed defects.

Tools and Techniques

- GitHub — QA documentation and portfolio management.
- Markdown — Structured test documentation.
- Manual Testing — Functional, positive, and negative test scenarios.
- Bug Reporting — Reproduction steps, expected and actual results, and supporting evidence.

What I Learned

Through this project, I practiced:

- Writing structured manual test cases.
- Defining expected and actual results.
- Executing test cases and assigning Pass/Fail statuses.
- Testing validation messages and user workflows.
- Documenting potential defects clearly.
- Organizing QA deliverables in a GitHub repository.

Notes
This is a portfolio project conducted against a publicly available demo application. The findings reflect the observations recorded during manual test execution and are not claims about a production system.

Author
Artemis Papavasileiou
