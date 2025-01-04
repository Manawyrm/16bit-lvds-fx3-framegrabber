# Cypress FX3-based 16bit LVDS Framegrabber (Hardware repo)

![Framegrabber PCB with FX3 SuperSpeed Explorer Kit](https://screenshot.tbspace.de/mbleyntaqgj.jpg)
![Framegrabber PCB next to SuperSpeed Explorer Kit](https://screenshot.tbspace.de/auolivbptzr.jpg)

### Overview

The 16bit-LVDS-FX3-Framegrabber is a Cypress FX3-based PCB, which can digitize a parallel 16bit digital video stream from a commercial image sensor.
It exposes a USB 3.0 UVC ("webcam") device to the operating system.

Video signal is accepted on a 50pin SCSI-II connector as parallel LVDS.  
Required signals:
- DATA_VALID
- HSYNC
- VSYNC
- PIXCLK
- DATA0 through DATA15

The framegrabber follows the common industry standard pinout for 16bit digital LVDS video.

### Additional info 
[Firmware](https://github.com/Manawyrm/16bit-lvds-fx3-framegrabber-fw)  