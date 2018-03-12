# A Game for the AVR - Written in Assembler Language

The purpose of this assignment is to write a small memory game in assembler code. The MCU to be used is the AVR ATmega2560 mounted on the STK600 development board. The game could also be developed on an Arduino Mega connected to some leds and switches.

## Description of the Game

The game is a turn-based memory game. The player will at the beginning of a turn be presented with a sequence of flashes on the leds that the player must then try to remember and input correctly on the buttons. If input correctly the round is won and the game continues, if not, the game is lost and restarted. Gradually the difficulty increases (the sequence getting longer).

* The UI of the game must be implemented with 8 leds
* User input must be implemented using 8 switches
* The user should get feedback from the game when a game is started (and restarted) and when a round is won.
* The sequence of flashes represents a sequence of numbers from 0 to 7. The sequence can contain the same numbers multiple times. 

## Requirements

### Analysis and Design
You must analyse the problem and describe it on diagram form before implementing it. *Use for instance Activity or State Machine diagrams for this purpose.*

### Test
Make a plan for testing your implementation. The plan should provide details on how to test the individual components or actions of your implementation.

### Implementation
Implement the game in AVR assembler. The code must be well-structured and extensively commented. 

## Practical Information
### Definition of Done
The game should be demonstrated for me on class and your implementation code handed in on github. See section below for details on how to hand in on github.

All group members should have participated actively in producing code and thus it should be possible to find all group members in the git commit history.

### Deadline 
5th of April by the end of the lesson (2.20pm)

### Github
Before starting to commit any code, this repository should be forked to the github account of a group member. This forked repository is where you are going to create your Atmel Studio project and commit your assembler code. Eventually you can "Hand in" by creating a pull request. This will enable me to see your code and provide you comments on your project.

If you are unsure of the details, ask me or a fellow student og go watch a video (like this: https://www.youtube.com/watch?v=_NrSWLQsDL4) or read the documentation.
