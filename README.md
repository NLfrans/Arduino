HowTo Blink a LED on NodeMCU EPS8266 by using arduino

Follow the movie on https://www.youtube.com/watch?v=NEo1WsT5T7s

 - Install Arduino from https://www.arduino.cc/en/software
 - Plug de USB in your computer
 - Go to https://github.com/esp8266/arduino
 - Copy the link to de board manager URL https://arduino.esp8266.com/stable/package_esp8266com_index.json
 - Open Arduino, click op "File=>Preferences"
 - Past the link to "Additional Boards Manager URLs" and click "OK"
 - Click on "Tools=>Board=>Boards manager"
 - Search for "8266"
 - Click on "Install"
 - When done click on "Close"
 - Click on "Tools=>Board=>ESP8266...=>NodeMCU 1.0 (ESP-12E Module)"
 - Click on "File=>Examples=>ESP8266=>Blink"

 - Replace "LED_BUILTIN" for "D7" 3 times
 - Save the file
 - Click on "Tools=>Port" select the "virtual serial port"
 - Click on "Sketch=>upload"

 - Connect you LED with pin D7 and GND
 - The LED will now blink
