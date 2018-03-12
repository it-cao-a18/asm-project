# A Game for the AVR - Written in Assembler Language

The purpose of this assignment is to write a small memory game in assembler code. The MCU to be used is the AVR ATmega2560 mounted on the STK600 development board. The game could also be developed on an Arduino Mega with some connected leds and switches.

## Description of the Game

The game is a turn-based memory game. The player will at the beginning of a turn be presented with a sequence of flashes on the leds that the player must then try to remember and input correctly on the buttons. If input correctly the round is won and the game continues, if not, the game is lost and restarted. Gradually the difficulty increases (the sequence getting longer).

* The UI of the game must be implemented with 8 leds
* User input must be implemented using 8 switches
* The user should get feedback from the game when a game is started (and restarted) and when a round is won.
* The sequence of flashes represents a sequence of numbers from 0 to 7. The sequence can contain the same numbers multiple times. 

## Requirements

### Analysis and Design
* You must analyse the problem and describe it on diagram form before implementing it. *Use for instance Aktivity or State Machine diagrams for this purpose.*

### Test
* Make a plan for testing your implementation. The plan should provide details on how to test the individual components or actions of your implementation.

### Implementation
* Implement the game in AVR assembler. The code must be weel-structured and extensively commented. 