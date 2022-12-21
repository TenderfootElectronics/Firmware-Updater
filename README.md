# Firmware-Updater
The Firmware update software for use with 2022 and newer modules.
Tenderfoot Electronics Firmware Updater

Step1
Before using, make sure you are using Windows and have installed AVRDude.
A copy of AVRDude is included in the subfolder of this zip file. To install AVRDude, run the avrdude.exe file.

Step2
Make sure you have a copy of the firmware you wish to flash to your product. This will be a ".hex" file.

Step3
Make sure the product that you are updating is switched off, and all other switches are in the off positions.
Also make sure you have easy access to the mini USB port on the product.

Step4
Insert the mini USB cable into the unit and connect it to your computer.

Step5
Open the Tenderfoot Updater software.

Step6
Press the "Select Firmware" button and locate the ".hex" file mentioned in step 2.

Step7
Select the USB Port that the product is connected to. If there are multiple options, 
you can unplug the product and restart the application to see which option is missing.
This will tell you which one to select next time you run the program.
Alternatively, you can open the windows device manager, and under the "Ports" list, 
you will see a COM port labeled with "CH340". This will be the correct port to choose in the updater 

Step8
The "Install Firmware" button will now be active. Click this to install the firmware. You
will see the progress of the AVRDude program running in a black command window.
When it has finished the writing and reading process, it should say "avrdude done. Thank you."

(You may see a message saying "verification error, first mismatch at...." This is not a problem,
and as long as the Writing and Reading progress got to 100%, you're fine!)

You can now close all of the windows, unplug the product and it should be up-to-date!

If you have any questions, please e-mail SUPPORT@TENDERFOOTELECTRONICS.COM
