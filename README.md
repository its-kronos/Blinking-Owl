# Blinking-Owl
An astable multivibrator with flashing LEDs that serve as eyes for an owl.

# Schematic
![image](https://github.com/user-attachments/assets/62d07e14-3de6-47a2-bbdf-333fee625b83)

# PCB

## Front

![image](https://github.com/user-attachments/assets/f8599c5e-118e-42d7-bc29-ced34e97988b)

![image](https://github.com/user-attachments/assets/4768c36a-c10d-4af7-b5b1-2b443bf3efd7)


## Back

![image](https://github.com/user-attachments/assets/ecf22d41-43fa-43ca-9353-39213907336d)

![image](https://github.com/user-attachments/assets/53a5ac6a-c170-48a6-a8b2-8899455d8081)


# BOM

- (2) CR2032 Battery Cell Holders
- (8) 4.7k Ohm Resistors
- (4) 47k Ohm Resistors
- (2) 10 uF Capacitors
- (2) LEDs
- (2) PNP Transistors

# Afterword
- After receiving the parts for the Hackclub "Solder" program, I was surprised that there were (12) 220 ohm resistors and (6) of the 4.7K and 47K ohm resisters, which wasn't explicitly made clear. This taught me that it's always a good idea to double check the available materials to avoid requiring substitutions.
- After ordering the PCB, the parts came around five days later. When I build a prototype on a breadboard, the LEDs wouldn't light up with 5 volts in series, but would only work in parallel, contrary to what a simulation on Falstad showed me. This taught me that it is often better to wire voltage-dependant things in parallel to avoid issues like these. It also helped to understand that even if it takes longer for a build to be completed, prototyping something in real life on something like a breadboard is important to make sure that there are no problems down the road.
- I still figured out a way to make the current PCB work out with the current wiring, which was by adding two wires to connect corresponding legs of the two LEDs while scratching out the currect trace that connected them. Keeping this trace would allow current to flow backwards in an unintended direction to directly go through wires or traces, keeping the LEDs unlit.

# Demonstrations

## Prototype
https://github.com/user-attachments/assets/5ab8c685-fedc-4869-b676-18524e66d9f1


# Attributions
\- Created by its_kronos
