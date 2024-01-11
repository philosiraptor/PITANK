# PITANK
a little tracked vehicle for the raspberry pi zero two
you can download a raspberry pi image here:
https://drive.google.com/file/d/151bQS0FqwIOCgqsOupGxVaDsrEjjbBft/view?usp=sharing

wiring is fairly simple, PWM signals for its drive servos are on GPIO pins 12 and 13

see LCD wiring.jpg on how to wire the lcd

power for servos utilizes the 5v pin (either one is good)
and GND for servos is any gnd on the GPIO header

code is written in c# running .net core 7.0 utilizing Blazor server side to build the highly responsive web interface
if using the system image, it is available via port 8001
additional, please use the offical rpi imager software to apply new credentials 
