Xiaoxiang Smart BMS Display

For Arduino Pro mini or Arduino Nano with a 2.42" SSD1309 SPI OLED

Code is based on a heavily modified version of: https://github.com/bres55/Smart-BMS-arduino-Reader

This program reads data from the BMS via a secondary software serial port. It then prints it out to the computer via the arduino's main serial port. Additionally, it prints the important data to an OLED display. Note that the Display code only works for 4S batteries and will need to be heavily modified for other configurations. It shouldn't be too hard to modify this code to work with other display types as well, since the display code is mostly contained within its own subroutine.  

I reccommend using the JBTools Desktop application to configure the BMS prior to connecting the display. OverkillSolar has it uploaded here: https://github.com/FurTrader/OverkillSolarBMS/blob/master/Desktop_App_JBDTools-EN%20V1.1-20160718.zip

Hardware used: 
- Xiaoxiang 4S LiFePO4 Smart BMS
- Arduino Pro mini or Arduino nano
- 2.42" SSD1309 SPI OLED
- A small 12v->5v buck converter (The display draws too much current to be connected to the 12v output used by the bluetooth module, it must be connected to the B+/B- port of the BMS)
- (Optional) A 3D printed shroud to make the display panel mountable

Photos of test setup showing wiring and display:

<img src="https://raw.githubusercontent.com/vagueDirector/ArduinoXiaoxiangSmartBMSDisplay/master/Photos/20200723_154711.jpg">
<img src="https://raw.githubusercontent.com/vagueDirector/ArduinoXiaoxiangSmartBMSDisplay/master/Photos/20200723_154717.jpg">
<img src="https://raw.githubusercontent.com/vagueDirector/ArduinoXiaoxiangSmartBMSDisplay/master/Photos/20200723_154727.jpg">
<img src="https://raw.githubusercontent.com/vagueDirector/ArduinoXiaoxiangSmartBMSDisplay/master/Photos/20200723_154749.jpg">
<img src="https://raw.githubusercontent.com/vagueDirector/ArduinoXiaoxiangSmartBMSDisplay/master/Photos/20200723_154759.jpg">
<img src="https://raw.githubusercontent.com/vagueDirector/ArduinoXiaoxiangSmartBMSDisplay/master/Photos/20200723_154812.jpg">
