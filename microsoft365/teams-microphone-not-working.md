# Issue Summary
User unable to use microphone during Microsoft Teams calls.

# Environment
- Windows 10 laptop
- Microsoft Teams desktop app
- Built-in laptop microphone

# User Description
"People can’t hear me on Teams, but I can hear them. The mic was working before."

# Troubleshooting Steps
- Confirmed microphone was not muted in Teams
- Checked Windows Sound Settings to ensure the correct input device was selected
- Tested microphone using Windows "Test your microphone" feature
- Restarted Microsoft Teams
- Closed other apps that might be using the microphone (e.g., Zoom, browser tabs)
- Granted microphone permissions to Teams in Windows Privacy Settings
- Restarted the laptop and tested again

# Resolution
Microphone permissions were disabled for Teams. Enabling microphone access in Windows Privacy Settings resolved the issue.

# Root Cause
Teams did not have permission to access the microphone after a recent Windows update.

# Notes
Advised user to check microphone permissions again if the issue reoccurs after updates.
