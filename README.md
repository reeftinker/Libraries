Libraries
=========

Arduino Libraries for your Reef Angel Controller

Release Notes 1.1.11
========= 
Some RANet Fixes
PH Expansion average fix
DDNS Implementation
HTTP Basic Authentication added
KalkDoser functions added
Inclusion of SunLocation, Moon, and Tide classes
New Class TimedPort with built in timers, stop/start runtimes, OSC function
Implementation of Feeding/WaterChange Speeds for RF module
PAR Expansion Module support added
WiFiAlert class added

WaterLevel Module Changes
	MultiChannel WaterLevel support added
	WaterLevel will no longer wrap below 0%

DCPump Changes - 
	LowATOChannel support
	New modes - ElseMode and GyreMode 
	Threshold to limit speed at 30% cutoff. Can be set in Memory or in INO
	AntiSyncOffset - Set an offset to increase/decrease the secondary pump
	Feeding and WaterChange speed default changed to 255 (Disabled if >100)

PWM Changes
	16Channel Module support added
	Offset expanded to include Pre/Post Offsets
	HighRes functions added for up to 12bit resolution
	New PWM curves added 
		PWMSmoothRamp (slope with transitions) 
		PWMSigmoid (Bell-curve)
