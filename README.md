# TAB5305-12-Soundbar-ESPHome-IR-Remote
Adds remote control functionality for Philips TAB5305/12 Soundbar to Home Assistant via ESPHome.

# Prerequisites
1. Connect all components as shown in the picture below.

![Breadboard Layout](https://test.leondierkes.de/media/IR_Blaster_Steckplatine_fix.png)

2. Download "ir-blaster.yaml" and replace all "REPLACE_ME" fields with your values.

3. Click on "NEW DEVICE" on the ESPHome dashboard, give it the name "ir_blaster", select esp8266 and paste the code of your edited "ir-blaster.yaml" there.

4. Now click on "INSTALL" -> "Manual Download" -> "Modern Format" in the upper right corner. Afterwards a ".bin" file will be generated, which you have to download and then install at "https://web.esphome.io/?dashboard_install".  
