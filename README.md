# dtc_pedestrian
DTC PLC Program for Pedestrian, version 1.0.1

## v1.0.1
- Add version and SN data
- Add 0 value if all lamp off

## v1.0.0
First Release

Feature List
- 3 Mode : **DYNAMIC**, **REGULAR**, **HAZARD**, updated via Push Button, Middleware. Auto change to **HAZARD** at midnight. Auto change to **REGULAR** after loss connection. Autochange to **DYNAMIC** after connection back Online
- 6 State : Idle, Wait Cross, Delay Check, Pedestrian Cross, Yellow, Red Delay
- Countdown Calculation
- Timer Limitation
- Read/Write Data Block from Middleware

