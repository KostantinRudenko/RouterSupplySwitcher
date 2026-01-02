## RouterSupplySwitcher
RouterSupplySwitcher is a device designed for automatic power source switching for a router.

The device ensures uninterrupted router operation by automatically selecting the available power source and providing a stable 12V output.

## Hardware components

### Power input/output
- Barrel Jack ×2 (input/output)
- USB-A (output)
- USB-C (input)

### Power conversion
- XL6009 DC-DC boost converter
- Potentiometer 10 kΩ (output voltage adjustment)

### Protection and power routing
- Schottky diode SS34
- General-purpose diodes ×2

### Passive components
- Resistor 330 Ω
- Capacitors:
  - 220 µF ×1
  - 100 µF ×1
  - 0.1 µF ×2

Detailed wiring and connections are provided in the electronic schematic (PDF).

## Operating principle

The device accepts power from Barrel Jack or USB-C inputs.
If external power is present, the router is powered directly from the input source while maintaining a regulated 12V output.

In case of input power loss, the power path automatically switches, ensuring uninterrupted router operation.
Input voltage may vary between 5V and 12V, while the output voltage is regulated to a fixed 12V using a DC-DC boost converter.


