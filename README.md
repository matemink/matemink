# Igor Kostenko

Software engineer with a production Android background, currently focused on
C++20, Embedded Linux, UAV systems, and computer vision.

## What I'm building

### [CompanionLab](https://github.com/matemink/CompanionLab)

[![CompanionLab CI](https://github.com/matemink/CompanionLab/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/CompanionLab/actions/workflows/ci.yml)

A UAV companion-computer testbench built around Raspberry Pi 5 and Pixhawk 6C:

- C++20 service with clean domain, application, adapter, and presentation boundaries.
- MAVLink telemetry and command handling with ArduPilot SITL and real Pixhawk hardware.
- Raspberry Pi Camera Module 3 pipeline with AprilTag detection and camera calibration.
- Gazebo-based flight scenarios, fault injection, native tests, and ARM64 CI builds.

The project is being developed as a reproducible precision-landing system. Real
flight is not required: autonomous behavior is validated in simulation, while
hardware work remains propeller-free and observation-only.

## Current stack

[![Current stack](https://skillicons.dev/icons?i=cpp,cmake,linux,raspberrypi,py,opencv,git,githubactions&theme=light)](https://skillicons.dev)

## Production background

[![Production background](https://skillicons.dev/icons?i=kotlin,java,androidstudio,gradle&theme=light)](https://skillicons.dev)
