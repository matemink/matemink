# Igor Kostenko

Software engineer with a production Android background, currently focused on
C++20, Embedded Linux, UAV systems, and computer vision.

## What I'm building

### [OnboardAutonomy](https://github.com/matemink/OnboardAutonomy)

**Robotics · Computer Vision · Embedded Linux · UAV Autonomy**

[![OnboardAutonomy CI](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml)

A C++20 onboard autonomy runtime built around Raspberry Pi 5 and Pixhawk 6C:

- C++20 service with clean domain, application, adapter, and presentation boundaries.
- MAVLink telemetry and command handling with ArduPilot SITL and real Pixhawk hardware.
- Raspberry Pi Camera Module 3 pipeline with AprilTag detection and camera calibration.
- Gazebo-based flight scenarios, fault injection, native tests, and ARM64 CI builds.

The project is being developed as a reproducible precision-landing system. Real
flight is not required: autonomous behavior is validated in simulation, while
hardware work remains propeller-free and observation-only.

### [ExpressionMesh](https://github.com/matemink/ExpressionMesh)

**Computer Vision · Machine Learning · Python**

[![ExpressionMesh CI](https://github.com/matemink/ExpressionMesh/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/ExpressionMesh/actions/workflows/ci.yml)

A compact facial-expression classification pipeline from landmarks to real-time inference:

- MediaPipe Face Mesh produces 1,404 features for a scikit-learn Random Forest.
- Deterministic training, explicit model contracts, and installable Python CLI tools.
- Unit tests and Python 3.10/3.12 CI, with provenance and limitations in a model card.

## Current stack

[![Current stack](https://skillicons.dev/icons?i=cpp,cmake,linux,raspberrypi,py,opencv,githubactions&theme=light)](https://skillicons.dev)

## Production background

[![Production background](https://skillicons.dev/icons?i=kotlin,java,androidstudio,gradle&theme=light)](https://skillicons.dev)
