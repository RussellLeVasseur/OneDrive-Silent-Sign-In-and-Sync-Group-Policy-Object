# Onedrive-Silent-SignIn-and-Sync-Group-Policy-Object
A group policy that successfully signs users in silently and syncs their known folders.


Configure a group policy exactly as shown in the provided PDF. If a user signs out, all you simply need to do is set the ClientEverSignedIn and SilentBusinessConfigCompleted Current User registry keys back to 0 and it will auto log them in again. I suggest monitoring login status with a powershell script and setting those keys to 0 automatically when needed. 
