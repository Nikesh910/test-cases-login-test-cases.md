# Login Test Cases

| TC ID | Test Scenario | Test Data | Expected Result |
|---|---|---|---|
| TC-001 | Valid login | Correct username + password | User should login successfully |
| TC-002 | Wrong password | Correct username + wrong password | Error message should appear |
| TC-003 | Wrong username | Wrong username + correct password | Error message should appear |
| TC-004 | Both fields empty | Blank username + password | Validation message should appear |
| TC-005 | Username empty | Blank username + valid password | Username validation should appear |
| TC-006 | Password empty | Valid username + blank password | Password validation should appear |
| TC-007 | Remember me | Valid username + password + Remember Me | User should remain logged in |
