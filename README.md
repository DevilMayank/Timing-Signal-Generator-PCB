# Timing Signal Generator PCB

## Project Overview
This project presents the schematic design and PCB layout of a Timing Signal Generator developed using EasyEDA Pro.

The circuit combines an NE555 timer, a 74LS90 decade counter, a 74LS42 BCD-to-decimal decoder, and an SN74HCT14 Schmitt-trigger inverter.

## Main Components
- NE555 Timer IC
- SN74LS90 Decade Counter
- SN74LS42 BCD-to-Decimal Decoder
- SN74HCT14 Schmitt Trigger Inverter
- 10 Red LEDs with current-limiting resistors
- Resistors and capacitors
- SPDT slide switch
- Tactile push button
- 5V power connector

## Working Principle
The NE555 generates clock pulses that are supplied to the 74LS90 decade counter.

The counter provides a 4-bit BCD output to the 74LS42 decoder, which activates one of ten LED outputs corresponding to decimal values 0–9.

The design also includes a push-button clock circuit using an SN74HCT14 Schmitt-trigger inverter and an AUTO/MANUAL selection switch.

## PCB Specifications
- **Design software:** EasyEDA Pro V3.2.209
- **PCB layers:** 2
- **Board dimensions:** Approximately 102.1 mm × 65.7 mm
- **Power supply:** Regulated 5V DC
- **PCB DRC:** Passed with zero issues
- **Manufacturing files:** Gerber ZIP

## Design Status
The schematic, PCB layout, and Gerber export have been completed. The design has passed EasyEDA's configured DRC checks. Physical hardware functionality has not been tested.

## Author
Mayank Choudhary
