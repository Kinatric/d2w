# D2W Open-Source Wheeled Robotics Project

[![Project](https://img.shields.io/badge/Project-D2W-2E8B57?style=flat-square)](https://github.com/Kinatric/d2w)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=flat-square)](#project-status)
[![Hardware license](https://img.shields.io/badge/Hardware-CERN--OHL--W--2.0-blue)](LICENSING.md) [![Software license](https://img.shields.io/badge/Software-GPL--3.0--or--later-blue)](LICENSING.md)

[![Play the Kinatric D2W introduction video on YouTube](https://img.youtube.com/vi/CxxLvUWkfug/hqdefault.jpg)](https://youtu.be/CxxLvUWkfug)

D2W is an open-source wheeled robot built on the Kinatric robotics platform. This is the main repository for the D2W open-source robotics project. It serves as the starting point for project information, hardware resources, technical documentation, and links to companion software repositories.

This repository connects D2W hardware design, motion data, policy training, simulation validation, and deployment resources. Hardware specifications, software dependencies, and compatibility will be documented with the corresponding releases.

## Project Status

The project is under development. This repository contains project documentation, CAD resources in [`cad/`](cad/), and a bill of materials in [`bom/`](bom/). D2W training code is maintained in [Kinatric/d2w_rl_lab](https://github.com/Kinatric/d2w_rl_lab), and deployment code is maintained in [Kinatric/rl_sim2real](https://github.com/Kinatric/rl_sim2real). PCB design source remains private and is excluded from the hardware license grant. Assembly instructions have not yet been published.

STEP models, PDF drawings, 3D-printable parts, the machining list, and the BOM are available below. Check the companion repositories for supported D2W configurations and runtime requirements.

## Start Here

| Goal | Starting point | Status |
|---|---|---|
| Explore hardware files | [Hardware resources](#hardware-resources) | Available |
| Find D2W training code | [Kinatric/d2w_rl_lab](https://github.com/Kinatric/d2w_rl_lab) | Training repository |
| Find D2W deployment code | [Kinatric/rl_sim2real](https://github.com/Kinatric/rl_sim2real) | Deployment repository |
| Find API code | [Kinatric/api](https://github.com/Kinatric/api) | API repository |
| Find Android code | [Kinatric/android](https://github.com/Kinatric/android) | Android repository |
| Find iOS code | [Kinatric/ios](https://github.com/Kinatric/ios) | iOS repository |
| Report an issue or contribute | [Contributing](#contributing) | Contributions welcome |

### API Code

API code is maintained in [Kinatric/api](https://github.com/Kinatric/api). See that repository's README for API documentation, setup, and usage instructions.

### Android Code

Android code is maintained in [Kinatric/android](https://github.com/Kinatric/android). See that repository's README for setup, build, and usage instructions.

### iOS Code

iOS code is maintained in [Kinatric/ios](https://github.com/Kinatric/ios). See that repository's README for setup, build, and usage instructions.

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

## Clone the Repository

```bash
git clone https://github.com/Kinatric/d2w.git
cd d2w
```

This repository contains documentation and hardware resources. For training code and installation instructions, see [Kinatric/d2w_rl_lab](https://github.com/Kinatric/d2w_rl_lab). For deployment code and runtime requirements, see [Kinatric/rl_sim2real](https://github.com/Kinatric/rl_sim2real).

## Repository Boundaries

- This repository is the main entry point for D2W hardware resources, documentation, and companion software links.
- Each companion software repository will document its own environment, installation steps, and validation requirements.
- Compatibility between hardware, firmware, robot models, and control policies will be documented with releases.

## Community and Social Media

Follow Kinatric and join the community using the links below, or scan a QR code on your phone.

<table>
  <tr>
    <th>YouTube</th>
    <th>Discord</th>
    <th>Facebook</th>
    <th>LinkedIn</th>
  </tr>
  <tr>
    <td align="center"><a href="https://youtube.com/@kinatric"><img src="assets/social/youtube.png" width="160" alt="Kinatric YouTube QR code"></a></td>
    <td align="center"><a href="https://discord.gg/AZUQdNnSN"><img src="assets/social/discord.png" width="160" alt="Kinatric Discord QR code"></a></td>
    <td align="center"><a href="https://facebook.com/kinatric"><img src="assets/social/facebook.png" width="160" alt="Kinatric Facebook QR code"></a></td>
    <td align="center"><a href="https://www.linkedin.com/company/136176620/"><img src="assets/social/linkedin.png" width="160" alt="Kinatric LinkedIn QR code"></a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://youtube.com/@kinatric">Watch on YouTube</a></td>
    <td align="center"><a href="https://discord.gg/AZUQdNnSN">Join Discord</a></td>
    <td align="center"><a href="https://facebook.com/kinatric">Follow on Facebook</a></td>
    <td align="center"><a href="https://www.linkedin.com/company/136176620/">Connect on LinkedIn</a></td>
  </tr>
</table>

## Contributing

Use [Issues](https://github.com/Kinatric/d2w/issues) to report problems, suggest improvements, or request documentation corrections. Pull requests improving documentation and subsequently published resources are welcome.

For technical reports, include hardware and software versions, reproduction steps, logs, and relevant images where possible. Changes to mechanical, electrical, or control interfaces should identify the applicable versions and validation results.

All repository content must be written in English, including documentation, code comments, issue and pull request templates, and user-facing text.

## License

Kinatric-owned software and firmware contributions are licensed under **GPL-3.0-or-later**. Kinatric-owned robot hardware designs and associated manufacturing documentation are licensed under **CERN-OHL-W-2.0**, subject to the file coverage in [LICENSING.md](LICENSING.md). Third-party material retains its original licenses and attribution; see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). Both full license texts are included in [LICENSES/](LICENSES/). Kinatric-owned trained policy weights are also GPL-3.0-or-later; see the coverage table and provenance requirements.

PCB designs and PCB source files are proprietary and excluded from the hardware license grant. Native CAD part and assembly files remain private; published mechanical files are exports. See [LICENSING.md](LICENSING.md) for coverage.
