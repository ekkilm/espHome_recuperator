# EspHome recuperator project

![Setup](https://drive.google.com/uc?export=view&id=15n5Hxg3Yx9Xn9xuNVVZ8pNVCahk-ZVsF)

### Description
The E-Extra EER series heat recovery unit is designed for constant air exchange in the room. The device is equipped with a regenerator that accumulates the thermal energy of the air leaving the room and heats the fresh air entering the room, thus ensuring minimal heat loss.

In this project, the operation of the recuperator is controlled by an ESP32 microcontroller. The original circuit breaker of the device was replaced by an ESP32, and the "M200 2a (250v)" relay has been replaced by a solid state relay "ASR-06DA (3-32Vdc/24-280Vac 6A)", which controls the fan current power with PWM.

The operation of the device can be controlled locally with the Rotator Encoder (ky-040).

Or...
The device is also integrated into the Home Assistant, so it can also be controlled in the Home Assistant by turning the switch on/off, setting the fan speed with the slider. This also enables all kinds of other automations, whatever you want to do with Home Assistant.

### HA dashboard
![HA_Setup](https://drive.google.com/uc?export=view&id=1rug0GrO5NXNkyhwpLsRPXZXKv4TGtyl5)

### Schema
![Pinout](https://drive.google.com/uc?export=view&id=16xxMSrrb5SOsrR6i8P5eC5VUrEPZPX_I)


### Device details
https://www.europlast.lv/en/products/category/Heat-recovery-units-Europlast
