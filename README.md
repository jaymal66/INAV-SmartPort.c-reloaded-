# INAV-SmartPort.c-reloaded-
Extensive  Flight Modes  reporting  via SmartPort telemetry.
The aim here is to provide via SmartPort telemetry  access to all flight modes  defined in the INAV configurator.
Users (Multimotor AND FW) aren't anymore limited to an arbitrary subset to pick those modes which they want to monitor  on their TX.
The following 6 additionnal modes are now included HOME RESET,NAV_LAUNCH,FLAPERON,TURN_ASSIST,AUTOTRIM AUTO TUNE.More can be added.
The reloaded  smartport.c has been tested with 1.7.3 and can be implemented with a custom build simply by replacing the original one.
The same hold for  1.8 RC1 since to my knowledge  1.8 RC1 and 1.7.3 share the same smartport.c .
Documentation at this time is limited to the comments in the section of the  code  dealing with the tmp1 container.
A prototype of the Lua code to decode the new setup of the tmp1 container is available on request.
