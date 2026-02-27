# Registration Form Checklist – Demo Site

> This checklist contains test cases for the registration form of a demo web application.  
> Priority indicates the importance of each test. Failed tests are included to demonstrate bug reporting skills.

| #  | Checklist item | Priority | Result | Comment |
|----|----------------|----------|--------|---------|
| 1  | User is able to register after filling in all required fields with valid data after clicking [Register] button | Critical | Passed | |
| 2  | Verify that an error message is displayed when the email address does not contain `@` | High | Passed | |
| 3  | Verify that an error message is displayed when the email address does not contain a domain | High | Passed | |
| 4  | Verify that an error message is displayed when the email address contains spaces | High | Passed | |
| 5  | Verify that an error message is displayed when the email address does not contain a username (e.g. `@gmail.com`) | High | Passed | |
| 6  | Verify that the email field accepts a valid email format (e.g. `user@example.com`) | High | Passed | |
| 7  | Verify that the user cannot register a second account using the same valid email address | Critical | Passed | |
| 8  | Verify that the system displays an error message when a duplicate email address is used during registration | High | Passed | |
| 9  | Verify that an error message is displayed when the password contains 7 characters | High | Failed | Password accepted. UI allows 5-40 characters, requirement specifies 8 characters |
| 10 | Verify that the user can register an account when the password contains exactly 8 characters and meets all complexity requirements | High | Passed | |
| 11 | Verify that the user can register an account when the password contains more than 8 characters (e.g. 9 characters) and meets all complexity requirements | High | Passed | |
| 12 | Verify that an error message is displayed when the password contains at least 8 characters but does not contain a lowercase letter | High | Failed | Password accepted without required lowercase letter. Requirement JS-REQ-004 not enforced |
| 13 | Verify that an error message is displayed when the password contains at least 8 characters but does not contain an uppercase letter | High | Failed | Password accepted without required uppercase letter. Requirement JS-REQ-004 not enforced |
| 14 | Verify that an error message is displayed when the password contains at least 8 characters but does not contain a digit | High | Failed | Password accepted without required digit. Requirement JS-REQ-004 not enforced |
| 15 | Verify that an error message is displayed when the password contains at least 8 characters but does not contain a special character | High | Failed | Password accepted without required special character. Requirement JS-REQ-004 not enforced |
| 16 | Verify that the user can register an account with a password of exactly 8 characters, including lowercase, uppercase, digit, and special character | High | Passed | |
| 17 | Verify that an error message is displayed when the value in the "Repeat password" field does not match the "Password" field | High | Passed | |
| 18 | Verify that the “Show password advice” toggle is turned on by default when the registration page is opened | High | Failed | The toggle is OFF by default, but requirement JS-REQ-006 specifies it should be ON |
| 19 | Verify that the “Show password advice” toggle displays all password requirements when it is turned on | High | Passed | |
| 20 | Verify that the "Security Question" dropdown exists on the registration page | High | Passed | |
| 21 | Verify that the "Security Question" dropdown contains security question options | High | Passed | |
| 22 | Verify that the user can select an option from the dropdown list | High | Passed | |
| 23 | Verify that the fields “Email”, “Password”, “Repeat Password”, “Security Question”, and “Answer” are required to register an account | Critical | Passed | |
| 24 | Verify that the user can successfully register when all required fields are filled | Critical | Passed | |
| 25 | Verify that clicking the “Already a customer?” link navigates the user to the login screen | High | Passed | |
