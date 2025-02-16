### Ps2_USB Teensy 2.0++ Mod. 

### Requirements 
```markdown
- A PJRC Teensy 2.0++ with 3.3v Regulator
- Arduino Ide and Teensy repo. Follow:(https://www.pjrc.com/teensy/td_download.html)
```

### Wiring 
Pinout Controller Ps2: 

![Pinout1](http://www.billporter.info/wp-content/uploads//2010/05/wiring.jpg)

Pinout Teensy2.0++ 

![Pinout2](https://www.pjrc.com/store/teensy2pp_card4b_rev2.png)


```markdown
Controller -------> Teensy
- Pin 1 ----------> Pin B3  23 DAT
- Pin 2 ----------> Pin B2  22 CMD
- Pin 3                        NC
- Pin 4 ----------> Pin  ⏚    GND
- Pin 5 ----------> Pin 3,3    VCC
- Pin 6 ----------> Pin B1 21  CLK
- Pin 7 ----------> Pin B0 20  ATT
- Pin 8                        NC
- Pin 9                        NC
```
### Software

- Cp Ps2x_lib in library folder
- Tools -> 
           
           Board -> Teensy 2++

           Port -> Hid: xxx

           Cpu Speed -> 8 to 16

           Usb type -> Keyboard + mouse + joystick
           
- Run the PS2_USB.ino 

### Note
- No Res need.
- Led Flashing means no controller found. 

![Pict1](https://i.ibb.co/Nrszy4Q/IMG-0896.jpg)

