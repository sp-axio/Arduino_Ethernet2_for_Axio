Ethernet "2" Library for Arduino  [![Linux build status](https://travis-ci.org/sp-axio/Arduino_Ethernet2_for_Axio.svg?branch=master)](https://travis-ci.org/sp-axio/Arduino_Ethernet2_for_Axio)
================================

This Arduino library is for shields that use the **Wiznet [W5500]** chipset only.
It does **not** work with other chipsets, such as the original Arduino Ethernet shield which
uses the Wiznet [W5100] chipset.

For more information about this library please visit us at: 
http://www.arduino.cc/en/Reference/Ethernet


W5500 Shields
-------------

* [Arduino Ethernet Shield v2](https://www.arduino.cc/en/Main/ArduinoEthernetShieldV2)

== How to use ==

* Install Etherent2 library from Arduino IDE.
* Copy 'w5500.cpp' file from 'src/utility' and overwrite to your Ethernet2 library 'libraries/Ethernet2/src/utility/w5100.cpp'.

* Connect Ethernet Shield v2 to Axio-Builder with jumper wires as shown below.

![w5100 arduino shield](https://raw.githubusercontent.com/sp-axio/Arduino_Ethernet2_for_Axio/master/eth2_w5500_axio.png "w5100 Ethernet shield v2 connect to Axio-Builder")

Note:
* W5500 Ethernet shield uses ICSP pins(SPI) to communicate with the Axio-Builder(Arduino).
* Digital pin 10 is used to SPI SSN.
* This code was tested by the Arduino Ethernet Shield v2.
