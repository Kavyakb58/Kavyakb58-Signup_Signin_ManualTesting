# Sign In & Sign Up Testing for BrowserStack
This project has **manual test cases** for the **Sign In** and **Sign Up** features on the **BrowserStack** website. The tests help make sure everything works correctly for users to register, log in, and reset their password.

## What’s Tested:

### Sign Up:
- Check if the "Sign Up" button works.
- Test if a user can register with valid details.
- Ensure email and password rules are followed.
- Show an error for duplicate emails.
- Show a success message after registration.

### Sign In:
- Check if the "Sign In" button works.
- Test if login works with correct details.
- Show an error for wrong email or password.
- Test the "Forgot Password" link.
- Ensure login works after password reset.

### Negative Tests:
- Show errors for invalid emails or passwords.
- Ensure empty or mismatched fields show an error.

## Test Details:

Each test includes:
- **Test Case ID**
- **Test Steps**
- **Expected Result**
- **Actual Result**
- **Status** (Pass/Fail)

## Tools Used:
- **Platform**: BrowserStack (Web)
- **Browsers**: Chrome, Firefox, Safari, Edge

## How to Run the Tests:
1. **Clone** this repo to your computer.
2. Review the test cases.
3. Manually test them on the **BrowserStack website**.
4. Record the test results.
