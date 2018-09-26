# Multiboard by Espablo
Supla for ESP8266
Firmware v2.7.2

Source code: https://github.com/SUPLA/supla-espressif-esp


Supported modules:
- inCan,
    GPIO2 - Temperature<br />
    GPIO4 - Sensor1
    GPIO16 - Sensor2
    GPIO14 - Button1
    GPIO12 - Button2
    GPIO5 - Relay1
    GPIO13 - Relay2
    GPIO0 - Button Configure (5s)
    GPIO4 - Input CFG (x10)
    GPIO2 - LED CFG

- inCan RollerShutter,
    GPIO2 - Temperature
    GPIO4 - Sensor1
    GPIO16 - Sensor2
    GPIO14 - Button1
    GPIO12 - Button2
    GPIO5 - Relay1
    GPIO13 - Relay2
    GPIO0 - Button Configure (5s)
    GPIO4 - Input CFG (x10)
    GPIO2 - LED CFG

- Sensors x8,
- SONOFF BASIC,
- SONOFF TH,
- SONOFF TOUCH,
- SONOFF TOUCH DUAL,
- SONOFF TOUCH TRIPLE,
- SONOFF_4CH,
- Yunshan,
-------------------------------------------------

Initial parameters for "ESP Falsh Download Tool":

CreystalFreq    26M

SPI SPEED       40 MHz

FLASH MODE      DOUT

BAUDRATE        115200

-------------------------------------------------

FLASH SIZE      8Mbit (1MByte)

multiboard_1024_dout_eagle.flash.bin-------->0x00000

multiboard_1024_dout_eagle.irom0text.bin---->0x40000


