## Adafruit Pixel Shifter - For Addressable LEDs PCB

<a href="http://www.adafruit.com/products/6066"><img src="assets/6066.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Pixel Shifter - For Addressable LEDs. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6066

### Description

We've been stocking WS2811-n-friends for a long time, enough to see many iterations and versions of the "one-wire-control" addressable LED pixel. We call them NeoPixels, since the part number itself can change quite a bit, but all have the same idea: send color data to lights and they'll change on their own without having to constantly PWM three or four diodes. Despite this simplicity, we've seen folks struggle with them because of voltage level expectations: some NeoPixel-compatible pixels are very picky and want 5V logic level. Without the right voltage, you get flickering or weird behavior. There's also some funky variants like the TM1814 that want inverted signal levels.

To make wiring easy, so you don't need a separate chip or breadboard, we made this Adafruit Pixel Shifter which can be easily wired in-line to your LED strips or grids or any other shape configuration they come in. On-board is a tiny 5V voltage generator, two shifters and one inverter. Provide it 3-5V power (it only needs a few milliamps) and it will shift up to two signal lines, with one of them also available as an inverted output. All pins are available on 0.1" terminal blocks, use a small flathead screw to attach your solid or stranded core wire, 18AWG to 26AWG.

It's a simple, low-cost, and solder-free way to make your finicky LED setups work with 3.3V logic chips like the RP2040, ESP32 / ESP8266, STM32, SAMD, Raspberry Pi or other modern 3.3V-logic devices. You can also use it for other 5V-logic-needing IC's that require one or two inputs. The onboard 74HCT2G34 shifter can easily handle 10MHz signals, most LED strips use a signal frequency of about 800KHz. A perfect companion to WLED!

You can also use this board as a quick signal debugger: there's a single tiny NeoPixel on the Data line, so you can verify that you're getting valid signal on that pin. If you aren't using NeoPixel protocol, or want to keep it dark, disable it by cutting the trace on the back.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
