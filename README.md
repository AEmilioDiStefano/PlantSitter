# CS-350 - Emerging Sys Arch and Tech (Embedded Systems) course


I have included all completed course assignments in this repository.  The main project is of course the final project, where a smart thermostat was developed to a list of specifications.  These included that the system detect temperature in real-time, and that the system activate a heating or cooling system in order to make the current temperature match a target temperature set by the user.  The user is able to increase or decrease the target temperature by pressing one of two buttons to increase or decrease this value, and a third button for alternating between heating, cooling, and off states.  



Since I already had some embedded systems development experience prior to taking this course, I chose to use alternative versions of some of the provided hardware in order to force myself to dive deeper into the underlying technology involved in each assignment and project milestone.  For example, I used an Arduino GPIO breakout rather than the Adafruit breakout included in our course materials.  This board is set up opposite to the Adafruit version in terms of the arrangement of GPIO pins, so I had to research each individual pin and how it should connect to the system in order to achieve the required functionality.  I researched how each hardware component communicates with the system, and how the circuitry must be assembled in order to create a functional and electronically safe circuit.  The software engineering aspect of this course was an excellent opportunity to reinforce my existing Python coding skills while gaining exposure to new Python libraries commonly used in embedded systems.  



This course has given me the opportunity to enhance my ability to use documentation directly rather than relying on third-party interpretations.  While guides and tutorials are a great resource for more simple computer science projects, the relatively complex nature of the assignments in this course mean that the documentation for the libraries and hardware components involved in development were really the only source of support.  This of course is also true of the vast majority of software engineering and  development in the professional world.



I have been highly focused on pursuing a career as a roboticist and eventually starting my own defense-oriented robotics company, so the skills acquired in this course were perhaps the most relevant to my planned career trajectory of all of the classes which I have previously taken at SNHU.  The amount of “Eureka” moments and the high level of satisfaction involved in even the smallest of breakthroughs achieved throughout the completion of these assignments made this by far the most enjoyable computer science course I have ever taken - and I really do mean that!   



One of the ways in which I made this project more maintainable was the inclusion of global (class-wide) variables for values such as the minimum temperature, maximum temperature, and target temperature in my final project submission.  I made sure to maintain readability to provide comprehensive comments explaining every line of my code, and even added in-file documentation for some of the files provided to us.  The modularization of each program into a series of reusable single-purpose functions means that components of this code can be added to other projects which rely on similar hardware and software architectures for their development.
 
