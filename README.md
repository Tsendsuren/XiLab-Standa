# XiLab-Standa

I am using 8SMC5-USB-B8-1 stage controller with 8MT30-50DCE linear stage. 
All related software and labview examples can be found here:
http://files.xisupport.com/Software.en.html

When you install Xilab 1.14.8 software, most probably you will face with this error:
"The application was unable to start correctly (0xc0000142). Click OK to close the application."
To eliminate this error, you should follow the steps:
1. Hold Windows key and press R.
2. Type regedit.exe and press Enter.
3. Go to this path HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Windows. ...
4. Now double click LoadAppInit_Dll (from the right pane)
5. Change its value data to 0.
6. Click Ok.
7. Now restart your computer.
