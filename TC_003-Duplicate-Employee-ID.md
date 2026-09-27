# Test Case: Duplicate Employee ID

- **Test Case ID:** TC_003
- **Module:** Employee Management
- **Test Type:** Negative Testing
- **Priority:** High
- **Execution Status:** PASS

## Objective
Verify that the system prevents duplicate employee IDs.

## Test Data
- Employee ID: EMP1001
- First Name: Priya
- Last Name: Reddy

## Test Steps
1. Open the PIM module.
2. Select Add Employee.
3. Enter employee details using an existing Employee ID.
4. Click Save.

## Expected Result
The system should reject the duplicate Employee ID and display a validation message.

## Actual Result
The system displayed "Employee Id already exists" and rejected the duplicate ID.

## Execution Status
PASS

## Defect ID
N/A
