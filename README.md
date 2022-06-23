# machinesetup
Using Boxstarter and Choco to setup a basic machine

From Powershell on the new machine.

Step 1: . { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force

Step 2: Install-BoxstarterPackage -PackageName https://gist.githubusercontent.com/bwilsonms/d79cdbdc7707dea921c0118184d35ae5/raw/d695cb8ff7824219dafc8c907166efe9d4c5d2e4/bwsetup.txt -DisableReboots



Reference: https://boxstarter.org/learn/weblauncher

