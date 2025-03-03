README - CS 350 Portfolio Submission
Project 1: Smart Thermostat System (Software Implementation)
Summary
This portion of the project focused on writing the Python code to control a smart thermostat system. The system manages temperature monitoring, heating and cooling control, and user interaction via buttons and an LCD display. The software was implemented using state machine logic to transition between different states (OFF, HEAT, COOL).

What I Did Well
Developed a state machine that effectively handled temperature control logic.
Successfully implemented GPIO interrupts to detect button presses.
Integrated I2C communication for real-time temperature monitoring using the AHT20 sensor.
Areas for Improvement
Initial debugging of the GPIO and I2C communication required significant troubleshooting.
Optimizing the UART output string formatting to ensure reliable data transmission.
Tools & Resources Used
Software: Python, GPIOZero, Adafruit Libraries.
Debugging Tools: Serial output logs, print debugging.
Skills Transferable to Other Projects
State machine design for embedded systems.
Handling GPIO inputs and interrupts efficiently.
I2C sensor communication with microcontrollers.
Project Maintainability & Readability
Modular code design allowed easy modifications and future upgrades.
Well-commented functions to explain logic for each part of the system.
Used industry-standard libraries for better scalability and compatibility.
