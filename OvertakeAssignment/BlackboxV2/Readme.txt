This Blackbox routine will provide simulated data for the overtaking of a vehicle and the chance of success.

Parameters available:

Blackbox.exe version(0-4) numberOfSamples enchancedOutput


For example:

Blackbox.exe 2 
This will generate the default of 10 records using version 2 of the algorithm 

Example of 1 record:
InitialSeparationM	OvertakingSpeedMPS	OncomingSpeedMPS	VehicleBeingOvertakenSpeedMPS
109.4			30.2			9.2			TRUE


Blackbox.exe 2 100
This will generate 100 records using version 2 of the algorithm 


Blackbox.exe 4 1000 1
This will generate 1000 records using version 4 of the algorithm and provide more input values 

Example of 1 record with enhanced input values:
InitialSeparationM	OvertakingSpeedMPS	OncomingSpeedMPS	VehicleBeingOvertakenSpeedMPS	WindSpeedMPS	FrictionCoefficient	RoadCondition	Success
162.7			30.5			17.7			16.2				6.3		0.73			Wet		TRUE
