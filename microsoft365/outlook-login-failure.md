# Issue Summary
User unable to log into Outlook after changing their password.

# Environment
- Windows 11 laptop
- Microsoft 365 (Outlook desktop app + web version)

# User Description
"I changed my password yesterday and now Outlook keeps asking for the old one."

# Troubleshooting Steps
- Confirmed the user recently changed their password
- Asked the user to try logging into Outlook Web (office.com)
- Verified that login works on the web version
- Closed Outlook desktop app completely
- Removed old saved credentials from Windows Credential Manager
- Reopened Outlook and entered the new password
- Confirmed that emails started syncing normally

# Resolution
Removing old credentials and signing in again with the new password resolved the issue.

# Root Cause
Outlook was still using cached credentials from before the password change.

# Notes
Advised user to update the password on all devices to avoid repeated prompts.
