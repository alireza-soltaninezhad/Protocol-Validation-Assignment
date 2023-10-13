
# Protocol Validation Assignment - Vrije University Amsterdam


## Introduction:
This repository contains a model for the movement and actions of a dockable device, with procedures for horizontal and vertical movement, calibration, emergency actions, and communication actions.

## Features:
1. Defines possible button types (`BUTTON`).
2. Differentiates between various horizontal positions (`HP`).
3. Specifies vertical positions, with considerations for non-distinct heights (`VP`).
4. Indicates horizontal (`HMD`) and vertical (`VMD`) movement directions.
5. Sensor detection for both horizontal and vertical positions.
6. Movement actions for the device in both dimensions.
7. Procedures for the movement and stop actions, including operator stops and automated stops.
8. Calibration, emergency, undocking actions.
9. Communication actions for detecting dock and undock, and for sensing.
10. Actions for braking and releasing brakes.

## How to Use:
The code uses the mCRL2 language and tools for specifying and analyzing concurrent systems. You should have mCRL2 installed to work with the model.

1. Clone the repository to your local machine.
2. Open the model with an mCRL2-compatible editor or toolset.
3. Analyze or simulate the model using mCRL2 tools.

## Directory Structure:
- Main Model File: `filename.mcrl2` (Replace `filename` with the actual file name, which hasn't been provided.)

## Notes:
- When working with the model, remember the purpose of having 5 different vertical positions (`v_lowest`, `v_low`, `v_standard`, `v_high`, `v_highest`). The device can stay at any height in-between, providing a fuzzy range.
- Initial state is set to `Uncal_Undock`.
- Actions and communication patterns are initialized at the end of the model.

