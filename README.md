# D2W Open-Source Wheeled Robotics Project

[![Project](https://img.shields.io/badge/Project-D2W-2E8B57?style=flat-square)](https://github.com/Kinatric/d2w)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=flat-square)](#project-status)
[![Hardware license](https://img.shields.io/badge/Hardware-CERN--OHL--W--2.0-blue)](LICENSING.md) [![Software license](https://img.shields.io/badge/Software-GPL--3.0--or--later-blue)](LICENSING.md)

[![Watch the Kinatric D2W introduction video on YouTube](https://img.youtube.com/vi/CxxLvUWkfug/hqdefault.jpg)](https://youtu.be/CxxLvUWkfug)

D2W is an open-source wheeled robot built on the Kinatric robotics platform. This repository contains mechanical design exports, manufacturing drawings, 3D-printable parts, and a bill of materials, with links to companion software repositories.

## Project Status

D2W is under development. The hardware resources below are available in this repository. Assembly and calibration instructions have not yet been published. Check the companion repositories for supported D2W configurations, installation steps, and runtime requirements.

## Hardware Resources

| Resource | Contents |
| --- | --- |
| [Bill of materials](bom/bom.xlsx) | Components, specifications, images, and quantities |
| [CAD and drawings](cad/) | STEP models and PDF manufacturing drawings |
| [Machining list](cad/D2W-Machining-List.xlsx) | Part quantities, materials, and surface finishes |
| [Lower-leg and wheel components](cad/D2W-Lower-Leg/) | Lower-leg, drive-wheel bracket, and bearing end-cap designs |
| [3D-printable parts](3dprint/) | STL models for housings, covers, and brackets |
| [Flashing tools](tools/README.md) | Vendor-hosted Windows tool downloads |

Part numbers are retained to match the drawings and BOM. Files prefixed with `Mirrored-` identify mirrored variants.

## Software Repositories

| Purpose | Repository |
| --- | --- |
| D2W policy training | [Kinatric/d2w_rl_lab](https://github.com/Kinatric/d2w_rl_lab) |
| Deployment | [Kinatric/rl_sim2real](https://github.com/Kinatric/rl_sim2real) |
| API | [Kinatric/api](https://github.com/Kinatric/api) |
| Android | [Kinatric/android](https://github.com/Kinatric/android) |
| iOS | [Kinatric/ios](https://github.com/Kinatric/ios) |

Each repository documents its own setup, usage, compatibility, and licensing.

## Clone the Repository

```bash
git clone https://github.com/Kinatric/d2w.git
cd d2w
```

## Community

[YouTube](https://youtube.com/@kinatric) · [Discord](https://discord.gg/AZUQdNnSN) · [Facebook](https://facebook.com/kinatric) · [LinkedIn](https://www.linkedin.com/company/136176620/)

## Contributing

Use [Issues](https://github.com/Kinatric/d2w/issues) to report problems or suggest improvements. Include the relevant part numbers, hardware/software versions, reproduction steps, and supporting images or logs. Changes to mechanical, electrical, or control interfaces should include validation results.

Write documentation, code comments, templates, and user-facing text in English. Preserve existing license and attribution notices.

## License

Kinatric-owned hardware designs and associated manufacturing documentation are licensed under **CERN-OHL-W-2.0**. Kinatric-owned software, firmware, and trained policy weights are licensed under **GPL-3.0-or-later**, subject to the coverage and provenance requirements in [LICENSING.md](LICENSING.md).

PCB designs and PCB source files are proprietary and excluded from the hardware license grant. Native CAD part and assembly files remain private; published mechanical files are exports. The license's Complete Source obligations still apply.

Third-party material retains its original terms and attribution; see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). Full license texts are in [LICENSES/](LICENSES/), and hardware files have matching `.license` notices.
