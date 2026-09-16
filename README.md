# test-cases-login-test-cases.md
test-cases/login-test-cases.md
# Login Test Cases

| TC ID | Test Scenario | Test Data | Expected Result |
|---|---|---|---|
| TC-001 | Valid login | Correct username + password | User should login successfully |
| TC-002 | Wrong password | Correct username + wrong password | Error message should appear |
| TC-003 | Wrong username | Wrong username + correct password | Error message should appear |
| TC-004 | Both fields empty | Blank username + password | Validation message should appear |
| TC-005 | Username empty | Blank username + valid password | Username validation should appear |
| TC-006 | Password empty | Valid username + blank password | Password validation should appear |
| TC-007 | Password masking | Enter password | Password should be hidden/masked |
| TC-008 | Logout | Logged-in user clicks Logout | User should be logged out |
