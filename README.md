Lab created for CS3 Class. Lab purpose: This lab was designed to demonstrate arrays of objects and to practice implementing classes.

Program Shells
StdDraw.java - This is a non-standard Java file similar to DrawingPanel. It allows the creation and display of a GUI. You won't make any new calls to StdDraw. If you want more info here is the standard documentation. (Note StdDraw does not use pixel coordinates. Instead it takes x and y locations between 0 and 1 and plots them assuming the drawing area is a unit square.)
StdAudio.java - Used to play sounds. You should not have to change any of the calls to this class or call any other methods. If interested, here is the documentation
GuitarHeroLite.java - A class that creates a GUI and allows the user to "pluck" two guitar strings by pressing the 'a' or 'c' key on the keyboard. This class will not work until you complete the GuitarString and RingBuffer classes. Implement a GuitarHero.java class similar to GuitarHeroLite, but your class will support 37 strings, not just 2.
RingBufferTester.java - Simple tests for your RingBuffer class.
Background:
Write a program to simulate plucking a guitar string using the Karplus-Strong algorithm. This algorithm played a seminal role in the emergence of physically modeled sound synthesis (where a physical description of a musical instrument is used to synthesize sound electronically).
Digital audio. For more background on digital audio, review Standard audio section of this web page and the Superposition of sound waves section of this web page.
Simulate the plucking of a guitar string. When a guitar string is plucked, the string vibrates and creates sound. The length of the string determines its fundamental frequency of vibration. We model a guitar string by sampling its displacement (a real number between -1/2 and +1/2) at N equally spaced points (in time), where N equals the sampling rate (44,100) divided by the fundamental frequency (rounding the quotient up to the nearest integer).

This lab was desgined by Princeton  by Kevin Wayne, Andrew Appel, Jeff Bernstein, Maria Ginsburg, Ken Steiglitz, Ge Wang

Lab finished on November 15th, 2023
