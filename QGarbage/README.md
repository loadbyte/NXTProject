# GarbageAgentNXT:

* This program abstracts the lego robot method calls by providing method which could be called from same program or by nxj pc program by calling it through bluetooth or USB.

# Files details:

* StandardRobot.java
	this program has all the objects of sensors and motors and methods for performing actions
* GarbageAgentNXT.java
	this program creates object of standardrobot and calls its method for actions to be performed
* RobotMonitor.java
	this program monitors the values of the sensors and displays in the lcd of lego
* Consts.java'
	has the consts used by above programs

# How to run the program:

* run make in this director to compile the files
* then to upload the nxj file to lego run the below commands for usb and bluetooth:
	- for bluetooth upload:
		nxj -b -r GarbageAgentNXT
	- for usb upload:
		nxj -u -r GarbageAgentNXT


