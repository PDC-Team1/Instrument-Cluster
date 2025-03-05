# Instrument-Cluster

This project is the third project of the DES module and follows the Head Unit Project. For fundamental information regarding basic architectures, custom OS, and communication methods, please refer to the Head Unit Project.


[Head Unit Project](https://github.com/Head-Unit-Team1/Head-Unit-Team1.git)


## New Feature - PDC(Parking Distance Control)
The IC manages all data as the server of the system. It exchanges data with various devices through CAN and SOME/IP.

### Added communication contents
| Communication | Participant | Data |
| ------------- | ----------- | ---- |
| CAN | Arduino | - Receive: Distance <br> - Send: Gear |
| SOME/IP | Head Unit | - Send: Distance |
