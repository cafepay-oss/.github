# Contributing to CafePay

Start with the README in the repository you want to change.
The [backend setup guide](https://github.com/cafepay-oss/cafepal/blob/main/LOCAL_SETUP.md) explains the complete local installation.
Use sample cafe data for development and tests.

## Report a bug

Open an issue in the affected repository.
Describe the steps, expected result, and actual result.
Include the commit, browser, and operating system when relevant.
Use small screenshots or logs that show the problem.
Remove passwords, tokens, phone numbers, receipts, and customer records.

Use the [security reporting guide](SECURITY.md) for security problems.

## Send a change

Create a branch from `main` in your fork.
Keep each change focused on one problem.
Explain the previous behavior and the new behavior in the pull request.
Add a test when the change fixes application behavior.
Update setup instructions when commands or configuration change.
Keep documentation direct and easy to follow.

Run the checks from the repository README.
Build the web app after changes to Vue code, styles, fonts, or build settings.
For payment changes, test failed requests, repeated requests, and requests that arrive at the same time.
State which checks passed and which checks you could not run.

CafePay code uses the MIT license.
By submitting code, you agree to contribute it under that license.
Preserve third-party license notices and include notices for new assets.
