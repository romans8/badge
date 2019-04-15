<h2> BSidesIowa 2019 Badge </h2>
The badge for BSidesIowa 2019 conference is a penny piano running on an ESP32 microcontroller running micropython.
This badge is fully rechargeable and all that is required to program it is a micro usb cable. 

<h3> Micropython </h3>
The micropython REPL prompt can be accessed using a serial console running at 115200 baud. 
Documentation for micropython can be found here, https://docs.micropython.org/en/latest/esp32/quickref.html

<h3> To program </h3>
The badge can be programmed directly through the REPL prompt on the serial console. To load new files onto the ESP32, first access the serial console and press Ctrl+C to end the running program on the board. Then, exit the serial console and use ampy.py to load new programs. Instructions to install ampy can be found here, https://learn.adafruit.com/micropython-basics-load-files-and-run-code/install-ampy

Common ampy commands:<br>
ampy -p /dev/ttyUSB0 put main.py
ampy -p /dev/ttyUSB0 ls 
