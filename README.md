# college-arduino-bt-car
College project involving a car controlled by an Arduino MEGA via Bluetooth also featuring a Ultrassonic Sensor.

- Bluetooth Module: **ZS-040 (HC-06)**
	- https://www.martyncurrey.com/arduino-and-hc-06-zs-040/
		- "There are several slightly different versions of the HC-06, however, all seem to use the same firmware and have the same AT commands."
		- "The Bluetooth module the ZS-040 is based on, the EGBT-046S, is a 3.3V device. The HC-06 breakout board has a 3.3v regulator that allows a larger input voltage to be used, in the range of 3.6 to 6 volts. The RX pin can still only accept 3.3V though. This means a voltage divider is required to connect to a 5V Arduino. A simple voltage divider can be created using 2 resistors. I am using a 1K ohm resistor and a 2K ohm resistor. The Arduino will read 3.3V as a HIGH so the HC-06 TX pin can be connected directly to the Arduino."
			- (img)
	- https://www.alldatasheet.net/datasheet-pdf/pdf/1253161/ETC1/ZS-040.html
	- (img)

---

- [ ] code.ino variables' names is basically all wrong because I consider the wrong schematics
