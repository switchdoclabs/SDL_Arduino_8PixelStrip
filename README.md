SDL_Arduino_8PixelStrip <BR>
SwitchDoc Labs <BR>
May 15, 2018<BR>


##Software Installation <BR>

This library uses the sxtandard Adafruit NeoPixel library

Recent versions of the Arduino IDE (1.6.2 and later) make library installation super easy via the Library Manager interface. From the Sketch menu, > Include Library > Manage Libraries...  In the text input box type in "NeoPixel". Look for "Adafruit NeoPixel by Adafruit" and select the latest version by clicking on the dropbox menu next to the Install button. Then click on the Install button. After it's installed, you can click the "close" button.

![alt text](http://www.switchdoc.com/wp-content/uploads/2018/05/leds_arduino-library-manager.png)


##Hardware Installation <BR>

Connect a Grove Connector from D6 to the INPUT of the 8 Pixel Strip


Compile and Run SDL_ESP8266_8PixelStick.ino on your Arduino IDE and watch the lights change<BR>

![alt text](http://www.switchdoc.com/wp-content/uploads/2018/05/IMG_5713.jpg) 

##To Modify

Change the following at the top of the file to use other pins are if you are chaining 8 pixel strips.

<pre>

#define PIN 6

#define NUM_LEDS 8
</pre>

