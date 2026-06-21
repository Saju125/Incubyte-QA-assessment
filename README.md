# Incubyte QA Assessment – Gmail Compose & Send

## Objective
Test the **Compose** functionality of Gmail by sending an email with:
- **Subject:** `Incubyte`
- **Body:** `QA test for Incubyte`

## Deliverables
| File | Description |
|---|---|
| `Incubyte_Gmail_Compose_TestCases_Sajid.xlsx` | Test cases for the Gmail Compose feature, covering both **Traditional** and **BDD** styles, with **Positive** and **Negative** scenarios |

## Test Case Sheet Structure

### Sheet 1: Traditional Test Cases
Columns: `Test Case ID | Module | Test Case Title | Type | Priority | Preconditions | Test Steps | Test Data | Expected Result`

### Sheet 2: BDD Test Cases
Columns: `Test Case ID | Feature | Scenario | Type | Priority | Given | When | Then`

## How These Were Derived
Test cases were designed by analyzing the Gmail Compose workflow end-to-end — input validation (To/Cc/Bcc, Subject, Body), core happy-path behavior, attachment handling, draft persistence, and resilience/error handling — using the assignment's required Subject (`Incubyte`) and Body (`QA test for Incubyte`) as the primary test data.

## Tools Used
- Manual test design based on Gmail's web UI behavior
- Microsoft Excel (.xlsx) for test case documentation

## Author
Sajid — QA Engineer
