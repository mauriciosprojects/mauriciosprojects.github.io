# BBGame114: Breadboard Game with 11x4 Matrix

BBGame114 is handheld game device that consists of an Arduino Nano processor board, an 11x4 LED matrix display, three input buttons and a piezoelectric speaker. This device can be programmed using the Arduino IDE. The [BBGame114 GitHub repository](https://github.com/mauriciosprojects/BBGame114) at [https://github.com/mauriciosprojects/BBGame114](https://github.com/mauriciosprojects/BBGame114) contains the BBGame114Lib library that can be used for programming this device, and it also contains a Space Invaders-like game.

<img src="https://github.com/mauriciosprojects/BBGame114/raw/doc/Build/BBGame114.png" width="800" alt="BBGame114 build diagram">
*Diagram of BBGame114 assembled on 830-point solderless breadboard*

<img src="https://github.com/mauriciosprojects/BBGame114/raw/doc/Build/BBGame114%20circuit%20diagram.png" width="800" alt="BBGame114 circuit diagram">
*Circuit diagram*

## Code

The [BBGame114 GitHub repository](https://github.com/mauriciosprojects/BBGame114) at [https://github.com/mauriciosprojects/BBGame114](https://github.com/mauriciosprojects/BBGame114) contains the following coding exercises:
* Exercises 1 to 3: Coding with an Arduino processor and 5 LEDs
* Exercises 4 to 7: Coding with a partial 5x4 LED matrix
* Exercises 8 to 10: Coding with a full 11x4 LED matrix, leading up to coding a full game
* Exercises 11 to 12: Additional special coding exercises

## How to Build

Building this breadboard game will take several hours, and this will vary based on the experience you have with basic electronics. 
The links below give an overview of this project and 3 sets of slides that are used for three days in a coding/electronics class for high 
school students.
* [Overview of BBGame114 project](http://bit.ly/2WcviWm)
* [BBGame114 Day 1 Slides](http://bit.ly/2PCl7rO)
* [BBGame114 Day 2 Slides](http://bit.ly/2GOGmDC)
* [BBGame114 Day 3 Slides](http://bit.ly/2DyE0GX)
* [BBGame114 Reference Slides](http://bit.ly/2GPc5om)

<img src="BBGame114_photo.jpg" width=600px>

## How to Teach

* Plan three days of 6 hours, or an equivalent or appropriate amount of time to teach
* Plan on additional instructors, on the order of one instructor per 3 to 5 students
* Purchase sufficient electronics parts for all students, all instructors and also for some spare kits
* Prepare each student's kit of parts beforehand so that this does not take up class time
* All instructors should build the circuit once before the class and also try out the coding exercises

<i>Special thanks to S. Ramakrishnan, R. Hunter, C. Chiock, T. Veneruso, L. De Pavia for their valuable help in teaching and making this class happen.</i>

## BBGame114 Arduino Library

The [BBGame114Lib.zip](https://github.com/mauriciosprojects/BBGame114/blob/master/Lib/BBGame114Lib.zip?raw=true) library for Arduino included in this repository is a library that allows the BBGame114 device to be programmed with higher level methods/functions than the Arduino `digitalWrite` and `digitalRead` functions. See the page [BBGame114Lib Library Reference](https://github.com/mauriciosprojects/BBGame114/wiki/BBGame114Lib-Library-Reference) page for more information on this library. 
