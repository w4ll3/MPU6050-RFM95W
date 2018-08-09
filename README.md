# Introduction
This aplication is an usage example of the MPU6050 sending information via the RFM95W transceptor.
# Assembling
To assemble this example we used an Arduino Nano for the LoRa transceptor and the MPU accelerometer and for receiving the information an ESP32 + LoRa was utilized.
The following connections need to be made:

NANO  | MPU6050
------|------
<center>
D3|INT
A4|SDA
A5|SCL
+5V|VIN
GND|GND
</center>
