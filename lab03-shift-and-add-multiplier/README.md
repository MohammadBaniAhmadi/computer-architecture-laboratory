# 4-bit Shift-and-Add Multiplier

**Computer Architecture Laboratory — Experiment 03**

A sequential 4-bit-by-4-bit multiplier using shift registers, accumulation, clock counting, and control logic.

## Design highlights

- Shift-register based operands
- Sequential accumulation of partial products
- Completion indication after the required clock cycles

## Repository contents

- `shift_and_add.pdsprj` — original Proteus project (editable schematic)
- `docs/Report.pdf` — original report

## How to open the project

1. Install **Proteus Design Suite** with schematic-design support. The exact original software version has not been established.
2. Open **`shift_and_add.pdsprj`** in Proteus.
3. Keep the `.hex` files (if present) next to the Proteus project. If the simulator displays a missing ROM/EPROM file, update the memory component’s file path to the corresponding local `.hex` file.
4. Inspect the schematic and follow the original project report for operation and intended behavior.

> **Verification:** The supplied design files are preserved, and their project archives passed integrity checks. Electrical simulation has **not** been executed or validated here because Proteus is not available in this environment.

## Documentation

The [original project report](docs/Report.pdf) describes the circuit design and provides supporting figures. Some reports are written in Persian.

## Attribution and reuse

This is a collaborative academic laboratory project. Contributor details are recorded in the accompanying report. The repository does **not** include an open-source license; obtain permission from the relevant contributors before redistributing or reusing the material beyond applicable permissions.
