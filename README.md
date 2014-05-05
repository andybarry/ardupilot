# ArduRead branch
This branch heavily modifies the firmware to change the APM into a sensor package that pushes all the data up the USB port and reads flight commands down from the USB port.  You need some other software on the CPU end to read the data:

https://github.com/andybarry/flight/tree/master/drivers/cpp_ardupilot_mavlink_bridge
