## Adafruit USB Serial RGB Character Backpack PCB
<a href="http://www.adafruit.com/products/782"><img src="assets/782.jpg?raw=true" width="390px"></a>&nbsp; 
<a href="http://www.adafruit.com/products/784"><img src="assets/784.jpg?raw=true" width="390px"></a><br/>
Click the image or links below to go to a specific product in the Adafruit shop.

PCB files for the Adafruit USB Serial RGB Character Backpack. Format is EagleCAD schematic and board layout
- Positive Backlight https://www.adafruit.com/product/782
- Negative Backlight https://www.adafruit.com/product/784

### DESCRIPTION
Adding a character display to your project or computer has never been easier with the new Adafruit USB or TTL serial backpack! This custom-designed PCB sits on the back of our 'standard' character LCD (16x2 or 20x4 sized) and does everything you could want: printing text, automatic scrolling, setting the backlight, adjusting contrast, making custom characters, turning on and off the cursor, etc. It can even handle our RGB backlight LCDs with full 8-bit PWM control of the backlight. That means you can change the background color to anything you want - red, green, blue, pink, white, purple yellow, teal, salmon, chartreuse, or just leave it off for a neutral background.

Inside the backpack is an USB-capable AT90USB162 chip that listens for commands both a mini-B USB port and a TTL serial input wire. The USB interface shows up as a COM/serial port on Windows/Mac/Linux. The backpack will automatically select data from whichever input is being used. For the USB connection, it will work at any baud rate. For the TTL connection, the default baud rate is 9600 but you can send it a command to set the baud rate to 2400, 4800, 9600, 19200, 28800, or 57600 baud. (The baud rate is flashed on the LCD during powerup). Any customizations such as baud rate, backlight color, brightness, splash screen, etc. are stored permanently EEPROM.

The command interface is compatible with the popular "Matrix Orbital" specifications, so this backpack will work perfectly with computer applications or libraries that are expecting a "Matrix" LCD such as "LCD Smartie". We added a few extra commands for the RGB backlight and setting the LCD size. If you don't want to use the commands, you can just start sending ASCII to the LCD and it will magically appear as typed.

This mini-kit comes with three parts: the Adafruit USB+Serial LCD backpack and a single 16x2 RGB positive or negative backlight LCD, and a strip of header. The LCD must be soldered onto the backpack using the header. This isn't a difficult task but a soldering iron and solder is required. It's easy, even for a beginner, to attach the LCD.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit.com](https://www.adafruit.com)!

Creative Commons Attribution, Share-Alike license, check license.txt for more information All text above must be included in any redistribution - 
See license.txt for more information.
