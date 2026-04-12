# Assignment – LTspice Ideal vs Practical Diode Comparison

## Objective
This simulation compares an ideal diode model and a practical 1N4148 diode model using a DC sweep from 0 V to 5 V.

## Circuit
The same circuit was used in both cases:
- DC source V1
- 1 kΩ resistor
- diode to ground

## Comparison
The ideal diode starts conducting immediately at almost 0 V. Therefore, the current increases linearly from the beginning of the sweep and reaches approximately 5 mA at 5 V.

The practical 1N4148 diode behaves differently. From the DC sweep graph, the diode starts conducting at around 0.65 V. Before this voltage, the current is almost zero. After turn-on, the current rises linearly and reaches approximately 4.4 mA at 5 V.

This difference happens because real silicon diodes require forward threshold voltage before conduction.

Ideal models are still useful because they simplify circuit analysis and make hand calculations easier.

However, ideal models become inaccurate when real forward voltage drop, switching speed, and power loss are important.
