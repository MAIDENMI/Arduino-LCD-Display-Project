Hey there! 👋 I'm thrilled to share my latest Arduino project featuring an alphanumeric LCD display (LCD1602).
This project allowed me to dive into the world of hardware and microcontrollers, creating a cool display that showcases personalized messages.

Project Highlights:
Display Features: The LCD1602 module has a vibrant LED backlight and can show two rows of up to 16 characters each. It's perfect for presenting text messages in a clean and readable format.

Arduino Uno Magic: Utilizing an Elegoo Uno R3, I connected the LCD display along with a potentiometer for contrast adjustment. The result? A neat and functional setup that's both fun and educational.

Completed Code: The provided Arduino code, inspired by the LiquidCrystal library, demonstrates the display's capabilities. It prints a welcoming message and interesting facts about me, updating every few seconds.

Project Overview:
In this project, I successfully wired up and utilized the LCD display to print custom messages using Arduino Uno. 
The display has an LED backlight, and I even incorporated a potentiometer to control the contrast. 
The code included in this repository demonstrates how to set up the hardware and display messages on the LCD.

![](images/LCDDisplay.png)


Completed Features:
Display "Hello,Linkedin!" on the LCD screen upon startup.
Periodically change messages on the screen to showcase personal details.
Easily customizable code for your own messages and display configurations.

![](images/ArduinoLcdDisplay.png)

Components Used:
1x Elegoo Uno R3
1x LCD1602 module
1x Potentiometer (10k)
1x 830 tie-points Breadboard
16x M-M wires (Male to Male jumper wires)

Wiring Instructions:
Connect LCD RS pin to digital pin 7
Connect LCD Enable pin to digital pin 8
Connect LCD D4 pin to digital pin 9
Connect LCD D5 pin to digital pin 10
Connect LCD D6 pin to digital pin 11
Connect LCD D7 pin to digital pin 12
Connect LCD R/W pin to ground
Connect LCD VSS pin to ground
Connect LCD VCC pin to 5V
Connect a 10K resistor: one end to +5V, the other end to ground, and the wiper to LCD VO pin (pin 3)
Running the Code:
Upload the provided Arduino code to your Elegoo Uno.
Watch as the LCD display comes to life with the programmed messages.




