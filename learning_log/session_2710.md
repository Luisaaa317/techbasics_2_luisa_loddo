# Topics
-	Pins on Arduino board
-	Tilt switch
-	Potentiometer
-	Photoresistor 
# Learnings
-	An Arduino board has digital pins used for programming the board, in case one runs out of them one can also use the analog pins
-	Theres a vin pin that can be used to power the board instead of the usb port
-	Pin D1 and D0 are usually never used because they could get in the way of read and write which are used to programm the board
-	A tilt switch is a switch that has a little metal ball inside, if the switch is upright the little metal ball inside connects the legs
-	To be able to get a good sensor reading one should use the command INPUT_PULLUP to avoid cable noise disturbing the reading
-	A potentiometer can be used to control things such as volume or the rbightness of an LED by turning the knob and manipulating the voltage, voltage can be converted into a digital value from 0 to 1023
-	A photoresistor is a light sensitive resistor, if too little light is there it can be used to acknowledge the lack of light and furthermore turn on an LED
# Struggles
- I couldn't quite get the photoresistor to work with the LED
