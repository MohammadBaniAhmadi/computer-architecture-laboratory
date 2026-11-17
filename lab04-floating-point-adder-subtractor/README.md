# IEEE 754 Floating-Point Adder/Subtractor

**Computer Architecture Laboratory — Experiment 04**

A circuit designed for 32-bit IEEE 754 floating-point addition and subtraction, with an operation-select signal.

## Design highlights

- 32-bit floating-point inputs
- Operation-select-controlled addition or subtraction
- Sign, exponent, and fraction processing described in the report

## Repository contents

- `p4.pdsprj` — original Proteus project (editable schematic)
- `docs/Report.pdf` — original report

## How to open the project

1. Install **Proteus Design Suite** with schematic-design support. The exact original software version has not been established.
2. Open **`p4.pdsprj`** in Proteus.
3. Keep the `.hex` files (if present) next to the Proteus project. If the simulator displays a missing ROM/EPROM file, update the memory component’s file path to the corresponding local `.hex` file.
4. Inspect the schematic and follow the original project report for operation and intended behavior.

> **Verification:** The supplied design files are preserved, and their project archives passed integrity checks. Electrical simulation has **not** been executed or validated here because Proteus is not available in this environment.

## Documentation

The [original project report](docs/Report.pdf) describes the circuit design and provides supporting figures. Some reports are written in Persian.

## Attribution and reuse

This is a collaborative academic laboratory project. Contributor details are recorded in the accompanying report. The repository does **not** include an open-source license; obtain permission from the relevant contributors before redistributing or reusing the material beyond applicable permissions.
