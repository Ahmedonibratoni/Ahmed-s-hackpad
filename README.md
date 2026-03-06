# Ahmed-s-hackpad
My first project. I want to make a macro pad with 6 keys, a rotary encoder for controlling the volume, and 2 LEDs for indicating if volume is turned down to 0 and if the device is turned on
Case for it will be a plain box with no top, because I don't want case at all, but for the requirements i needed to make something.
User will be able to change macro for each key directly in the code that will be flashed to the device when changes are made.
The firmware is not in its final stage, but it will be similar to what it is now, probably with some tweaks because I wasn't able to test it...


<img width="256" height="428" alt="Screenshot 2026-03-06 132009" src="https://github.com/user-attachments/assets/af3655ba-fc04-429c-8cba-2bdf85a94da5" />

<img width="307" height="510" alt="Screenshot 2026-03-06 132025" src="https://github.com/user-attachments/assets/8253f474-a663-40f7-8ac6-43a1dc3de53b" />



BOM was extracted directly from KiCAD
| Id | Designator                   | Footprint                                      | Quantity | Designation            | Supplier and ref|
|----|------------------------------|------------------------------------------------|----------|------------------------|-----------------|
| 1  | SW7                          | RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm | 1        | RotaryEncoder_Switch   |                 |
| 2  | SW6,SW2,SW4,SW3,SW5,SW1      | SW_Cherry_MX_1.00u_PCB                         | 6        | SW_Push                |                 |
| 3  | D2,D1                        | LED_SK6812MINI_PLCC4_3.5x3.5mm_P1.75mm         | 2        | SK6812MINI             |                 |
| 4  | U1                           | XIAO-RP2040-DIP                                | 1        | XIAO-RP2040-DIP        |                 |
