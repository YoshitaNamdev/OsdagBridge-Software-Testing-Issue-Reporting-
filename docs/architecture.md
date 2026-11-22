# OsdagBridge Architecture Overview

- **Author:** Yoshita Namdev
- **Developer:** Yoshita Namdev
- **Maintainer:** Yoshita Namdev
- **Project Type:** Individual Project

## System Architecture

OsdagBridge is structured around a shared Python engineering core (`src/osdagbridge/core/`) that powers the desktop application (`src/osdagbridge/desktop/`), command-line interface (`src/osdagbridge/cli/`), and web stack (`web/`).

- **Core Calculation Engine (`osdagbridge.core`):** Implements parametric bridge geometry, IRC/IS code provisions (`core/utils/codes/`), 3D grillage finite-element modeling (`ospgrillage` / `OpenSeesPy`), limit state design checks (`core/bridge_types/plate_girder/`), Bill of Quantities (`core/boq/`), and automated PDF/LaTeX report generation (`core/reports/`).
- **Desktop GUI (`osdagbridge.desktop`):** PySide6 user interface providing interactive input docks, 2D/3D OpenCASCADE CAD views, structural response plots, and report customization dialogs.
- **Verification & Testing Suite (`tests/`):** Automated Pytest verification suite covering unit, integration, scenario, and reporting tests across 95 registered test cases.
