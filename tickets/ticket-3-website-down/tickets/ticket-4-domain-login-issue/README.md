# User Unable to Log in to Workstation (Domain Issue)

## Issue Summary
User unable to log into workstation using domain credentials.

## Troubleshooting Steps
- Verified network connectivity using ipconfig /all
- Confirmed system connected to correct domain
- Tested DNS resolution
- Attempted login with known credentials
- Checked for domain trust issues

## Findings
- Network connectivity confirmed
- DNS functioning correctly
- Issue identified as account/domain-related

## Resolution
- Reset user password in Active Directory
- Verified successful login

## Extended Description
User reported inability to log into their workstation using domain credentials. Initial troubleshooting confirmed proper network connectivity and valid IP configuration. DNS resolution was functioning correctly, ruling out network-related issues. Authentication attempts failed, indicating a likely account-related issue. Password was reset in Active Directory, and login was successfully restored.

## Skills Demonstrated
- Active Directory user management
- DNS troubleshooting
- Network validation
- Issue isolation
