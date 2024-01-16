# Traffic Light and Pedestrian Signal Simulation using Logisim

## Overview

This Logisim project simulates a basic traffic light and pedestrian signal system. It utilizes two clocks, ROMs, a reset button, splitters, and LEDs to mimic the behavior of traffic lights and pedestrian signals.

## Components

- **Clocks:** Two 4-bit clocks control the timing of the simulation.
- **Reset Button:** Resets the system to a predefined state.
- **ROMs:** Two ROM modules with configurations 4x3 and 4x2 store sequences for traffic and pedestrian signals.
- **Splitters:** Divide the ROM outputs into branches for different components.
- **LEDs:**
  - Upper LEDs (three): Represent traffic lights (red, yellow, green).
  - Lower LEDs (two): Represent pedestrian signals (green and red).

## Functionality

- **Traffic Lights (Upper LEDs):**
  - Sequence controlled by the 4x3 ROM.
  - Red, yellow, and green LEDs light up sequentially.
  - Clock progression determines the state transitions.

- **Pedestrian Signals (Lower LEDs):**
  - Sequence controlled by the 4x2 ROM.
  - Green and red LEDs indicate pedestrian status.
  - Clock progression determines the state transitions.

## Usage

1. Open the Logisim project file.
2. Simulate the circuit to observe the behavior of the traffic light and pedestrian signal system.
3. Utilize the reset button to reset the simulation to a defined state.

## Notes

- Ensure Logisim is properly installed to run the simulation.
- Experiment with different clock timings and ROM configurations for varied behavior.

## Author

Abheesht Mishra


