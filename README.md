# Igor Kostenko

Software engineer with a production Android background, currently focused on
C++20, Embedded Linux, UAV systems, and computer vision.

## What I'm building

### [OnboardAutonomy](https://github.com/matemink/OnboardAutonomy)

**Robotics · Computer Vision · Embedded Linux · UAV Autonomy**

[![OnboardAutonomy CI](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml)

A C++20 companion-computer autonomy runtime for Raspberry Pi 5 and Pixhawk 6C,
combining MAVLink control, real-time computer vision, safety supervision, and
reproducible Gazebo validation:

- C++20 service with clean domain, application, adapter, and presentation boundaries.
- MAVLink telemetry and command handling with ArduPilot SITL and real Pixhawk hardware.
- Raspberry Pi Camera Module 3 pipeline with AprilTag detection and camera calibration.
- Gazebo-based flight scenarios, fault injection, native tests, and ARM64 CI builds.

Validated end-to-end with ArduCopter SITL and Gazebo, then deployed to a
propeller-free Raspberry Pi 5 and Pixhawk 6C hardware bench.

### [ExpressionMesh](https://github.com/matemink/ExpressionMesh)

**Computer Vision · Machine Learning · Python**

[![ExpressionMesh CI](https://github.com/matemink/ExpressionMesh/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/ExpressionMesh/actions/workflows/ci.yml)

An end-to-end facial-expression recognition pipeline from synthetic data to
live predictions:

- Generates a labeled facial-expression dataset with Stable Diffusion.
- Trains a scikit-learn classifier on MediaPipe Face Mesh landmarks.
- Runs real-time local inference from an OpenCV webcam feed.
- Provides reproducible training, automated tests, CI quality gates, and a model card.

## Current stack

[![Current stack](https://skillicons.dev/icons?i=cpp,cmake,linux,raspberrypi,py,opencv,githubactions&theme=light)](https://skillicons.dev)

## Production background

[![Production background](https://skillicons.dev/icons?i=kotlin,java,androidstudio,gradle&theme=light)](https://skillicons.dev)
