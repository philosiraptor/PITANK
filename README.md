# PITANK
<img width="1080" alt="image" src="https://github.com/philosiraptor/PITANK/assets/7144712/3c475833-15ed-4910-96b3-ce79eb5d373b">

a little tracked vehicle for the raspberry pi zero two.

you can download a raspberry pi image here:
https://drive.google.com/file/d/151bQS0FqwIOCgqsOupGxVaDsrEjjbBft/view?usp=sharing

wiring is fairly simple, PWM signals for its drive servos are on GPIO pins 12 and 13

see LCD wiring.jpg on how to wire the lcd

power for servos utilizes the 5v pin (either one is good)
and GND for servos is any gnd on the GPIO header

code is written in c# running .net core 7.0 utilizing Blazor server side to build the highly responsive web interface
if using the system image, it is available via port 8001
additional, please use the offical rpi imager software to apply new credentials 
<img width="768" alt="image" src="https://github.com/philosiraptor/PITANK/assets/7144712/89f5a9b1-f8a2-4b84-8dcb-f21032d63584">

its tiny, but it seems to traverse all manner of residential flooring without issue, just big enough to explore !
