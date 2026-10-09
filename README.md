# Raspberry Pi Thermostat

**SNHU CS 350 | Embedded Systems | Python**

A Raspberry Pi-based thermostat prototype with Off, Heat, and Cool modes. The system compares sensor temperature with a setpoint and uses physical buttons, LED indicators, an LCD display, and serial communication to manage and report its state.

## Technologies

Python · Raspberry Pi · GPIO · I2C · UART / serial communication · PWM · State machines · Temperature and humidity sensor · 16×2 LCD

## Features

- Cycle between Off, Heat, and Cool using a physical button.
- Raise and lower the temperature setpoint by one degree.
- Use red and blue LED indicators to show heating and cooling conditions.
- Alternate LCD information between temperature readings and thermostat mode/setpoint, alongside the date and time.
- Send periodic thermostat status updates through the serial port.

## Project files

- [Thermostat_KM.py](Thermostat_KM.py): thermostat program.
- [CS350_Final_State_Machine_KM.pdf](CS350_Final_State_Machine_KM.pdf): state-machine documentation.

**Project context:** This academic project was built using course-provided starter code and hardware instructions. The reflections below describe my experience integrating, testing, and troubleshooting the thermostat. The original starter-code files are not included separately in this repository. Running this program requires compatible Raspberry Pi hardware and wiring.

## Development process and lessons learned

### Troubleshooting and what I did well

Working through this project really tested and challenged my troubleshooting skills and understanding of how the hardware works. The course guides were set up differently from my hardware, so it was up to me to figure out the correct wiring to get everything working as it should. I became better at using GPIO connections and existing working components as reference points instead of relying only on the breadboard positions shown in the guide. I also tested the project in smaller sections, so when something did not work correctly, I could narrow down the cause instead of troubleshooting the entire system at once.

### What I would improve

I could improve by planning and documenting my wiring more carefully before making changes to the hardware. Although I was able to troubleshoot the differences between the course guides and my breadboard, keeping a clearer record of each GPIO connection and breadboard position from the beginning would have made troubleshooting faster. I could also document my changes as I make them so that any modifications are easier to follow later.

### Tools and resources

Documentation for Python libraries, Raspberry Pi hardware, and individual sensors and components is something I will continue using. I also became more comfortable comparing course documentation with hardware documentation when something did not match exactly. Breaking a problem into smaller tests and using error messages, GPIO documentation, and component specifications as troubleshooting resources will also be useful in future projects.

### Transferable skills

Troubleshooting and problem-solving will probably be the most transferable skills from this project. I learned not to assume that hardware, diagrams, or instructions will always match perfectly and to use what I know about the system to determine where a problem is occurring. Testing smaller sections before combining them into the complete program is something I can also use in future projects. I gained more experience working with hardware and software together, GPIO connections, sensors, state machines, serial communication, and I2C devices.

### Maintainability and adaptability

I kept the program organized into separate classes and methods with specific responsibilities instead of placing all the logic into one section of code. Comments and descriptive names help explain what different sections of the program control. The state machine also keeps the thermostat behavior organized by defining its different states and transitions. This structure makes the project easier to troubleshoot or modify later because individual components or behaviors can be changed without redesigning the entire program.
