#Agricultural Irrigation System Project
This project implements an agricultural irrigation system using a Real-Time Operating System (RTOS). The system performs the following tasks during each irrigation session:

*Open fertilizer mixing Valve 1 for 5 seconds
*Close Valve 1, open fertilizer mixing Valve 2 for 5 seconds
*Close Valve 2, open fertilizer mixing Valve 3 for 5 seconds
*Close valve 3, open pump 1 for 10 seconds
*Turn off pump 1, turn on pump 2 for 30 seconds
*Finally, turn off pump 2
After this process, the system will repeat the above steps every 60 seconds.

##Hardware Requirements
*Microcontroller (e.g., STM32, Arduino, Raspberry Pi)
*3 Solenoid valves
*2 Pumps
*5 LED lights (to represent the valves and pumps)

##Software Requirements
*Real-Time Operating System (e.g., FreeRTOS, ChibiOS, TI-RTOS)
*Programming language (e.g., C, C++)

##Project Structure
The project consists of the following files:
*main.c: Entry point of the program, where the RTOS tasks are created and the system is initialized.
*irrigation_system.c: Implements the logic for the irrigation system, including the tasks for opening/closing valves and turning on/off pumps.
*led_control.c: Manages the LED lights to indicate the status of the valves and pumps.
*README.md: This file, providing an overview of the project.

##Contribution
If you find any issues or have suggestions for improvement, feel free to create a new issue or submit a pull request.
