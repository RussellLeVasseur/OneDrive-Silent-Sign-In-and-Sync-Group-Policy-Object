# Onedrive-Silent-SignIn-and-Sync-Group-Policy-Object
A group policy that successfully signs users in silently and syncs their known folders.


Configure a group policy exactly as shown in the provided PDF.

- If a user signs out of onedrive, you can force a silent re-login again by setting the OneDrive ClientEverSignedIn and SilentBusinessConfigCompleted registry keys back to 0. You can use [this companion script](https://github.com/RussellLeVasseur/OneDrive-Health-Check) or write your own. 
