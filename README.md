# HubitatLogs
HubitatLogs.exe is a Windows PC based log and event viewer for Hubitat Elevation development. 
The viewer that is integrated into Hubitat is resource limited and does not 
have the capability to view large amounts of logging output for long lengths 
of time. Several times I have been using the integrated viewer only to have the 
the displayed info start disappearing because of limited resources.  I have 
been told to just limit the log info being produced by my automations and I
will have a better chance at not loosing infomation on the display. This is not 
the method I want use in my development so I wrote a Windows program to read 
the WebSockets for Logs and Events. Helog is a descent program that uses 
these sockets to archive the info on the PC but I wanted a real time solution. 
With HubitatLogs.exe you can log for weeks and probably not put a dent into 
the available memory on a PC. A list of some of the capabilities of HubitatLogs 
is as follows:

  * Provides seperate windows for logs and events
  * You can have seperate windows for logging different apps/devs
  * You can save your session info into files anytime
  * You can read an archived file into its own seperate window
  * If you arrange several windows you can recall them at the next boot up
  * Has several filters to help display information that is most useful
  * You can display any combination of apps/devs from one to all
  * You can enable a keep alive capability that will prevent hanging if Hubitat




<style>
        .image-container {
            margin-top: 50px; /* Add 20 pixels of space above the image */
        }
        </style>
        <div class="image-container">
     ![image](https://github.com/user-attachments/assets/e3ad71f9-b7f2-4783-9a5e-b994b837f082)
        </div>



