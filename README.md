# ESPHome-THR320D-Boiler
ESPHome config for Sonoff THR320D to steer hot water boiler.

Prerequisites
THR320D with DS18B20Cable

Warning - THR320D needs to be temporary disassembled to install initial ESPHome. 
To initial set up - see https://devices.esphome.io/devices/Sonoff-THR320D

THR320d internal relay is cabable to switch up to 20A load. I'd rather preffer and suggest to use external high power relay (3 phase siemens in my case) to safely switch the heater. 
