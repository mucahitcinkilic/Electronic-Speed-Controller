FPV Drone Motor and ESC Design (4S Lipo Battery)
This repository contains the design and implementation of an FPV drone motor driver system using STM32 microcontroller. It includes high-current capable MOSFETs, DRV8301 ESC controller, and a power management system. The system is optimized to work with a 4S Lipo battery and is designed for use in FPV drone projects.

Features
Motors: Velox V2306 V2 BLDC Motors (Max thrust: 1636g)
ESC Controller: DRV8301 (High-current support)
Battery: 4S 8000mAh Lipo Battery
Power Distribution: Optimized power distribution board with high-current connectors
Overcurrent Protection: Implemented through DRV8301's overcurrent detection
Control System: STM32-based motor control with PWM and BLDC motor control algorithms
Circuit Design
The circuit includes high-performance MOSFETs and the DRV8301 to control BLDC motors.
Designed for a 4S Lipo battery with a focus on power efficiency and flight time.
Integrated capacitors and inductors for power filtering and noise reduction.
Flight Time Estimation
Battery: 4S 8000mAh Lipo
Estimated flight time: Calculated based on motor power consumption and total system weight.
Setup and Usage
Hardware Setup:
Connect the 4S Lipo battery to the power distribution board.
Wire the DRV8301 ESC controller to the STM32 microcontroller for motor control.
Ensure MOSFETs are properly connected to the motor windings and power lines.
Software Setup:
Upload the STM32 motor control code to your microcontroller.
Configure the PWM signals for motor speed control and implement feedback loops as needed.


License
This project is open-source and released under the MIT License.