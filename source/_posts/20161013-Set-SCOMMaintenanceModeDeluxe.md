---
title: 'Set-SCOMMaintenanceMode Deluxe ed. [#opsmgr #powershell]'
s: Set-SCOMMaintenanceModeDeluxe
date: 2016-10-13 00:21:03
tags:
    - Powershell
    - OpsMgr 2012 R2
    - Gist
categories:
    - Microsoft
    - OpsMgr 2012
---

# Untimely, perhaps

While most of us are waiting for SCOM 2016 RTM to be generally available i've completely forgot to blog about my little `Set-SCOMMaintenanceModeDeluxe.ps1` script I wrote a while ago.

It is pretty much a small extension to the regular `Set-SCOMMaintenanceMode` cmdlet that allows you to set Computers, Groups or specific Windows Services into maintenance mode.
I have yet to make it a proper module (although I have promised myself to do so) so you'd still have to manually download the script and execute it the old-fashioned way.

I've uploaded it as a public gist on github, so feel free to add adapt it to your needs.

# Here's the gist

{% gist  b3f044aa77894ed80d82f8849a48035b Set-SCOMMaintenanceModeDeluxe.ps1 %}

