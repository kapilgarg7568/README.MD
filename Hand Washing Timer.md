# **Hand Washing Timer**
This will alert you by a buzzer that countds 20 seconds of your hand washing.

***The HC-SR04 ultrasonic sensor***

It offers excellent range detection with high accuracy and stable readings in an easy-to-use from 2cm to 400 cm.To start the distance measurement the TRIGGER pin of HC-SR04 must receive a pulse of high (5V) for at least 10us, this will initiate the sensor will transmit out 8 cycle of ultrasonic burst at 40kHz and wait for the reflected ultrasonic burst. When the sensor detected ultrasonic from receiver, it will set the Echo pin to high (5V) and delay for a period (width) which proportion to distance. Time = Width of Echo pulse, in uS (micro second) Distance in centimeters = Time / 58
