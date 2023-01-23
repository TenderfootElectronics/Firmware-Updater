# Firmware-Updater
The Firmware update software for use with 2022 and newer modules.

Tenderfoot Electronics Firmware Updater
----
**Step1**
Before using the updater, make sure you are using Windows and have installed AVRDude. There are 2 ways that we can do this:



**_OPTION 1_** - Automatic install of AVRDude via Arduino IDE
Download the most recent version of the Arduino IDE for free from the official arduino website:

https://www.arduino.cc/en/software

This automatically installs AVRDude and can be uninstalled after the firmware update is complete.

_**Progress to Step2 (not option 2)**._



**_OPTION 2_** - Manual install of AVRDude 
A copy of AVRDude is included in the subfolder of this zip file, but can also be downloaded from:

https://github.com/avrdudes/avrdude/releases 


To install AVRDude, place the AVRDude folder in a location of your choice.

Next, we need to add this folder to the path variable. To do this, click on your windows start bar and search "about your pc". Click this and then click on "advanced system settings" on the right.

Click on the "Environment Variables" button. Then in the lower box find and select the variable "Path", and click the "edit" button.

In the new pop-up window, press the "Browse..." button and locate the AVRDude directory.

Then press OK and close the system properties windows and _**progress to Step2**._

----

**Step2**
Make sure you have a copy of the firmware you wish to flash to your product. This will be a ".hex" file.

----

**Step3**
Make sure the product that you are updating is switched off, and all other switches are in the off positions.
Also make sure you have easy access to the mini USB port on the product.

----

**Step4**
Insert the USB mini cable into the unit and connect it to your computer.

----

**Step5**
Open the TenderfootUpdater.exe program.

----

**Step6**
Press the "Select Firmware" button and locate the ".hex" file mentioned in step 2.

----

**Step7**
Select the USB Port that the product is connected to. 

If there are multiple options, you can unplug the product and restart the application to see which option is missing.

This will tell you which one to select next time you run the program.

Alternatively, you can open the windows device manager, and under the "Ports" list, you will see a COM port labeled with "CH340". This will be the correct port to choose in the updater 

----

**Step8**
The "Install Firmware" button will now be active. Click this to install the firmware. 

You will see the progress of the AVRDude program running in a black command window.

When it has finished the writing and reading process, it should say "avrdude done. Thank you."

(You may see a message saying "verification error, first mismatch at...." This is not a problem,
and as long as the Writing and Reading progress got to 100%, you're fine!)

You can now close all of the windows, unplug the product and it should be up-to-date!

If you have any questions, please e-mail SUPPORT@TENDERFOOTELECTRONICS.COM

