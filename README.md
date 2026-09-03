# OpenCart - E-Commerce Website Testing

## Project Overview

A manual testing project performed on the OpenCart e-commerce web application to validate core functionality, user workflows, and cross-functional business flows.

## Testing Scope

The application was tested across the following functional areas:

- Login
- Registration
- Product Search
- Shopping Cart
- Checkout
- Logout
- Cross-Functional Workflows

## Testing Coverage

- 58 Test Scenarios
- 99 Test Cases
- Functional and negative test scenarios
- Cross-functional and end-to-end user flows
- Defect identification and reporting

## Testing Types

- Functional Testing
- Regression Testing
- Smoke Testing
- Exploratory Testing
- End-to-End Testing
- Negative Testing
- Cross-Browser / Compatibility Testing

## Key Test Scenarios

### Login
- Valid and invalid login credentials
- Field validation
- Email and password validation
- Forgot Password functionality
- Password masking
- Session management
- Security validation
- Browser compatibility

### Registration
- Valid and invalid registration data
- Duplicate email validation
- Mandatory field validation
- Email format validation
- Password strength
- Special characters
- Maximum field length
- Privacy Policy validation

### Search
- Valid and invalid search keywords
- Special characters and numeric input
- Partial keyword search
- Case sensitivity
- Leading/trailing spaces
- Empty search
- Search result relevance

### Shopping Cart
- Add, remove, and update products
- Multiple product handling
- Cart persistence after refresh
- Cart persistence after logout/login
- Required product option validation
- Price calculation

### Checkout
- Valid checkout flow
- Mandatory field validation
- Invalid pincode validation
- Checkout without products
- Payment method validation
- Checkout cancellation
- Page refresh during checkout
- Order confirmation
- Duplicate order prevention

### Logout & Session Management
- Successful logout
- Restricted page access after logout
- Browser back-button behavior
- Multiple-tab session handling
- Cart persistence after logout/login
- Session validation

### Cross-Functional Testing
- Search → Add to Cart → Checkout
- Add to Cart → Logout → Login → Verify Cart
- Multiple-tab cart handling
- Browser refresh during transaction
- Network interruption during checkout

## Defect Management

Defects identified during testing were documented with reproducible steps, expected results, actual results, severity/priority, and supporting information.

Defects were reported and tracked using Jira.

## QA Deliverables

- Test Plan
- Test Scenarios
- Test Cases
- Requirements Traceability Matrix (RTM)
- Bug Reports
- Test Execution Report
- Test Summary Report

## Project Structure

| Folder | Description |
|---|---|
| `01-Test-Plan` | Test planning and scope |
| `02-Test-Scenarios` | Test scenarios identified for testing |
| `03-Test-Cases` | Detailed test cases and execution results |
| `04-RTM` | Requirement-to-test-case traceability |
| `05-Bug-Reports` | Defects identified during testing |
| `06-Test-Execution` | Test execution results |
| `07-Test-Summary` | Overall testing summary and results |

## Tools & Technologies

- Manual Testing
- Jira
- Microsoft Excel
- Microsoft Word
- Web Browser

## Project Status

Completed
