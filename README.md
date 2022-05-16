# OneDrive Silent SignIn and Sync Group Policy Object
A group policy that successfully signs users in silently and syncs their known folders.

## How to Use
Configure a group policy exactly as shown in the provided PDF.

## Features
- This configuration will silently sign in users and move known Windows folders (Desktop, Documents, Pictures) to the OneDrive directory.
- If a user signs out of OneDrive, you can encourage a silent re-login again by setting the OneDrive ClientEverSignedIn and SilentBusinessConfigCompleted registry keys back to 0. You can use [this OneDrive Health Check companion script](https://github.com/RussellLeVasseur/OneDrive-Health-Check) or write your own.

## Requirements
- OneDrive Installed.
- User domain accounts pre-configured to Microsoft 365 and OneDrive.
- Microsoft Active Directory Domain.
