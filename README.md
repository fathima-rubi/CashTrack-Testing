# CashTrack Testing

## Project Overview
CashTrack is an Android mobile application for personal finance management.
This project contains the complete manual testing documentation for the 
CashTrack app including requirement analysis, test planning, test case 
design, execution, and defect reporting.

## Application Under Test
- **App Name:** CashTrack
- **Version:** 1.0.0
- **Platform:** Android
- **Device:** Vivo Y29 (Android 16)

## Modules Tested
- Category Module
- Transaction Module

## Testing Types
- Functional Testing
- Validation Testing
- UI Testing
- Persistence Testing

## Test Summary
| Metric | Count |
|--------|-------|
| Total Test Cases | 27 |
| Passed | 24 |
| Failed | 3 |
| Pass Percentage | 88.89% |
| Total Defects | 3 |

## Defects Found
| Bug ID | Summary | Severity |
|--------|---------|----------|
| BUG-001 | Category name accepts whitespace-only values | Medium |
| BUG-002 | Transaction amount accepts zero value | High |
| BUG-003 | Transaction amount accepts negative values | Critical |

## Tools Used
- **Test Management:** Jira
- **Documentation:** Google Sheets
- **Bug Tracking:** Jira

## Documents Included
- Requirement Document
- Test Plan
- Test Scenarios
- Test Cases
- RTM (Requirement Traceability Matrix)
- Test Execution Report
- Test Summary Report
