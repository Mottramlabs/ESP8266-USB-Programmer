# ESP8266-USB-Programmer

Description
A USB programmer for the ESP8266 chips from Espressif Systems. This board uses the CH340 USB to serial interface to program the ESP devices. The board also uses the GPIO0 and Reset lines to aid programming, just as Wemos and NodeMCU development modules. Uses the Arduino IDE. Connection is via a Type B USB socket,

# Pin Connections
Pin   Name    Function
1     RST     Reset from Programmer
2     3V3     3V3 from programmer(optional)
3     GND     Ground common connection
4     TX      TX connection
5     RX      RX connection
6     GPIO0   Used to signal the ESP’s bootloader


