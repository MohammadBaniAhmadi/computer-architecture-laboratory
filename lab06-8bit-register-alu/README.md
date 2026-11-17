# 8-bit Register-Based ALU

**Computer Architecture Laboratory — Experiment 06**

A simple 8-bit register and arithmetic unit that supports instruction-controlled register selection, addition, and subtraction.

## Design highlights

- Four 8-bit registers
- Instruction-controlled datapath and destination decoding
- 8-bit ALU for basic arithmetic operations

## Repository contents

- `p6.pdsprj` — original Proteus project (editable schematic)
- `docs/Report.pdf` — original report

## How to open the project

1. Install **Proteus Design Suite** with schematic-design support. The exact original software version has not been established.
2. Open **`p6.pdsprj`** in Proteus.
3. Keep the `.hex` files (if present) next to the Proteus project. If the simulator displays a missing ROM/EPROM file, update the memory component’s file path to the corresponding local `.hex` file.
4. Inspect the schematic and follow the original project report for operation and intended behavior.

> **Verification:** The supplied design files are preserved, and their project archives passed integrity checks. Electrical simulation has **not** been executed or validated here because Proteus is not available in this environment.

## Documentation

The [original project report](docs/Report.pdf) describes the circuit design and provides supporting figures. Some reports are written in Persian.

## Attribution and reuse

This is a collaborative academic laboratory project. Contributor details are recorded in the accompanying report. The repository does **not** include an open-source license; obtain permission from the relevant contributors before redistributing or reusing the material beyond applicable permissions.
