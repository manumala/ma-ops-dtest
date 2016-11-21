System Device Interface
=======================

A system device refers to a hardware component including:

Fans/cooling devices
Power supplies
Temperature sensors
LEDs
EEPROM
Programmable devices.
Transceivers
All hardware components except for NPUs are abstracted as system devices. The SDI API defines a low-level platform-independent abstraction for all types of system devices. Only system device drivers that implement the SDI API are hardware-specific — the API itself is hardware-independent.

The implementation of the SDI API can use any approach suitable for a given platform or vendor:

sysfs access to Linux kernel device drivers
User space devices drivers using UIO or other methods
New vendor-specific kernel modules, accessible through sysfs, netlink or ioctl calls
Combination of any of the methods above
Other approaches not mentioned above are also possible, as long as the implementation supports the SDI API.
