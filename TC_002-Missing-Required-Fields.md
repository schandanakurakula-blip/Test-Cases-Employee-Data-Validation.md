# Test Case: Missing Required Fields

- **Test Case ID:** TC_002
- **Module:** Employee Management
- **Test Type:** Negative Testing
- **Priority:** High
- **Execution Status:** PASS

## Objective
Verify that the system prevents saving an employee record when a mandatory field is missing.

## Test Data
- First Name: Blank
- Last Name: Paul
- Employee ID: EMP1002

## Test Steps
1. Open the PIM module.
2. Select Add Employee.
3. Leave the First Name field blank.
4. Enter the Last Name and Employee ID.
5. Click Save.

## Expected Result
The system should display a required-field validation message and prevent saving.

## Actual Result
The system displayed "Required" for the First Name field and did not save the employee record.

## Execution Status
PASS

## Defect ID
N/A
