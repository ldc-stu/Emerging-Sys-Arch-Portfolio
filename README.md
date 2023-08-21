# Emerging-Sys-Arch-Portfolio

Summarize the project and what problem it was solving.
  The two projects I have chosen are the final project that regards a prototype of a thermostat and milestone 3 that is about Morse Code. The thermostat project involved creating a task scheduler that would use the temperature sensor to check the ambient temperature and compare that against a set point to determine if the heating system should be turned on or off. The two buttons on the device adjust the temperature set point up or down. The task scheduler would check if a button had been pressed every 200ms, check the ambient temperature every 500ms, and determine if it was needed to turn off or on the LED every second. It would also need to report the current status of the device via UART with info of the room temperature, set-point temperature, heating state (on or off), and the current runtime in seconds.
  The Morse code project displayed two messages in Morse code. The two messages, 'SOS' and 'OK', were displayed one at a time on a continuous loop giving the ability to switch between messages by pressing one of the buttons. Two LEDs and a state machine determines if an LED should be on or off. A red LED that is on for 500ms represented a dot and a green LED that is on for 1500ms represented a dash. An established 1500ms pause with both LEDs off between each character of the message and another 3500ms pause between each word. If the button was pressed to switch messages while a message was already displayed, the new message would allow the old message to be shown before it takes over.
  
What did you do particularly well?
  This courses topics are relatively new to me so it was expected to be overwhelmed when working with the board. I had mitigated this problem by completing section by section one at a time so I may avoid that feeling of being overwhelmed and this helped emmensely in appropiate work flow without getting frustrated or burnt out. Following a logical order in developing code also helped in proper debugging during troubleshooting

Where could you improve?
  As mentioned earlier, I improved by going piece by piece but managing development time consistently still causes trouble for me. Another area I could improve on are the creation of the state diagrams as in any course that demands this leaves me troubled during the inital phase of interpretting code into a visual diagram.
  
What tools and/or resources are you adding to your support network?
  Most, if not all of what I had learned during this course was new material for me so I can take that new info onto new courses regarding communication between hardware and software. In the case of a resource that helped me develop througout the course, the offical PDF manual of the TI CC3220S-LAUNCHXL was the most valuable when working with the board.
    
What skills from this project will be particularly transferable to other projects and/or course work?
  As a complete begineer in this topic the newly found knowledge regarding communication between hardware and software will prove valuable in the designs of both. I will continue in working in segments to avoid being overwhelmed as that would be good practice in most things that doesn't even consider computer science.
    
How did you make this project maintainable, readable, and adaptable?
  In order for our project to be maintainable, readable, and adaptable by using good coding practices I used descriptive variable names, commented my code, and used functions to break up the code into segments. With the assistance of a state machine this made it easier in additions to our program, such as modifying it through arrays instead. 
