# Car-Washing-Report

Mini Car Washer Prototype

----Overview------
The Mini Car Washer Prototype is an automated system designed for cleaning small vehicles like bicycles, motorbikes, and small cars. It combines the power of Arduino Uno, IR sensors, servo motors, and relays to provide an efficient and compact solution for vehicle cleaning.

--------Features--------
Automatic Vehicle Detection: Detects vehicles using IR sensors.
Efficient Water Spraying: Uses a relay-controlled water pump.
Wiping Mechanism: Servo motor-driven arm to remove excess water.
Compact and Cost-Effective Design.


---------Components Used--------------
Arduino Uno: Central control unit for processing and controlling the system.
IR Sensors: Detect the presence of vehicles and trigger washing actions.
Servo Motor: Operates the wiping arm for drying.
Relay: Manages the ON/OFF operations of the water pump.


---------How It Works---------
Vehicle Detection: IR sensors detect a vehicle's presence.
Water Spray: The Arduino Uno activates the relay to start the water pump.
Wiping Action: A second IR sensor triggers the servo motor to operate the wiping arm.
Completion: After a set duration or when the vehicle moves away, the system stops the water pump.

![image](https://github.com/prem-comet/Car-Washing-Report/blob/480b94526c85a618601895365c841067f97dde8f/Screenshot%202025-02-08%20214747.png)
----------Implementation Steps-------
Assemble components according to the circuit diagram.
Write and upload the Arduino code for system operations.
Test the prototype on small vehicles to ensure proper functionality.

-----Results---------
The prototype successfully:
Detects vehicles using IR sensors.
Sprays water efficiently with relay control.
Dries surfaces using a servo motor-powered wiper.

--------Future Enhancements--------
Add advanced sensors for better vehicle detection.
Introduce a feedback mechanism to monitor water usage.
Improve the drying mechanism for a complete washing experience.
