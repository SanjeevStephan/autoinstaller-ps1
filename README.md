# autoinstaller-winget
Install Software Packages using winget tool on the window 11 in powershell from the json-list

```

    _         _          ___           _        _ _
   / \  _   _| |_ ___   |_ _|_ __  ___| |_ __ _| | | ___ _ __
  / _ \| | | | __/ _ \   | || '_ \/ __| __/ _` | | |/ _ \ '__|
 / ___ \ |_| | || (_) |  | || | | \__ \ || (_| | | |  __/ |
/_/   \_\__,_|\__\___/  |___|_| |_|___/\__\__,_|_|_|\___|_|

                               Created By Sanjeev Stephan Murmu
.SYNOPSIS
    Auto-Installer for Windows 11 using winget

.DESCRIPTION
    This Script will install the following software packages on the window system using [winget] window-package-installer
Name                                     Id                        Version          Match                 Source
-----------------------------------------------------------------------------------------------------------------------

PowerShell                                      Microsoft.PowerShell            7.3.4.0                             winget
OpenSSH Beta                                    Microsoft.OpenSSH.Beta          9.2.2.0                             winget
Microsoft Visual Studio Code                    Microsoft.VisualStudioCode      1.78.2          Moniker: vscode     winget
Windows Terminal                                Microsoft.WindowsTerminal       1.16.10261.0    Moniker: terminal   winget
Microsoft Edge                                  Microsoft.Edge                  113.0.1774.57                       winget
Power Automate for desktop                      Microsoft.PowerAutomateDesktop  2.32.111.23124                      winget
PowerToys (Preview)                             Microsoft.PowerToys             0.70.1                              winget
Microsoft Visual C++ 2015-2022 Redistributable… Microsoft.VCRedist.2015+.x64    14.36.32532.0                       winget

Git                                             Git.Git                      2.41.0                                 winget
Python 3.11                                     Python.Python.3.11           3.11.3          Command: python        winget
Brave                                           Brave.Brave                  114.1.52.122                           winget
Node.js LTS                                     OpenJS.NodeJS.LTS            18.16.0         Tag: nodejs            winget
Notion                                          Notion.Notion                2.0.41                                 winget
Oracle VM VirtualBox                            Oracle.VirtualBox            7.0.8                                  winget

.NOTES
    -> Author : Sanjeev Stephan Murmu
    -> Created On : 8th June 2023
    -> Learn More About Winget (https://learn.microsoft.com/en-us/windows/package-manager/winget/)
 
```
