# 12 V DC Input Protection Circuit

## Selected diode
I selected the *1N5819 Schottky diode* for the 12 V DC input protection circuit.

## Justification
The diode is suitable because its voltage rating is safely above 12 V, and its 1 A current rating is enough for a simple low-power DC circuit. It is also inexpensive, widely available, and commonly used for input protection.

A Schottky diode is a good choice because it has a lower forward voltage drop than a normal silicon diode. This reduces power loss and keeps the output voltage closer to the source voltage.

## LTspice result
The simulation gave:
- Input voltage = *12.0 V*
- Output voltage = *11.7023 V*
- Current = *0.117 A*

The diode drop is about *0.30 V*, so the protected output remains close to 12 V. This shows that the circuit works well as a basic DC input protection circuit.
