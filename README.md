# ArduRead branch
This branch heavily modifies the firmware to change the APM into a sensor package that pushes all the data up the USB port and reads flight commands down from the USB port.  You need some other software on the CPU end to read the data:

https://github.com/andybarry/flight/tree/master/drivers/cpp_ardupilot_mavlink_bridge


To fix compile issue:
https://code.google.com/p/ardupilot-mega/issues/detail?id=842

odroid@odroid-gps:/usr/share/arduino/lib$ sudo nano version.txt

odroid@odroid-gps:/usr/share/arduino/lib$ cat version.txt 
1.0.3
