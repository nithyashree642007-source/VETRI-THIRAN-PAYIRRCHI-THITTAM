# Test Cases

Test Case 1: High Impact Validation

Test: Change Impact to High.

Expected Result: Urgency should be automatically set to High.

Actual Result: Urgency was automatically set to High.

Status: Passed.


Test Case 2: Assigned To Validation

Test: Set Impact to High and leave Assigned To empty.

Expected Result: Incident should not be saved.

Actual Result: Incident was not saved and an error message was displayed.

Status: Passed.


Test Case 3: Reverse Condition

Test: Change Impact from High to Medium.

Expected Result: Assignment Group should no longer be mandatory and Urgency should become editable.

Actual Result: The condition was reversed successfully.

Status: Passed.


Test Case 4: List Edit Restriction

Test: Try to change State directly from the Incident list.

Expected Result: State change should be blocked.

Actual Result: Alert message was displayed and the change was blocked.

Status: Passed.


Test Case 5: Form-Based State Update

Test: Open the Incident form and change State.

Expected Result: State should be updated successfully.

Actual Result: State was updated successfully.

Status: Passed.
