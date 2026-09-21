# Bug Report

## Summary
The application crashes when the user attempts to submit a form with an empty required field.

## Severity
High

## Priority
Medium

## Environment
- Operating System: Windows 11
- Browser: Chrome 126
- App Version: 1.2.3

## Steps to Reproduce
1. Open the application homepage.
2. Navigate to the contact form.
3. Leave the required "Email" field blank.
4. Click the "Submit" button.

## Expected Result
The form should display a validation message and prevent submission until the field is filled.

## Actual Result
The application throws an error and the page becomes unresponsive.

## Logs
- Error message: "UnhandledException: Cannot read properties of undefined"
- Timestamp: 2026-09-21 10:15 AM

## Additional Notes
This issue appears to affect all users who attempt to submit incomplete forms.
