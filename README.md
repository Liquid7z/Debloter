# Debloter
Debloat your device without PC

Apps Required: LADB and Package Name Viewer.

Note: Wi-fi connectivity is required through the whole process!

LADB: Download Link

Package Name Viewer: Download Link(https://www.mediafire.com/file/gvh8tyl4ejht3kh/LADB+2.1.apk/file)

Steps to debloat:

1. Enable Developer mode. Then turn on Wireless debugging as well as USB debugging in developer options.

2. Swipe down to the bottom in the developer options and enable "Force activities to be resizable".

3. Now open LADB app, it will ask for the pairing code and port number. Now go to the recent tab and press on the LADB app icon until the spilt screen option appears.

4. In the second window open developer options from settings and then click on Wireless debugging. Don't disable it, just click where Wireless debugging is written.

5. Now click on "Pair device with pairing code". You will get the code which you have to put it in the LADB app. 

6. You will have two numbers: (1) Pairing code and (2) Port number.
Port number starts after the colon (:) under "IP address and port"! For e.g, here [192.168.1.102:12345], 12345 is the port number.

7. Input the pairing code as well as port number in LADB app and click on connect. Wait for it to connect. This process needs to be done only once, next time it will connect automatically. Just make sure you have enabled USB debugging and Wireless debugging.

8. Now close the split screen and other apps except the LADB app.

9. Now run: pm uninstall -k --user 0 <package_name> for uninstallation.
Replace <package _name> with the package name of the app you want to debloat. You can get the package name for any app using the Package Name Viewer app.


Re-install debloat

For re-installing the app run: cmd package install-existing <package _name>
