
# Test Strategy
## Practice Software Testing  End-to-End QA Project

### 1. Introduction
This document defines the overall testing approach for the Practice Software Testing (Toolshop) e-commerce application.

**Application URL:** https://practicesoftwaretesting.com/

The objective is to evaluate the application's functionality, usability, reliability, compatibility, security basics, and overall quality.

### 2. Testing Objectives
- Verify that application features work according to expected behaviour.
- Identify and document defects.
- Validate positive, negative, and boundary scenarios.
- Automate important user journeys using Playwright.
- Verify API requests and responses.
- Evaluate accessibility and responsive behaviour.
- Assess performance in an authorised test environment.
- Maintain clear and reproducible test evidence.

### 3. Testing Types and Approach

| Testing Type | Testing Approach |

| Functional Testing | Verify registration, login, search, products, cart, and checkout where supported. |
| Smoke Testing | Check whether essential application features are working. |
| Regression Testing | Re-test existing features after changes. |
| Exploratory Testing | Explore the application to discover unexpected issues. |
| UI Testing | Validate page layouts, buttons, forms, messages, and navigation. |
| Responsive Testing | Check layouts at different screen sizes. |
| Cross-Browser Testing | Check supported browsers such as Chrome, Firefox, and WebKit. |
| API Testing | Validate endpoints, status codes, response bodies, and error handling. |
| Database Testing | Validate stored data and data integrity where database access is available. |
| Performance Testing | Evaluate response times and behaviour using k6 in a controlled environment. |
| Accessibility Testing | Check keyboard navigation, labels, contrast, and WCAG-related issues. |
| Security Testing | Perform basic, safe checks such as input validation and authentication behaviour. |

### 4. Testing Tools

| Tool | Purpose |

| Playwright | UI and API automation |
| JavaScript | Automation programming language |
| Postman | Manual API testing |
| Jira | Defect tracking and management |
| Microsoft Excel | Test cases and test results |
| k6 | Performance testing |
| axe-core | Accessibility checks |
| Git and GitHub | Version control and project documentation |
| GitHub Actions | CI/CD automation |
| SQL | Database validation where accessible |

### 5. Test Environment
- Application: Practice Software Testing (Toolshop)
- Environment: Public demo for authorised functional and manual testing
- Automation: Local development environment using Node.js and Playwright
- Browsers: Chromium, Firefox, and WebKit
  Operating System: macOS
- API: Official application API documentation and available endpoints
- Performance: Local or otherwise explicitly authorised test environment

Load and stress tests will not be performed against the public demo without permission.

### 6. Test Design Techniques
The following test design techniques will be used:

- Equivalence Partitioning
- Boundary Value Analysis
- Positive Testing
- Negative Testing
- Decision Table Testing, where appropriate
- State Transition Testing, where appropriate
- Exploratory Testing

### 7. Defect Management
Defects will be documented with:
- Defect ID
- Defect title
- Description
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Test environment
- Screenshots or other evidence
- Defect status

### 8. Entry Criteria
Testing can begin when:
- The application is accessible.
- The feature under test is available.
- Requirements or expected behaviour are understood.
- Test cases and test data are prepared.
- The required test environment and tools are available.

### 9. Exit Criteria
Testing for a feature or test cycle can finish when:
- Planned test cases have been executed or their status explained.
- Results have been documented.
- Critical defects have been reported and communicated.
- Failed tests have sufficient evidence.
- Relevant regression testing has been completed.
- A test summary has been prepared.

### 10. Risks and Mitigation

| Risk | Mitigation |

| Public demo downtime | Record the issue and retry later. |
| Application changes | Keep test cases and automation updated. |
| Unavailable test accounts | Use permitted test accounts and document limitations. |
| Browser differences | Run tests across selected browser projects. |
| Unstable automated tests | Use reliable locators and Playwright auto-waiting. |
| No database access | Document the limitation and focus on API/UI validation. |
| Performance testing restrictions | Use a controlled, authorised environment. |

### 11. Deliverables
- Test Strategy
- Test Plan
- Test Scenarios
- Test Cases
- Test Execution Results
- Defect Reports
- Automation Scripts
- API Test Collection
- Performance Test Results
- Accessibility Findings
- Final Test Summary Report

### 12. Conclusion
This strategy provides a structured approach to testing the Practice Software Testing application. It will help ensure that testing activities are organised, repeatable, documented, and aligned with professional QA practices.
