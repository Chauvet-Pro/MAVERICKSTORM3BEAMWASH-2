# Maverick Storm 3 BeamWash-2

### Note: These software updates are specifically ONLY for the Maverick Storm 3 BeamWash-2 or the Maverick Storm 3 BeamWash with the upgrade ring kit.

## Software Versions

[V1.250403 - Maverick Storm 3 BeamWash - 2](https://github.com/Chauvet-Pro/MAVERICKSTORM3BEAMWASH-2/blob/02d7e775b14dab8d6a05881c057fe8113052fe1b/Firmware/V1.250403.zip)
- Fixed RDM failures
- Fixed the bug that during software update, some LED will not turn off
- Fixed the bug that there is CPU error every now and then while there is no fault in the fixture

[V1.241128 - Maverick Storm 3 BeamWash-2](https://github.com/Chauvet-Pro/MAVERICKSTORM3BEAMWASH-2/blob/d5f6b233acc081399f24b15482b1cba1d3c37021/Firmware/V1.241128.zip)
- Added TV25 and TV35 fan modes

[V1.240514 - Maverick Storm 3 BeamWash-2](https://github.com/Chauvet-Pro/MAVERICKSTORM3BEAMWASH-2/blob/f5fcdace6def1768f758b755475c8147802676b6/Firmware/V1.240514.zip)
- Released software version

&nbsp;

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message "**USB UPDATE**" will be displayed. Select **<YES>**.  
3.	The next screen will show the software versions available for this fixture on the USB drive.  For multiple versions of the software for the same fixture, use **<UP>** or **<DOWN>** to select the desired version.  Press **<ENTER>**.
4.	The “**USB UPDATE**” screen will re-appear.  Press **<YES>**.
5.	The upgrade will start. **DO NOT** turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “**USB Update Wait**”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.

