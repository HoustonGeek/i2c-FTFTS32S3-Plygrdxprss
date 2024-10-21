# i2c-FTFTS32S3-Plygrdxprss

This example code shows How connect two Device using I2C bus interface.  This will be very useful when your project need multiple device and control/communicate each other.  For example Adafruit Circuit Playgorund Express comes with several sensors and RGB LED's etc, we can read/write from other device.  The Adafruit Feather TFT ESP S3 is well documented, but it is a microprocessor with BLE-LE and Wifi, and can run a web server.  

# Hardware used 
    a. Adafruit Feather TFT ESP32-S3 (ESP32)
    b. Adafruit Circuit Playgorund Express (PGE)
    c. connecting wires 

Integrating the ESP32 and Adafruit Circuit Playground Express board using I2C communication. Here the ESP32 as master device and playground as slave. Master can send a commands to slave device using I2C bus. Slave Device will receive 
commands. This example code simply On OFF RED LED on the board.

# Wiring 

ESP32 - USB -> 3.3V on PGE
ESP32 - GND -> GND on PGE
ESP32 - SCA -> SCA on PGE
ESP32 - SCL -> SCL on PGE



# Steps 
    a. Connect Adafruit Circuit playground Express and upload playground receiver code.
    b. Connect  ESP32 and  upload ESP32  master code



# Reference 

https://www.adafruit.com/product/3333
https://www.adafruit.com/product/5483
https://www.arduino.cc/en/Reference/Wire