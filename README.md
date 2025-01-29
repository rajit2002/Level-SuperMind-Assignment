# Level-SuperMind-Assignment
Level SuperMind App Testing Assignment

    Project Overview :
This project involves manual testing of the Level SuperMind app to identify and document bugs. The key focus areas were Signup, Login, Meditation Feature, and Notification Feature. The purpose was to ensure that these functionalities are working as expected and identify any discrepancies.

Scenarios Tested : 

1. Signup Feature
Verified the flow for new users to sign up using email and phone number.
Ensured proper validation for input fields such as email, phone number, and OTP.

2. Login Feature
Tested the login functionality with valid and invalid credentials.
Checked the behavior for expired OTP scenarios using both email and phone number.

3. Meditation Feature
Validated the functionality of accessing meditation sessions.
Verified that users can navigate through the meditation library without any issues.

4. Notification Feature
Tested the visibility and accessibility of the notification icon.
Checked the flow for receiving and interacting with notifications.


Bugs Identified : 

Bug 1: Successful Login with Expired OTP (Email)

Steps to Reproduce:
Open the app and navigate to the login page.
Enter a valid email and request an OTP.
Wait until the OTP expires.
Enter the expired OTP and attempt to log in.

Expected Behavior: The app should display an error message stating the OTP has expired.
Actual Behavior: Login is successful even with an expired OTP.

Severity: Critical



Bug 2: Successful Login with Expired OTP (Phone Number)

Steps to Reproduce:
Open the app and navigate to the login page.
Enter a valid phone number and request an OTP.
Wait until the OTP expires.
Enter the expired OTP and attempt to log in.

Expected Behavior: The app should display an error message stating the OTP has expired.
Actual Behavior: Login is successful even with an expired OTP.

Severity: Critical


Bug 3: Difficulty Locating Notification Icon

Steps to Reproduce:
Open the app and navigate through the dashboard.
Look for the notification icon.

Expected Behavior: The notification icon should be prominently visible and easy to locate.
Actual Behavior: The notification icon is either missing or difficult to find.

Severity: Major




Test Artifacts :

Test Plan: Defined the scope, approach, and resources for testing the Level SuperMind app.
Bug Report: Documented the identified bugs with steps to reproduce, expected vs. actual behavior, and severity levels.
Test Cases: Created detailed test cases for Signup, Login, Meditation, and Notification features to ensure comprehensive coverage.


Conclusion :
The manual testing process helped identify critical and major issues in the Level SuperMind app. Addressing these bugs will enhance the app's usability and reliability for end users.




