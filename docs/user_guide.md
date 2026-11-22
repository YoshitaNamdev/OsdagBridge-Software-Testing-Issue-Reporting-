# OsdagBridge User Guide

- **Author:** Yoshita Namdev
- **Developer:** Yoshita Namdev
- **Maintainer:** Yoshita Namdev
- **Project Type:** Individual Project

## Using OsdagBridge

1. **Launching the Desktop Interface:**
   Run `python -m osdagbridge.desktop` to open the graphical interface and select the **Plate Girder Bridge** module.
2. **Configuring Bridge Parameters:**
   Enter span length, carriageway width, girder spacing, skew angle, and material grades (structural steel, deck concrete, and reinforcement) in the Input Dock, or load an `.osi` configuration file from `test_cases/`.
3. **Running Analysis & Viewing Results:**
   Click **Design** to execute the 3D grillage analysis and limit state code checks. Inspect 3D CAD geometry, bending moment/shear/deflection diagrams, and utilization ratios in the Output Dock.
4. **Generating Design Reports:**
   Click **Generate Report** to export a complete engineering design calculation report in PDF and LaTeX formats.
