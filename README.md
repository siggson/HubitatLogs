# HubitatLogs
HubitatLogs.exe is a log and event viewer for Hubitat Elevation development. 
The viewer that is integrated into Hubitat is resource limited and does not 
have the capability to view large amounts of logging output for long lengths 
of time. Several times I have been using the integrated viewer only have the 
the displayed info start disappearing because of limited resources.  I have 
been told to just limit the log info being produced by my automations and I
will have a better chance at loosing infomation on the display. This is not 
the method I want use in my development so I wrote a Windows program to read 
the WebSockets for Logs and Events. Helog is a descent program that uses 
these sockets to archive the info on the PC but I wanted a real time solution. 
With HubitatLogs.exe you can log for weeks and probably not put a dent into 
the available memory on a PC.
