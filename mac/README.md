### CH34X USB-SERIAL DRIVER INSTALLATION INSTRUCTIONS

##### Support System
- OSX 10.9 and above

##### Installation 

 - Extract the contents of the zip file to a local installation directory Double-click CH34x_Install.pkg
 - Install according to the installation on procedure
 - Restart after finishing installing

After the installation is completed, you will find serial device in the device list(/dev/tty.wchusbserial*), and you can access it by serial tools.

If you can’t find the serial port then you can follow the steps below:

 - Open terminal and type `ls /dev/tty*` and see is there device like tty.wchusbserial;
 - Open `System Report -> Hardware -> USB`, on the right side `USB Device Tree` there will be device named `Vendor-Specific Device` and check if the Current is normal.
If the steps upper don’t work at all, please try to install the package again.

##### Note:

Please enter `System Preferences -> Security & Privacy -> General`, below the title `Allow apps downloaded from:` you should select the second choice: ”Mac App Store and identified developers” so that our driver will work normally.
