# # Two-Stage Operational Amplifier Design with Miller Compensation and Nulling Resistor

## Overview
This project involves the design of a two-stage operational amplifier (opamp) enhanced with Miller compensation and a nulling resistor to improve stability and performance. The design and simulation were carried out using Cadence Virtuoso.

## Key Features
- **Two-Stage Opamp Architecture**: Includes a differential amplifier and gain stage for high input impedance and gain.
- **Miller Compensation**: Enhances stability by introducing a Miller capacitor, shifting the dominant pole, and improving the phase margin.
- **Nulling Resistor**: Used to counteract the potential right-half plane zero introduced by the Miller capacitor, further improving stability.

## Analyses Conducted
- **DC Analysis**: Verified the proper operation of the opamp by observing the behavior of input and output voltages within and outside the saturation region.
- **Stability (STB) Analysis**: Identified the need for Miller compensation due to a negative phase margin (-15.3°) and gain margin (-20 dB).
- **Parametric Analysis**: Determined the optimal values for Miller capacitance and the nulling resistor.
- **AC Analysis**: Evaluated the phase margin (73°) and gain margin (1.1 dB) over a frequency range of 1 Hz to 1 GHz.
- **XF Analysis**: Measured the closed-loop output impedance, with a peak value of 3.27 kΩ at 127 MHz.
- **Temperature Variation Analysis**: Observed the decrease in phase margin with increasing temperature.

## Results
- **Optimal Values**: Miller capacitance: 1 pF, Nulling resistor: 4 kΩ.
- **Performance Improvements**: Phase margin increased from -15.3° to 73°, and gain margin improved from -20 dB to 1.1 dB.

## Applications
The designed opamp is suitable for various applications, including signal conditioning, analog filters, sensor interfaces, data acquisition systems, voltage followers, comparators, and audio amplifiers.

## Conclusion
Miller compensation and the nulling resistor significantly enhance the stability and reliability of the two-stage opamp, making it suitable for a wide range of analog circuit applications.
