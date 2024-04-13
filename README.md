# arduino-helldivers-menu
<h3> Description </h3>
The application is meant to show the user an OLED menu depicting various Stratagems seen in Helldivers 2. The user can scroll through the options via buttons. The menu is meant to be reminiscent of the menu of the Flipper 0. Future functionalities should include the ability to select a stratagem, after which a macro is run (a combination of up-down-left-right keys) for ease of activating stratagems in the game, which requires the user to quickly input a specific combination of the aforementioned keys (for example, UP-RIGHT-DOWN-DOWN-DOWN).

<h3> Limitations </h3>
Unfortunately, the Arduino Uno does not have the core keyboard library, and therefore cannot act as a keyboard for the system. This makes the goal impossible with the Arduino Uno without giving the Uno the required HID firmware, which is done with specific cables that I currently do not have.

<h3> Software used </h3>
IMAGE TO BITMAP CONVERTER: https://javl.github.io/image2cpp/
ONLINE PHOTO EDITOR: https://www.photopea.com/
SYSTEM SIMULATOR: https://wokwi.com/
IDE: https://www.arduino.cc/en/software

<h3> Hardware used </h3>
1x Arduino Uno
1x Screen OLED 0.91” IC:SSD1306 128x32
1x Breadboard 400
9x Dupont Wires
1x USB A/B Cable
4x Buttons

<h3> Thanks to </h3>
@upir_upir on Youtube for their tutorial: https://www.youtube.com/watch?v=HVHVkKt-ldc&t=22s
