# ExFAB Arsenal

To support accessible and reproducible lab automation, this repository contains all 3D‑printable tools designed at the ExFAB Biofoundry, compatible with multiple automation platforms.

## Supported Platforms

- Opentrons
- Tecan

## Repository Structure

The repository is organized by labware type reflecting how automation systems interface with physical geometry and standards. The `src` directory contains all design files grouped by labware classes (e.g., SBS plates, tube formats). Platform compatibility and specific use cases should be indicated in accompanying documentation. The `templates` directory provides standardized documentations to ensure consistency across contributions.  

```
├── src
│   ├── plates
│   │   ├── 96_well_ns_sbs
│   │   └── ...
│   ├── tube_holders
│   └── ...
└── templates

```

## Contributing

We welcome improvements, additional platform support, and workflow-driven tooling.

Please include the following files within the appropriate folder:
- STL files for all printable components
- Source design files (Fusion, Blender etc.) whenever possible
- Platform-specific labware files, if applicable (e.g., .json for Opentrons, .zeia for Tecan), so parts can be used directly on supported systems.
- At least one preview image (render or photo of the printed part)
- A README document (you may use the provided template), including:
  - Description
  - Origin
  - Compatible platforms
  - Version
  - Print settings
  - Tested information
  - Notes
Clear documentation and print validation details are strongly encouraged to ensure reproducibility and reliability.


## Disclaimer

These components are not manufacturer-certified and are provided as open-source designs.
Users are responsible for validating fit, mechanical stability, and deck offsets before use.
All parts should be thoroughly tested and verified prior to running automated workflows or experiments.
Use at your own risk.

## Attribution and Citation

This repository contains both **original designs developed by ExFAB** and **third-party designs** sourced from external repositories.

Third-party models retain their original licenses and attribution requirements. Please refer to the README and license information within each model's folder for the original source and citation instructions.

If you use **original designs developed by ExFAB** in publications, presentations, or other work, please cite:

*ExFAB Arsenal. Open-source hardware toolkit for laboratory automation. GitHub repository. Available at: https://github.com/exfab/ExFAB-Arsenal. Accessed: 2026-02-19.*


## License

See LICENSE file for details.


