Quick Start
1.	Connect the SEN54 Sensor to your Arduino board's standard I2C bus. Check the pinout of your Arduino unoboard to find the correct pins. The pinout of the SEN54 Sensor board can be found in the data sheet.

SEN5X	Arduino	Jumper Wire
VCC	5V	Red
GND	GND	Black
SDA	SDA	Green
SCL	SCL	Yellow
SEL	GND for I2C	Blue

2.	 
Pin	Name	Description	Comments
1	VCC	Supply Voltage	5V ±10%
2	GND	Ground	
3	SDA	I2C: Serial data input / output	TTL 5V and LVTTL 3.3V compatible
4	SCL	I2C: Serial clock input	TTL 5V and LVTTL 3.3V compatible
5	SEL	Interface select	Pull to GND to select I2C
6	NC	Do not connect	

3.	Open Arduino IDE 
4.	Or try Example File => Examples => Sensirion I2C SEN5X => exampleUsage (Installed library) 
5.	Click the Upload button in the Arduino IDE or
6.	 Sketch => Upload
7.	When the upload process has finished, open the Serial Monitor or Serial Plottervia the Tools menu to observe the measurement values. Note that the Baud Rate in the corresponding window has to be set to 115200 baud.
