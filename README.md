# Computer Architecture Laboratory — GitHub-ready projects

This bundle contains **nine independent Proteus projects**, each in its own repository-ready directory. Every project includes its original `.pdsprj` schematic file, an original report, supporting memory files where supplied, a project-specific README, and `.gitignore`.

| Lab | Project | Description |
|---|---|---|
| 01 | [Three-Digit BCD Adder](lab01-bcd-adder/) | A digital circuit for adding two three-digit BCD numbers, combining full adders with decimal correction and carry propagation. |
| 02 | [6-bit Carry-Select Adder](lab02-carry-select-adder/) | A 6-bit carry-select adder built from 2-bit adder stages and multiplexers to reduce carry propagation delay. |
| 03 | [4-bit Shift-and-Add Multiplier](lab03-shift-and-add-multiplier/) | A sequential 4-bit-by-4-bit multiplier using shift registers, accumulation, clock counting, and control logic. |
| 04 | [IEEE 754 Floating-Point Adder/Subtractor](lab04-floating-point-adder-subtractor/) | A circuit designed for 32-bit IEEE 754 floating-point addition and subtraction, with an operation-select signal. |
| 05 | [Three-Digit BCD-to-Binary Converter](lab05-bcd-to-binary/) | A sequential converter that transforms a three-digit BCD value into binary using repeated shifts, conditional subtraction, and control signals. |
| 06 | [8-bit Register-Based ALU](lab06-8bit-register-alu/) | A simple 8-bit register and arithmetic unit that supports instruction-controlled register selection, addition, and subtraction. |
| 07 | [EPROM Program Execution and Fibonacci](lab07-eprom-fibonacci/) | An extension of the register-based ALU design with EPROM instruction storage and a program counter to execute a Fibonacci sequence program. |
| 08 | [Simple 8-bit Computer](lab08-8bit-computer/) | A simple 8-bit computer with an ALU, register datapath, program and data memory, program counter, and instruction control. |
| 09 | [Microprogrammed Control Unit for an 8-bit Computer](lab09-microprogrammed-control/) | A microprogrammed control implementation for an 8-bit computer, replacing hardwired control with ROM-based microinstructions. |

## Publish a project separately on GitHub

The nine directories are intentionally **not** initialized as Git repositories. For each folder, create a new (preferably empty) repository on GitHub and then run:

```bash
cd lab01-bcd-adder
git init
git branch -M main
git add .
git commit -m "Initial commit: add Proteus project and report"
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

Repeat from the other eight folders, changing the GitHub repository URL accordingly. If the GitHub repository already contains a README/commit, merge the remote history rather than force-pushing.

## Important notes

- **Proteus Design Suite** is required to open/edit/simulate `.pdsprj` files. These are not Logisim projects or source code that can run in GitHub itself.
- Original `.pdsprj` files were not modified or converted. Only folder organization and documentation were added.
- Original PDFs can contain student names/IDs. Review their contents and obtain collaborators’ approval before making the repositories public.
- No license has been added because project-sharing and reuse terms have not been provided.
- Circuit simulations were **not** rerun; only ZIP and project-container integrity was checked.
