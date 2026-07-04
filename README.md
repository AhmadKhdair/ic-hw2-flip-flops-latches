# IC HW2 — Latches & Flip-Flops (SPICE + Electric VLSI)

Integrated Circuits (IC) course, Homework 2. Transistor-level design and
simulation of sequential logic cells:

- **Transparent latch** — CMOS latch, verified for both transparent-high and
  transparent-low behavior.
- **Rising-edge D flip-flop** — master-slave flip-flop built from two latches.

Each cell was designed as a schematic in Electric VLSI and simulated at the
transistor level with SPICE to verify timing behavior (propagation delay,
setup/hold, waveform correctness).

## Structure

```
schematics/            Electric VLSI library (.jelib) with the flip-flop/latch schematics
spice/                 SPICE netlists (.spi) for the latch and rising-edge flip-flop
simulation-results/    Waveform, schematic, and layout snapshots from simulation
docs/                  Full homework report (Report.pdf)
```

## Reproducing the simulation

- Open the `.jelib` file in [Electric VLSI](https://www.staticfreesoft.com/) to view/edit the schematic and layout.
- Run the `.spi` netlists directly in any SPICE simulator (e.g. ngspice, LTspice) to reproduce the waveforms in `simulation-results/`.

---
Author: Ahmad Khdair
