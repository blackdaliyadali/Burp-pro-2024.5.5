# Burp-pro-
Burpsuite Professional Version -202x

Overview:--

Burp Suite Professional is the web security tester's toolkit of choice. Use it to automate repetitive testing tasks - then dig deeper with its expert-designed manual and semi-automated security testing tools. Burp Suite Professional can help you to test for OWASP Top 10 vulnerabilities - as well as the very latest hacking techniques. Advanced manual and automated features empower users to find lurking vulnerabilities more quickly. Burp Suite is designed and used by the industry's best.

##################################################################################################################################################################################

Linux installation:------------------------

sudo apt update && sudo apt install -y wget && wget -qO- https://raw.githubusercontent.com/xiv3r/Burpsuite-Professional/main/install.sh | sudo bash

Run:---

burpsuitepro

##################################################################################################################################################################################

Setup Licenses:--

Note: Copy the license from loader to the burpsuite > manual activation > copy burpsuite request key to loader request > copy response key to the burpsuite.

##################################################################################################################################################################################

Shortcut Launcher - (xfce)
right click the desktop -> create a launcher name it Burpsuite Professional, add command burpsuitepro and select burpsuite community icon.

##################################################################################################################################################################################

Windows Installation:-----


Make a Burp directory name in C Drive for faster access.

Download install.ps1 and extract move the file inside to C:\Burp

Open Powershell as administrator and execute below command to set Script Execution Policy.

"Set-ExecutionPolicy -ExecutionPolicy bypass -Scope process"

Inside PowerShell go to cd C:\Burp

Now Execute install.ps1 file in Powershell to Complete Installation.

"./install.ps1"

Change the icon of Burp-Suite-Pro.vbs to the given icon

Create a shortcut to Desktop. Right Click over Burp-Suite-Pro.vbs Go to Shortcut tab, and below there is Change Icon tab

Click there and choose the burp-suite.ico from C:\Burp\

For Start Menu Entry, copy Burp-Suite-Pro.vbs file to

C:\ProgramData\Microsoft\Windows\Start Menu\Programs\
