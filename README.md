# Alexa at Your Fingertips
A smart glove which converts sign language into Alexa commands. Can also be used for speech.
Alexa brings ease and fun to almost everyone with just a small voice command. But what about those who can't speak? This project is for the verbally disabled people who could use alexa at the ease of a gesture. Not only can they control their smart home, but also communicate to other people without the person in front of them knowing the gesture language.

How it's made
The glove uses flex sensors( 4.5 inch), one in each finger to read the gestures through arduino, which is shown on the serial output.

Step 1:
Connect the flex sensors to a bread board. I used 2 bread boards, 3 flex sensors in one and 2 in one. Make sure the flex sensors are connected throw 10k resistors.

Step 2:
Give the analog connections to each flex sensor.Thumb, Index, Middle, Ring and Pinkey to A0, A1, A2, A3 and A4 respectively.

Step 3:
Give a common ground and common VCC(5V) on each bread board(could be interconnected since arduino has one 5V pin). Connect these to the board.

Step 4:
Connect your Arduino to your PC and upload the code attached.

Step 5:
Open your serial monitor and check the values. Change your code and make your own gestures accordingly.
