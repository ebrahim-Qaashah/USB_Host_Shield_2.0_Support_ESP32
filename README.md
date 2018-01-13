
## USB Host Shield with ESP32 Support.





Date: 12 Jan 2018   

---------
- By:  Eng. Ebrahim Qaashah
- ebrahim.amq@gmail.com




| USB Shield               |ESP32                          |Function                        |
|----------------|-------------------------------|-----------------------------|
| VCC |  3.3V  | Power |
| GND |  GND   | Power |
| D9       | GPIO15       |    INT   |
|D10 | GPIO5  |  SPI SS  |
| D11 | GPIO23  |  SPI MOSI  |
| D12 | GPIO19 |   SPI MISO |
| D13 | GPIO18 |   SPI SCK |
|          |  |   |




- I modified  USB host 2.0 library to support ESP32 platform.
- Original library does not support ESP32 platform. you can get it form the following link:
- https://github.com/felis/USB_Host_Shield_2.0
- 
