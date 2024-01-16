# Password Security System

## Aim
This project aims to design and implement a password security system using logic gates to enhance the security of digital systems and applications.

## Components Required
- XOR and NOR gate
- Two eight-position DIP switches
- Two light-emitting diodes
- Four 1N914 "switching" diodes
- Ten 10K ohm resistors and two 470 ohm resistors
- Pushbutton switch
- One 9-volt battery
- Two breadboards
- Connecting wires

## Methodology
A password security system using logic gates works by allowing a user to set a password using the first four inputs. A separate set of four inputs is then used by another user to try to predict the passcode. If the code matches the initial one, a HIGH output is given.

The output terminals of the four XOR gates are connected through a diode network that functions as a four-input OR gate. If any of the four XOR gates outputs a “high” signal, this indicates that the entered code and the key code are not identical. A “high” signal is then passed on to the NOR gate logic.

## Procedure
### Steps Involved
1. Set the power supply to 9 volts and place voltage and ground to the breadboard.
2. Connect voltage to each “key code” switch and each "data entry" switch.
3. Connect a “key code” switch to pins 1, 4, 10, and 13 of the XOR gate, as well as connect a “data entry switch” to pins 2, 5, 9, and 12 of the XOR gate.
4. Connect a 10kΩ resistor to each “key code” switch, as well as to each “data entry” switch.
5. Place a wire from each resistor to ground.
6. Allow a wire to come from pin 3, pin 6, pin 8, and pin 11 of the XOR gate to pins 1, 3, 5, and 9 of the 1N914 “switching” diode.
7. Place a wire from pins 2, 4, 6, and 8 of the 1N914 “switching” diode to a 10kΩ resistor.
8. Place a wire from the 10kΩ resistors to ground.
9. Connect pin 2 of the 1N914 “switching” diode to pin 1 of the NOR gate, as well as a 10kΩ resistor connected to pin 2 of the 4001 quad.
10. Place a wire from pin 3 of the 4001 quad to pin 4 of the 4001 quad and place a wire from pin 5 to the pushbutton switch.
11. Connect the pushbutton switch to ground.
12. Place a wire from pin 6 to a light-emitting diode.
## Circuit Diagram
## Implementation 
## Final Result
