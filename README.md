# Interfacing-keypad-using-ESP32
Interfacing a simple 4X4 keypad using ESP32.

## Reference
https://esp32io.com/tutorials/esp32-keypad

## Components used
ESP32, 4x4 keypad, jumper wires.

Connections: connect ESP32 to computer using USB cable. Connect the pin r1 to GIOP19, r2 to GIOP18, r3 to GIOP05, r4 to GIOP17, c1 to GIOP16, c2 to GIOP04, c3 to GIOP0 and c4 to GIOP02. 

## Theory
Keypad is a bunch of buttons arranged in a matrix, where each button represents a key. We access keys using pins provided.
We are using a keypad to authenticate. Here we have pre-defined a password in code, if a user types the same, access is granted else not.

## Code
### Printing key pressed on a serial monitor
https://github.com/meghana-23-7/Interfacing-keypad-using-ESP32/blob/main/sketch_task6Interfacing.ino

### Interfacing password
https://github.com/meghana-23-7/Interfacing-keypad-using-ESP32/blob/main/sketch_task6Print.ino


## Output

### Trying to print the key pressed
Key pressed on the keypad was accurately printed on the serial monitor.

### Verifying password: password was correctly verified.
