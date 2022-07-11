# Basic Machine Setup
Using Boxstarter and Choco to setup a basic machine

From an Administrator PowerShell on the new machine.

Step 1: . { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force

Step 2: Install-BoxstarterPackage -PackageName https://gist.githubusercontent.com/bwilsonms/d79cdbdc7707dea921c0118184d35ae5/raw/d7f26ec8397371a3754013f61b43dd412742c05f/bwsetup.txt -DisableReboots

Reference: https://boxstarter.org/learn/weblauncher
