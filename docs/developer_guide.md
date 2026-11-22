# OsdagBridge Developer Guide

- **Author:** Yoshita Namdev
- **Developer:** Yoshita Namdev
- **Maintainer:** Yoshita Namdev
- **Project Type:** Individual Project

## Development Workflow

1. **Environment Setup:**
   Create and activate the Conda environment from `environment.yml`, then install the package in editable mode (`pip install -e .`).
2. **Code Organization:**
   - Core bridge components: `src/osdagbridge/core/bridge_components/`
   - Plate girder analysis & design: `src/osdagbridge/core/bridge_types/plate_girder/`
   - Design codes (IRC:5, IRC:6, IRC:22, IRC:24, IRC:112, IS 800): `src/osdagbridge/core/utils/codes/`
   - Automated report generator & styling: `src/osdagbridge/core/reports/`
3. **Testing & Quality Assurance:**
   Run the complete verification suite with `pytest -v` before committing changes. Detailed testing guidelines and defect tracking are available under `documentation/` and `test_results/`.
