# REAL TIME CLOCK 
Real Time Clock using Atmel brand ATmega328P controller and DTH11 sensor using simulation Proteus

## components:
ATmega328P microcontroller from Atmel.
lcd screen LM016L
DS1307 Serial Real Time Clock 64x8

## libraries:
<Wire.h>
<EEPROM.h>
<RTClib.h>
<LiquidCrystal.h>

## Description
The prooject get the real time of the clock of the computer. Also the first buttom (Up Buttom) set the alarm time, the second buttom (Middle Buttom) increment the digit's value and the last buttom (Bottom Buttom) jump the other digits (minutes) or finish the configuration after modify the minutes. After the alarm time has been set then it show a message saying that: "Alarm time has been set". When the time match with alarm time then blink the red led. 

The function beep() will be used to vibrate a horn at 2Hz. The function match() is used to determine if the time entered by the user as an alarm coincides with the real time. If there is a coincidence, the horn sounds and displays a message: "Wake up...."
The function time() is in charge of carrying out the time modification operation.
