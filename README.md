# MacOS Security Baseline
This is a simple shell script that configures some of the most commonly recommended MacOS security settings that are not enabled by default.

## What It Does:
-   Deletes Saved Wireless Networks.
-   Requires Password Immediately After Sleep.
-   Turns On Firewall.
    -   Enables Stealth Mode.
-   Disables Remote Login
-   Installs Needed System Updates.
    -   Enables Automatic Updates
-   Validates System Integrity Protection is enabled.
-   Enables Full Disk Encryption.

Note: Script Will Prompt For Password If Not Root.

## Usage:
-   Review for your preferences and comment out options **You** don't want.
-   Set `homessid` and `workssid` variable to stop from deleting these!
-   **Warning:** This script does not ask before making changes.

**To Run:**

```
chmod +x security-baseline.sh
./security-baseline.sh
```


## Important Notice
I likely don't know what I am doing, and this could be done faster, better and simpler some other way. These scripts could also break your MacBook and make you cry.
