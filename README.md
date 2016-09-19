# MySensors_v2.0_Uno
A MySensors v2.0 compatible sketch for the node hardware based on the Arduino Uno, with protoype daughterboard containing 
nRF24L01+ and DS18B20. Structure of project is PlaformIO compatible (>=v3.0.0b13 of the PlatformIO CLI, IDE v1.4.0) 

Hardware Connections (Breakoutboard to Arduino):
 -VCC = 3.3V
 -GND = GND
 -SDA = A4 (use inline 10k resistor if your board is 5V)
 -SCL = A5 (use inline 10k resistor if your board is 5V)

Arduino Uno R3, DS18B20 on A0 (also known as Digital Pin 14)

System Clock  = 16MHz
