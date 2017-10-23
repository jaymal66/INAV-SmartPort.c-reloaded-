# INAV_smartport.c_reloaded
Comprehensive Flight Modes  reporting  via SmartPort telemetry.

The aim here is to report via SmartPort telemetry the state of ALL flight modes enumerated in the INAV configurator.
Thus users (MM and FW) aren't anymore limited to an arbitrary subset to pick those modes which they want to monitor on their FrSky TX.
The following 6 additional modes are now included HOME RESET,NAV_LAUNCH,FLAPERON,TURN_ASSIST,AUTOTRIM and AUTO TUNE.
Also a more efficient encoding of the modes states is used to move more information within the bandwidth provided by the tmp1 container # something which in turn provide room to include easily further modes .
The modified smartport.c has been tested with 1.7.3 and can be implemented with a custom build simply by replacing the original one.
The same hold for  1.8 RC1 since to my knowledge  1.8 RC1 and 1.7.3 share the same smartport.c . 
Documentation at this time is limited to the comments in the section of the  code  dealing with the tmp1 container.
A prototype of the Lua code to decode the new encoding scheme of the tmp1 container is available on request.
