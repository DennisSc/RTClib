This is a fork of JeeLab's fantastic real time clock library for Arduino.

For details on using this library with an RTC module like the DS1307, see the guide at: https://learn.adafruit.com/ds1307-real-time-clock-breakout-board-kit/overview

To download. click the DOWNLOADS button to the right, and rename the uncompressed folder RTClib.

Place the RTClib folder in your *arduinosketchfolder*/libraries/ folder. 
You may need to create the libraries subfolder if its your first library. 
Restart the IDE.


Basic functions  (see libraries/examples of how to use):
  .begin
  .adjust
  .isrunning
  .now
  
DS1307 specific functions:
  .readnvram
  .writenvram
  .readSqwPinMode
  .writeSqwPinMode

DS3231 specific functions:
  .getTemperature
  .getA1Time
  .setA1Time
  .setAlarm1Simple
  .turnOnAlarm
  .turnOffAlarm
  .checkAlarmEnabled
  .checkIfAlarm
  
DS3231 functionality tested on Arduino Pro Mini (Jan 8, 2016 - MrAlvin)
For other compatibility details see https://github.com/adafruit/RTClib

ToDo: 
 - debug Alarm2
 - make DS3231 SQW functon calls similar to DS1307 function calls

