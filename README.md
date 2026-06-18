# Swing Ride Simulation

A custom swing ride attraction with a rigged ride vehicle. 

## Overview

This project simulates a swing ride attraction in Unreal Engine. Blueprint logic constructs and transmits OSC messages reflecting the ride vehicle's real-time state (e.g. swing angle, rotation speed). TouchDesigner receives these messages and uses them to drive an audio-reactive lighting system, syncing the show lighting to the physical motion of the ride in real time.

The ride vehicle itself was modeled in Blender.

## Repository Contents

- **Blender file** — ride vehicle mesh, rig, and materials
- **TouchDesigner file** — TouchDesigner patch recieving OSC message and translating it into color value 
- **Unreal script** — Blueprint logic for OSC message construction and transmission

## Tools

Blender · Unreal Engine (Blueprints, OSC) · TouchDesigner

## Next Steps

Drive the visual appearance of the ride by the color value developed in TouchDesigner. 
