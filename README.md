# Reflectance-Measurement-System-ESP32

Reflectance measurement system using dual photodiodes, op-amp differential amplification (gain 10), and an ESP32 microcontroller for surface reflectivity experiments.

> ⚠️ **Status:** Work in progress  
> This reflectance measurement system is an early prototype.  
> Circuit values, simulations, and ESP32 firmware are still being tuned and will be updated over time.

## Overview

Transmitted light is directed onto a target surface and sensed by a first photodiode, while a second photodiode measures the reflected beam. Their outputs are buffered by op-amp voltage followers and fed into a differential amplifier with a gain of 10, whose output is read by the ESP32 ADC for reflectivity estimation.

## Next steps

- Select and calculate resistor values for the photodiode and op-amp stages.  
- Validate the differential amplifier gain and dynamic range in Proteus.  
- Implement ESP32 ADC reading and basic serial output of the reflectance value.
