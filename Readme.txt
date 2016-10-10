Readme - HTTP Post library for Arduino.
2016/09/29
Made by Tobias Koops from MicroEnergyInternational
Based on code from Andreas Spiess
License: Opensource
http://gitlab.koukei.de/Tobias/A6HTTPLibrary.git

This is a library for the A6-GSMChip by Ai-Thinkers.

Standart settings:
RX(Arduino): PIN 4
TX(Arduino): PIN 3
Reset: PIN 10 (needed for correct initialization)
Baudrate: 9600 (Arduino - A6)
Baudrate: 112500 (Arduino - PC)

These can be changed in A6HTTP.cpp
In A6HTTP_Example I used the free service from posttestserver.com of posting something on it and beeing able to see it afterwards.

If you set up everything the right way, you should be able to use this example just as it is.


