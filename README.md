# LocationHistory PowerShell Module

This PowerShell module is based on the `cd.psm1` PSCX (PowerShell community extensions) module written by Keith Hill, with some enhancements and bug fixes.

This module provides an extended `Set-Location` replacement function called `Set-LocationEx` that maintains a location history, allowing easy navigation to previous locations.

When you load this module, it sets the `cd` alias to the `Set-LocationEx` function.

After installing this module, I recommend adding `Import-Module LocationHistory` to your PowerShell profile.

You can install this module in any of the following ways:

1. Download and run the Windows installer. This is the easiest way, and is the only way to install the PowerShell 2.0 version. The installer also installs the module for the 32-bit version of PowerShell if you are running a 64-bit Windows version.

2. Run `Install-Module` from an elevated PowerShell window to install it from the default repository. See https://www.powershellgallery.com/packages/LocationHistory/. I believe `Install-Module` first became available in PowerShell v5.
