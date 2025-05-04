# CS-350 - Emerging Sys Arch and Tech (Embedded Systems) course 


I have included all completed course assignments in this repository.  The final project involved the development a smart thermostat running on a Raspberry Pi single-board computer.  The requirements for this project included that the system detect temperature in real-time, and that the system activate a heating or cooling system in order to make the current temperature match a target temperature set by the user.  The user is able to increase or decrease the target temperature by pressing one of two buttons to increase or decrease this value, and a third button for alternating between heating, cooling, and off states.  



This course was closely aligned with my career goals, so I chose to challenge myself by using alternative versions of some of the provided hardware in order to force myself to dive deeper into the underlying technology involved in each assignment and project milestone.  For example, I used an Iduino GPIO breakout rather than the Adafruit breakout included in our course materials.  This board is set up opposite to the Adafruit version in terms of the arrangement of GPIO pins, so I had to research each individual pin and how it should connect to the system in order to achieve the required functionality.  I also used a different type of temperature sensor (SHT31), which forced me to research how these temperature sensors are referenced within the associated Python libraries.  At the top of the Thermostat.py file, I included a line of commented-out code beside the declaration of the sensor object to set the system to interpret data to the other type of temperature sensor.  The system is now able to use either the AHTx0 and SHT31 temperature sensor, making it more serviceable in more parts of the world.  I researched how each hardware component communicates with the system, and how the circuitry must be assembled in order to create a functional and electronically safe circuit.  The software engineering aspect of this course was an excellent opportunity to reinforce my existing Python coding skills while gaining exposure to new Python libraries commonly used in embedded systems.  



This course has given me the opportunity to enhance my ability to use documentation directly rather than relying on third-party interpretations.  While guides and tutorials are a great resource for more simple computer science projects, the relatively complex nature of the assignments in this course mean that the documentation for the libraries and hardware components involved in development were really the only source of support.  This of course is also true of the vast majority of software engineering and  development in the professional world.



I have been highly focused on pursuing a career as a roboticist, and the skills acquired in this course were perhaps the most relevant to my planned career trajectory of all of the classes which I have previously taken at SNHU.  The amount of “Eureka” moments and the high level of satisfaction involved in even the smallest of breakthroughs achieved throughout the completion of these assignments made this by far the most enjoyable computer science course I have ever taken.



One of the ways in which I made this project more maintainable was the inclusion of additional variables for values such as the minimum temperature, maximum temperature, and target temperature in my final project submission.  This was an additional safety feature which I thought I'd add in the interest of making as realistic a smart thermostat system as possible.  I made sure to maintain readability and to provide comprehensive comments explaining every line of my code.  I even added further comments to some of the files provided to us.  The modularization of each program into a series of reusable single-purpose functions means that components of this code can be added to other projects which use similar hardware and software architectures.
 
