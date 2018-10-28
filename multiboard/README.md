# Multiboard by Espablo
Supla for ESP8266
Firmware v2.7.2

Description https://forum.supla.org/viewtopic.php?f=11&t=3843<br />

GPIO <b>Button</b> and <b>Sensor</b> should have a 4.7k pull-up to 3.3V VCC

<b>Supported modules:</b><br />
<b>- ElectroDragon,</b><br />
    GPIO0 - Button1<br />
    GPIO2 - Button2<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO16 - LED CFG<br />
    GPIO1 - User Configurable<br />
    GPIO3 - User Configurable<br />
    GPIO4 - User Configurable<br />
    GPIO5 - User Configurable<br />
    GPIO14 - User Configurable<br />
    GPIO15 - User Configurable<br />

<b>- inCan,</b><br />
    GPIO2 - Temperature<br />
    GPIO4 - Sensor1<br />
    GPIO16 - Sensor2<br />
    GPIO14 - Button1<br />
    GPIO12 - Button2<br />
    GPIO5 - Relay1<br />
    GPIO13 - Relay2<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO4 - Input CFG (x10)<br />
    GPIO2 - LED CFG<br />
    GPIO1 - User Configurable<br />
    GPIO3 - User Configurable<br />

<b>- inCan RollerShutter,</b><br />
    GPIO2 - Temperature<br />
    GPIO4 - Sensor1<br />
    GPIO16 - Sensor2<br />
    GPIO14 - Button1<br />
    GPIO12 - Button2<br />
    GPIO5 - Relay1<br />
    GPIO13 - Relay2<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO4 - Input CFG (x10)<br />
    GPIO2 - LED CFG<br />
    GPIO1 - User Configurable<br />
    GPIO3 - User Configurable<br />

<b>- Neo Coolcam,</b><br />
    GPIO13 - Button1<br />
    GPIO12 - Relay1<br />
    GPIO13 - Button Configure<br />
    GPIO4 - LED CFG<br />

<b>- RELAYS x9,</b><br />
    GPIO2 - Temperature<br />
    GPIO1 - Relay1<br />
    GPIO3 - Relay2<br />
    GPIO4 - Relay3<br />
    GPIO5 - Relay4<br />
    GPIO12 - Relay5<br />
    GPIO13 - Relay6<br />
    GPIO14 - Relay7<br />
    GPIO15 - Relay8 - this port must have LOW after enabling or resetting the module<br />
    GPIO16 - Relay9<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO2 - LED CFG<br />

<b>- SENSORS x8,</b><br />
    GPIO2 - Temperature<br />
    GPIO4 - Sensor1<br />
    GPIO5 - Sensor2<br />
    GPIO16 - Sensor3<br />
    GPIO12 - Sensor4<br />
    GPIO13 - Sensor5<br />
    GPIO14 - Sensor6<br />
    GPIO3 - Sensor7<br />
    GPIO1 - Sensor8<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO2 - LED CFG<br />

<b>- Shelly 1,</b><br />
    GPIO5 - Button1<br />
    GPIO4 - Relay1<br />
    GPIO0 - Button Configure (5s/x10)<br />

<b>- Shelly 2,</b><br />
    GPIO12 - Button1<br />
    GPIO14 - Button2<br />
    GPIO4 - Relay1<br />
    GPIO5 - Relay2<br />
    GPIO0 - Button Configure (5s/x10)<br />

<b>- Shelly 2 RollerShutter,</b><br />
    GPIO12 - Button1<br />
    GPIO14 - Button2<br />
    GPIO4 - Relay1<br />
    GPIO5 - Relay2<br />
    GPIO0 - Button Configure (5s/x10)<br />

<b>- SONOFF BASIC,</b><br />
    GPIO1 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO14 - Button2<br />
    GPIO12 - Relay1<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />
    GPIO3 - User Configurable<br />

<b>- SONOFF S2X - Sonoff S20, S22 and S26 Smart Socket,</b><br />
    GPIO0 - Button1<br />
    GPIO12 - Relay1<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />
    GPIO1 - User Configurable<br />
    GPIO2 - User Configurable<br />
    GPIO3 - User Configurable<br />


<b>- SONOFF TH,</b><br />
    GPIO14 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO12 - Relay1<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />
    GPIO1 - User Configurable<br />
    GPIO3 - User Configurable<br />

<b>- SONOFF TOUCH,</b><br />
    GPIO2 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO12 - Relay1<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />
    GPIO1 - User Configurable<br />
    GPIO3 - User Configurable<br />

<b>- SONOFF TOUCH DUAL,</b><br />
    GPIO2 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO9 - Button2<br />
    GPIO12 - Relay1<br />
    GPIO5 - Relay2<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO9 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />
    GPIO1 - User Configurable<br />
    GPIO3 - User Configurable<br />

<b>- SONOFF TOUCH TRIPLE,</b><br />
    GPIO2 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO9 - Button2<br />
    GPIO10 - Button3<br />
    GPIO12 - Relay1<br />
    GPIO5 - Relay2<br />
    GPIO4 - Relay3<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />
    GPIO1 - User Configurable<br />
    GPIO3 - User Configurable<br />

<b>- SONOFF_4CH,</b><br />
    GPIO2 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO9 - Button2<br />
    GPIO10 - Button3<br />
    GPIO14 - Button4<br />
    GPIO12 - Relay1<br />
    GPIO5 - Relay2<br />
    GPIO4 - Relay3<br />
    GPIO15 - Relay4<br />
    GPIO0 - Button Configure (x10)<br />
    GPIO13 - LED CFG<br />
    GPIO1 - User Configurable<br />
    GPIO3 - User Configurable<br />

<b>- Yunshan,</b><br />
    GPIO1 - Temperature<br />
    GPIO3 - Button1<br />
    GPIO4 - Relay1<br />
    GPIO5 - Sensor1<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO2 - LED CFG<br />
    GPIO1 - User Configurable<br />

-------------------------------------------------

Initial parameters for "ESP Flash Download Tool":

CrystalFreq     26M

SPI SPEED       40MHz

FLASH MODE      DOUT

BAUDRATE        115200

-------------------------------------------------

FLASH SIZE      8Mbit (1MByte)

multiboard_1024_dout_eagle.flash.bin-------->0x00000

multiboard_1024_dout_eagle.irom0text.bin---->0x40000


