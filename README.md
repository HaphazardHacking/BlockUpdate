# BlockUpdate
.vbs script to block specific updates 

Current functionality:
* Actively perform a check for updates against WUA
* Compare KB numbers against installed or pending updates
* Hide specified KB numbers updates, preventing them from being installed



Updates can't be uninstalled using the WUA API unless the updates were initially deployed with WSUS.
I found this out too late and can't be assed to rewrite the whole thing in PowerShell, hence the wonky .ps1

Still to be done:
* Write the uninstaller .ps1
* Complete the uninstaller function
* Re-order 'Main' to account for the uninstaller
* Add arguments to allow options for unattended execution
* Re-write entirely in powershell
