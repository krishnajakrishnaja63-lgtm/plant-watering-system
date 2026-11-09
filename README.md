# Automatic Plant Watering System

An Arduino UNO based irrigation prototype that waters a plant automatically when the soil gets dry.

## Components
- Arduino UNO
- Soil moisture sensor
- Relay module
- DC water pump
- Power supply and jumper wires

## How it works
1. The soil moisture sensor reads the moisture level of the soil.
2. The Arduino compares the reading with a set threshold.
3. If the soil is drier than the threshold, the Arduino switches the relay on and the pump waters the plant.
4. When the moisture rises back above the threshold, the pump is switched off.

## Key points
- Sensor threshold calibrated to reduce water wastage
- Pump timing tuned for low-maintenance plant care
- Threshold is configurable in the code

## Author
Krishnaja G, EEE undergraduate, Rajiv Gandhi Institute of Technology, Kottayam
