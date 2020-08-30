# BBGame248

BBGame248 is handheld game device that consists of an Arduino Nano processor board, a 24x8 LED matrix display, four input buttons and a piezoelectric speaker. This device can be programmed using the Arduino IDE. The [BBGame248 GitHub repository](https://github.com/mauriciosprojects/BBGame248) at [https://github.com/mauriciosprojects/BBGame248](https://github.com/mauriciosprojects/BBGame248) contains the BBGame248Lib library that can be used for programming this device, and it also contains a Space Invaders-like game.

![BBGame248 build diagram](https://github.com/mauriciosprojects/BBGame248/blob/master/Build/BBGame248.png?raw=true)
*Diagram of BBGame248 assembled on breadboard*

## Code

The [BBGame248 GitHub repository](https://github.com/mauriciosprojects/BBGame248) at [https://github.com/mauriciosprojects/BBGame248](https://github.com/mauriciosprojects/BBGame248) contains the following coding exercises:
* Exercises 1 to 3: Coding with an Arduino processor and 5 LEDs
* Exercises 5 to 7: Coding with a partial 8x8 LED matrix
* Exercises 8 to 10: Coding with a full 24x8 LED matrix, leading up to coding a full game
* Exercises 11: Additional coding exercise with light sensor

## How to Build

Building this breadboard game will take several hours, and this will vary based on the experience you have with basic electronics. 
The links below give an overview of this project, 2 sets of slides and handouts to print that are used for two days in a coding/electronics class for high school students.
* [Overview of BBGame248 project](http://bit.ly/2PxNZ4p)
* [BBGame114 Day 1 Slides](http://bit.ly/2JHTufC)
* [BBGame114 Day 2 Slides](http://bit.ly/2IjOhJl)
* [Handouts](https://bit.ly/3aOGTTs) with illustrations and circuit diagrams for build steps

<img src="BBGame248_photo.jpg" width=600px><br>
<i>(Photo of first prototype, wiring is slightly different)</i>

## How to Teach

* Plan two days of 6 hours, or an equivalent or appropriate amount of time to teach
* Plan on additional instructors, on the order of one instructor per 3 to 5 students
* Purchase sufficient electronics parts for all students, all instructors and also for some spare kits
* Prepare each student's kit of parts beforehand so that this does not take up class time
* All instructors should build the circuit once before the class and also try out the coding exercises

These materials can be printed for the class:
* [Handouts](https://bit.ly/3aOGTTs) with illustrations and circuit diagrams for build steps
* [Detailed build steps and teaching points](https://bit.ly/3giUL9X) for instructors to guide build and learning

<i>Special thanks to Y. Hsing for the valuable help in teaching and making this class happen.</i>

# BBGame248 Arduino Library

The [BBGame248Lib.zip](https://github.com/mauriciosprojects/BBGame248/blob/master/Lib/BBGame248Lib.zip?raw=true) library for Arduino included in this repository is a library that allows the BBGame248 device to be programmed with higher level methods/functions than the Arduino `digitalWrite` and `digitalRead` functions. See the page [BBGame248Lib Library Reference](https://github.com/mauriciosprojects/BBGame248/wiki/BBGame248Lib-Library-Reference) page for more information on this library. 
