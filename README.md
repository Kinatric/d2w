# D2W Open-Source Wheeled Robotics Project

[![Project](https://img.shields.io/badge/Project-D2W-2E8B57?style=flat-square)](https://github.com/Kinatric/d2w)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=flat-square)](#project-status)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue?style=flat-square)](LICENSE)

D2W is the wheeled version of [Kinatric D2](https://github.com/Kinatric/d2), built on the same robotics platform. Most of the project structure and software workflow are shared with D2, with hardware resources and robot configurations adapted for the wheeled version. This is the main repository for the D2W open-source robotics project. It serves as the starting point for project information, hardware resources, technical documentation, and links to companion software repositories.

This repository connects D2W hardware design, motion data, policy training, simulation validation, and deployment resources. Hardware specifications, software dependencies, and compatibility will be documented with the corresponding releases.

## Meet Kinatric at CES 2027

Kinatric will be exhibiting at **CES 2027, January 6-9, 2027**, in Las Vegas, Nevada. Visit our team to learn more about D2, D2W, and our robotics platform.

**Find us at LVCC, South Hall 3 - Booth 40043.**

Venue: Las Vegas Convention Center (LVCC), Las Vegas, Nevada, USA.

| Date | Exhibit hours |
|---|---|
| Wednesday, January 6, 2027 | 10:00 AM - 6:00 PM |
| Thursday, January 7, 2027 | 9:00 AM - 6:00 PM |
| Friday, January 8, 2027 | 9:00 AM - 6:00 PM |
| Saturday, January 9, 2027 | 9:00 AM - 4:00 PM |

All times are local to Las Vegas (Pacific Standard Time, UTC-8). See the [official CES dates and hours](https://www.ces.tech/plan-your-visit/dates-and-hours/) for the latest schedule.

## Product Photos

D2W product photos will be added as they become available. For an introduction to the original D2 platform, see the [D2 repository](https://github.com/Kinatric/d2).

## Project Status

D2W is under development. This repository currently contains project documentation and flashing tool archives in [`tools/`](tools/). D2W CAD files and a bill of materials have not yet been published. Shared D2 platform training code is maintained in [Kinatric/d2_rl_lab](https://github.com/Kinatric/d2_rl_lab), and deployment code is maintained in [Kinatric/rl_sim2real](https://github.com/Kinatric/rl_sim2real). Electronics and assembly instructions have not yet been published.

D2W-specific robot models, wheel control settings, and hardware compatibility will be documented as they become available. The shared software links below are starting points; check each repository for documented D2W support and configurations.

The resource categories and workflow below describe the planned organization. They do not indicate that hardware packages or runnable control software are already available.

## Start Here

| Goal | Starting point | Status |
|---|---|---|
| Explore hardware and manufacturing resources | [Hardware resources](#hardware-resources) | Not yet published |
| Find shared platform training code | [Kinatric/d2_rl_lab](https://github.com/Kinatric/d2_rl_lab) | Training repository |
| Find shared platform deployment code | [Kinatric/rl_sim2real](https://github.com/Kinatric/rl_sim2real) | Deployment repository |
| Find API code | [Kinatric/api](https://github.com/Kinatric/api) | API repository |
| Find Android code | [Kinatric/android](https://github.com/Kinatric/android) | Android repository |
| Find iOS code | [Kinatric/ios](https://github.com/Kinatric/ios) | iOS repository |
| Understand the data, training, and deployment workflow | [Software workflow](#software-workflow) | Planned |
| Get the repository | [Clone the repository](#clone-the-repository) | Available |
| Report an issue or contribute | [Contributing](#contributing) | Contributions welcome |

## Hardware Resources

Hardware resources will be organized into the following categories. File locations, versions, and usage instructions will be added when each resource is published.

| Resource | Planned contents | Status |
|---|---|---|
| Main bill of materials | Part specifications, quantities, and sourcing references | Not yet published |
| Complete mechanical assembly | Full CAD assembly and exchange-format models | Not yet published |
| Manufacturing package | Part models, engineering drawings, and manufacturing requirements | Not yet published |
| 3D-printed parts | Printable models, material guidance, and assembly notes | Not yet published |
| Electronics | Circuit designs, interface definitions, and wiring documentation | Not yet published |
| Embedded firmware | Firmware source and flashing instructions for the corresponding hardware | Not yet published |
| Assembly and calibration | Assembly steps, inspection items, and calibration procedures | Not yet published |

## Software Workflow

The following workflow outlines the software organization. For shared D2 platform training code, see [Kinatric/d2_rl_lab](https://github.com/Kinatric/d2_rl_lab). For deployment code, see [Kinatric/rl_sim2real](https://github.com/Kinatric/rl_sim2real). Follow each repository's README for supported workflows, setup, usage, and validation requirements. Other software entry points will be added as they become available.

```text
D2W hardware models and parameters
                |
                v
Motion data collection and quality checks
                |
                v
Policy training, evaluation, and export
                |
                v
Simulation validation and deployment interface checks
                |
                v
Real-robot commissioning and operation
```

| Stage | Scope | Shared platform repository |
|---|---|---|
| Motion data | Collect or generate motion data, record provenance, and verify quality | To be announced |
| Policy training | Shared platform training code; see the training repository for supported workflows | [Kinatric/d2_rl_lab](https://github.com/Kinatric/d2_rl_lab) |
| Simulation validation | Verify robot models, control interfaces, and policy behavior | To be announced |
| Deployment | Shared platform deployment code; see the deployment repository for supported workflows and runtime requirements | [Kinatric/rl_sim2real](https://github.com/Kinatric/rl_sim2real) |

### API Code

API code is maintained in [Kinatric/api](https://github.com/Kinatric/api). See that repository's README for API documentation, setup, and usage instructions.

### Android Code

Android code is maintained in [Kinatric/android](https://github.com/Kinatric/android). See that repository's README for setup, build, and usage instructions.

### iOS Code

iOS code is maintained in [Kinatric/ios](https://github.com/Kinatric/ios). See that repository's README for setup, build, and usage instructions.

## Clone the Repository

```bash
git clone https://github.com/Kinatric/d2w.git
cd d2w
```

This repository contains documentation and hardware resources. For training code and installation instructions, see [Kinatric/d2_rl_lab](https://github.com/Kinatric/d2_rl_lab). For deployment code and runtime requirements, see [Kinatric/rl_sim2real](https://github.com/Kinatric/rl_sim2real).

## Repository Boundaries

- This repository is the main entry point for D2W hardware resources, documentation, and companion software links.
- Each companion software repository will document its own environment, installation steps, and validation requirements.
- Compatibility between hardware, firmware, robot models, and control policies will be documented with releases.

## Community and Social Media

Follow Kinatric and join the community using the links below.

| Platform | Link |
|---|---|
| YouTube | [Watch on YouTube](https://youtube.com/@kinatric) |
| Discord | [Join Discord](https://discord.gg/AZUQdNnSN) |
| Facebook | [Follow on Facebook](https://facebook.com/kinatric) |
| LinkedIn | [Connect on LinkedIn](https://www.linkedin.com/company/136176620/) |

## Contributing

Use [Issues](https://github.com/Kinatric/d2w/issues) to report problems, suggest improvements, or request documentation corrections. Pull requests improving documentation and subsequently published resources are welcome.

For technical reports, include hardware and software versions, reproduction steps, logs, and relevant images where possible. Changes to mechanical, electrical, or control interfaces should identify the applicable versions and validation results.

All repository content must be written in English, including documentation, code comments, issue and pull request templates, and user-facing text.

## License

This repository is distributed under the [GNU General Public License v3.0](LICENSE).

Referenced projects and third-party resources retain their own licenses and notices. See [LICENSE](LICENSE) for the full terms.
