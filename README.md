
# Swing Ride Simulation

A custom swing ride attraction with a rigged ride vehicle. 

<img width="357" height="275" alt="Screenshot 2026-06-17 at 9 37 55 PM" src="https://github.com/user-attachments/assets/7b4fa333-c722-43e3-8b10-e987eb369b45" />
<img width="396" height="307" alt="Screenshot 2026-06-17 at 9 57 36 PM" src="https://github.com/user-attachments/assets/e6782551-d393-4262-918f-1c3ddc82ca60" />

## Overview

This project simulates a swing ride attraction in Unreal Engine. Blueprint logic constructs and transmits OSC messages reflecting the ride vehicle's real-time state (e.g. swing angle, rotation speed). TouchDesigner receives these messages and uses them to drive an audio-reactive lighting system, syncing the show lighting to the physical motion of the ride in real time.

The ride vehicle itself was modeled in Blender.

## Repository Contents

- **Blender file** — ride vehicle mesh, rig, and materials
- **TouchDesigner file** — TouchDesigner patch recieving OSC message and translating it into color value 
- **Unreal script** — Blueprint logic for OSC message construction and transmission
- **Demo Video** — As the ride spins, watch the yaw value drive the color of a node in TouchDesigner 

## Tools

Blender · Unreal Engine (Blueprints, OSC) · TouchDesigner

## Next Steps

Drive the visual appearance of the ride by the color value developed in TouchDesigner. 
