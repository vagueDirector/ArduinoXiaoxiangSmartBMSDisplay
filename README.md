// Xiaoxiang Smart BMS Display
// For Arduino Pro mini or Arduino Nano with a 2.42" SSD1309 SPI OLED
// Code is based on a heavily modified version of: https://github.com/bres55/Smart-BMS-arduino-Reader

// This program reads data from the BMS via a secondary software serial port. 
// It then prints it out to the computer via the arduino's main serial port. 
// Additionally, it prints the important data to an OLED display. 
// Note that the Display code only works for 4S batteries and will need to be heavily modified for other configurations. 
// It shouldn't be too hard to modify this code to work with other display types as well, since the display code is mostly contained within its own subroutine.  
