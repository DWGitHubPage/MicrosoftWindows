If you forgot admin domain password on a server such as Windows Server 2016.
Came across someone asking what to do on Reddit and someone responded with the below which worked flawlessly.


This is assuming you have the Bitlocker key, or you don’t use Bitlocker.

Download server 2016 ISO > attach to VM > reboot into ISO > Repair your Computer > Troubleshoot > Command prompt

cd C:\Windows\System32

ren osk.exe osk.old

copy C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe osk.exe

Reboot the server, launch the on screen keyboard and Powershell will open

Net user Administrator PASSWORD

Make sure you reverse the file changes after.

And set up a second Domain Admin.
