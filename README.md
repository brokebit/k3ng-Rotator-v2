# K3NG Rotator Controller

![Schematic](https://github.com/brokebit/k3ng-Rotator-v2/blob/main/schematic.png?raw=true)
![3D Render](https://github.com/brokebit/k3ng-Rotator-v2/blob/main/k3ng-Rotator-v2.png?raw=true)

# LCD2004 Connection
**LCD Pin -> Rotator Pin**
1. 1 (GND) -> GND
2. 2 (VCC) -> +5V
3. 3 (Contrast) -> Center Pin (2) of Contrast Potentiometer
4. 4 (Register Select) -> LCD_RST
5. 5 (Read/Write) -> GND
6. 6 (Enable) -> LCD_EN
7. 7 (Data 0) -> NC
8. 8 (Data 1) -> NC
9. 9 (Data 2) -> NC
10. 10 (Data 3) -> NC
11. 11 (Data 4) -> LCD_D4
12. 12 (Data 5) -> LCD_D5
13. 13 (Data 6) -> LCD_D6
14. 14 (Data 7) -> LCD_D7
15. 15 (Backlight +) -> +5V + Contrast Potentiometer Pin 1
16. 16 (Backlight -) -> GND + Contrast Potentiometer Pin 3
