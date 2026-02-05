<p align="center">
  <img src="https://github.com/philippebourcier/SilentSight/blob/main/silentsight-v1.svg?raw=true" alt="SilentSight" width="300">
</p>

# SilentSight

SilentSight captures and analyzes PC/Mac/machine tools screens, interprets human-readable JSON instructions sent by humanoïd robots via API, and controls the target system via <a href="https://github.com/philippebourcier/SilentHID" alt="SilentHID">SilentHID</a>.

## Features

- **HDMI (or VGA) Screen Capture with Passthrough** - Captures screen output while allowing it to continue to the display.
- **JSON API for Instructions** - Receives JSON instructions from the humanoïd robot that are translated into steps.
- **Real-time Screen Analysis** - Analyzes the captured screen with a VLM for accurate execution of instructions.
- **Integration with SilentHID** - Sends keyboard and mouse commands to SilentHID for controlling the target system.

SilentSight is working with SilentHID to provide a comprehensive robotic control system for RPA and human-in-the-loop operations.
