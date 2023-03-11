# ESP32 DSMR Reader

This functionality will read the energy-measurement telegrams from a DSMR P1 port, and publish the changes periodically on dedicated MQTT topics. The current consumption is optionally available on a website hosted on the ESP32, should that be interesting for whatever reason e.g. if you don't have [Home Assistant](https://www.home-assistant.io/) or other application available to display the information published via MQTT.


ALL credit goes to [Robin Rosier](https://github.com/RosiersRobin) and the other developers from where the project was originally cloned.     
For a comprehensive description of the code see    
https://github.com/RosiersRobin/esp32_p1meter.    

This version of the code was addapted slightly because I could not make the original version work with a Kaifa v4 DSMR.

Also see the [ESPHome DSMR](https://esphome.io/components/sensor/dsmr.html) and [Home Assistant DSMR](https://www.home-assistant.io/integrations/dsmr/) integrations for other options.
