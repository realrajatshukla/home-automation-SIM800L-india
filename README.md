# home-automation-SIM800L-india

This code works for indian service providers
SIM800l is an easy and cheap GSM alternative

SIM800L works on 3.3V theoretically but i tried it on 5V and it worked just fine without any damages.
It take about 7-8 sconds to get the signal up and running. Be patient.
Once on chip LED starts blinking once every 3 seconds rest assured that the connection has been stablished.

Output can be observed on pin 8
RX and TX pins are 10 and 11
Don't forget to revrse the order its essential for the project to work

When i send start to the sim on module it turns on the relay and when i send it once again it turns it off.

just compile the code and upload to arduino and you are good to go.
