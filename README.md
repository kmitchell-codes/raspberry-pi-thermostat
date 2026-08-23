# CS350

Summarize the project and what problem it was solving.

This project created a thermostat that could be powered on and off and operated in cooling or heating mode. It had a set temperature so that the system could compare the current temperature to the desired temperature and determine whether heating or cooling was needed. The set temperature could be raised or lowered by 1 degree, with LEDs to show which mode it was set to and whether the current temperature was above or below the set temperature. The LCD also displayed the date and time and alternated between showing the current temperature and the thermostat state and set temperature.

What did you do particularly well?

I think working through this project I really got to test and challenge my troubleshooting skills and understanding of how the hardware works. The guides were  set up differently from my hardware, so it was up to me to figure out the correct wiring so that everything worked as it should. I became better at using the GPIO connections and existing working components as reference points instead of relying only on the breadboard positions shown in the guide. I also tested the project in smaller sections as I worked so that when something did not work correctly, I could narrow down the cause instead of troubleshooting the entire system at once.

Where could you improve?

I think I could improve by planning and documenting my wiring more carefully before making changes to the hardware. Although I was able to troubleshoot the differences between the course guides and my breadboard, keeping a clearer record of each GPIO connection and breadboard position from the beginning would have made troubleshooting faster. I could also improve documenting my changes as I make them so that any modifications are easier to follow later.

What tools and/or resources are you adding to your support network?

The documentation available for Python libraries, Raspberry Pi hardware, and individual sensors and components is something I will continue using as part of my support network. I also became more comfortable comparing course documentation with hardware documentation when something did not match exactly. Breaking a problem into smaller tests and using error messages, GPIO documentation, and component specifications as troubleshooting resources will also be useful in future projects.

What skills from this project will be particularly transferable to other projects and/or course work?

The troubleshooting and problem-solving skills from this project will probably be the most transferable. I learned not to assume that hardware, diagrams, or instructions will always match perfectly and to use what I know about the system to determine where a problem is occurring. Testing smaller sections before combining them into the complete program is also something I can use in future programming projects. The project also gave me more experience working with hardware and software together, GPIO connections, sensors, state machines, serial communication, and I2C devices.

How did you make this project maintainable, readable, and adaptable?

I made the project maintainable and readable by keeping the program organized into separate classes and methods with specific responsibilities instead of placing all of the logic into one section of code. Comments and descriptive names help explain what different sections of the program control. The state machine also keeps the thermostat behavior organized by clearly defining its different states and transitions. This structure makes the project easier to troubleshoot or modify later because individual components or behaviors can be changed without redesigning the entire program.
