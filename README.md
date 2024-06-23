Scrolling Clock - Arduino UNO, RTC, and DHT-11
Hey Science Enthusiasts! Get ready to dive into the world of Arduino with a fantastic project: a 64x8 LED Dot Matrix Clock with temperature and humidity display. Let's make this electrifyingly cool clock step-by-step!

Materials You'll Need:
 
Arduino Uno: Your brilliant brain for the project.
DHT11 Sensor: To measure temperature and humidity.
Max7219 32×8 LED Matrix Panel x 2: The stage for our clock display.
RTC DS1302 Module: Keeps track of the time.
LDR (Light Dependent Resistor): Adjusts the brightness of the LED.
Jump wires: Connect the dots!
Breadboard: The playground for your circuit.
USB Cable: To power up your Arduino and upload code.
Step 1: Connect the Hardware
 
Cue the dramatic science music, we’re setting up!

Connect the RTC DS1302 Module:

IO to Digital Pin 4.
SCLK to Digital Pin 5.
CE to Digital Pin 2.
Hook up the DHT11 Sensor:

VCC to 5V.
GND to GND.
Data Pin to Digital Pin 6.
Wire the Max72xx LED Matrix:

CS to Analog Pin A3.
DIN to 11.
CLK to 13.
VCC to 5V.
GND to GND.
Connect the LDR:

One end to 5V.
The other end to Analog Pin A2 and a 10kΩ resistor to GND.
Remember: Double-check your connections! Incorrect wiring can make your clock go cuckoo!


Step 2: Code Time!
 
Now, let’s give our Arduino its marching orders.

Fire Up Your IDE:

Open the Arduino IDE on your computer.
Install Required Libraries:

Go to Sketch -> Include Library -> Manage Libraries.
Search for and install:
“RTC by Makuna”
“Adafruit Unified Sensor”
“DHT sensor library”
“Adafruit GFX Library”
“Max72xxPanel”
Copy the Code:

Click here for Arduino Sketch
4. Upload the Code:

Connect your Arduino to your computer using the USB cable.
Select the correct board and port from Tools.
Click the Upload button.
Step 3: Test Your Clock!
Lights, camera, action!

Power Up Your Setup:

Connect your Arduino to a power source.
Watch your LED matrix come to life displaying the current time and weather data!
Set the Clock:

Open the Serial Monitor in the Arduino IDE.
Input the current date and time in the format <dd/mm/yyyy hh:mm
 
> to set your clock.

Success! You’ve built your very own 32×8 LED Dot Matrix Clock with temperature and humidity display!

Troubleshooting Tips:
No Display? Check all connections, especially the power and data lines to the matrix.
Wrong Time? Make sure you’ve set the RTC module correctly through the Serial Monitor.
No Temperature/Humidity? Verify your DHT sensor connections and code configuration.
Congratulations, you now have a spectacular clock to dazzle your friends and keep time! Remember, in the wise words of Bill Nye, “Everyone you will ever meet knows something you don’t.” Keep learning and experimenting!

Science rules!
