# LED-Controller-PowerDelivery
Controller for WS2812B/SK6812 LEDs specially made for monitor backlighting with [WLED](https://kno.wled.ge/) and [Lightpack](https://github.com/psieg/Lightpack).

[Video example @ YouTube](https://youtu.be/EE_DajBsjAQ)

Controller can be attached to VESA 75 / 100 monitor mount using the case included in this repo.

![Front](https://github.com/dtimber/LED-Controller-PowerDelivery/blob/main/Pictures/LED-Controller-PD_2024-Dec-17_01-49-33PM-000_CustomizedView2065316698.png)


Firmware can be flashed without additional USB power delivery supply connected to J1. Simply use J2 for programming.

Required WLED GPIO Settings:
* GPIO2 -> LED data output
* GPIO15 -> LED power output (WLED relay function)

Additional Parts required:
* 1x USB Power Delivery Supply with 30 W (15V / 2 A)
* 1x USB Type A to C or Type C to C cable
* 3x M3 insert nuts (outer diameter: 4.6 mm / length: 6 mm) for the case
* 3x M3 screws (countersunk head e.g. ISO 10642 / length: 12 mm) for the case
* 1x connector 538-43645-0300 for the LED stripe cable
* 3x contacts 43030-0007 for the LED stripe cable
