Platform Adaptation Service
===========================

The PAS provides a higher-level abstraction and aggregation of the functionality provided by the system device interface (SDI) component, and implements the object models associated with system devices. The PAS monitors system devices and reports (publishes) status changes or faults as events. It also allows user applications to retrieve current status information and set control variables of system devices.

The PAS object API allows user applications to:

Read current temperature values reported by temperature sensors
Get and set fan speed values
Set a LED state
Read power levels reported by PSUs
Get system inventory and EEPROM information
Set transceiver module state (Tx laser on/off) and get module information
The PAS detects:

Common field replaceable units (FRUs), such as PSUs and fans, and insertion and removal events
Over-temperature events for pre-defined temperature thresholds
Transceiver insertion on physical ports
