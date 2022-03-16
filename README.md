# Network-Connection-Notify
The powershell script using the winform that will notify the user by voice / desktop notification when the network connection is changed. This script can also be used to make a continuous network port probing at Layer-4 connection (same as telnet). But, you might have changes of getting blocked from the destination endpoint/server if you set the interval to a low value (eg: 1 sec).
Since it's written in Powershell Studio 2017, I include both the .ps1 file and .psf file and the packaged version. Please see the relevant executable under /bin/* folder.
You can edit/modify the script according to your needed (including the replacing any icons) except modifying the 'The Scripting House' logo itself.
The default value in Endpoint URL (dns.google) is given just an example purpose only.
