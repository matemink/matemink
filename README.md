# Ihor Kostenko

Software engineer with a production Android background, currently focused on
Kotlin Multiplatform, C++20, Embedded Linux, and computer vision.

## Current stack

[![Current stack](https://skillicons.dev/icons?i=cpp,cmake,linux,raspberrypi,py,opencv,fastapi,githubactions&theme=light)](https://skillicons.dev)

## Production background

[![Production background](https://skillicons.dev/icons?i=kotlin,java,androidstudio,gradle&theme=light)](https://skillicons.dev)

## What I'm building

### [OnboardAutonomy](https://github.com/matemink/OnboardAutonomy)

**C++20 · MAVLink · Camera Diagnostics · Embedded Linux**

[![OnboardAutonomy CI](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml)

A telemetry and camera observation prototype for ArduPilot, with a
Raspberry Pi 5 / Pixhawk 6C bench and Gazebo + SITL simulation:

- Reads MAVLink over UDP or Linux USB/UART with identity filtering and recovery.
- Captures independent camera streams and exposes console status, browser preview,
  and JSONL diagnostics.
- Checks recovery, package boundaries, static analysis, and native ARM64 builds in CI.

ArduPilot owns flight control. The current companion observes telemetry and
frames; standalone OpenCV DNN experiments are separate from the demo runtime.

<a href="https://matemink.github.io/OnboardAutonomy/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/matemink/OnboardAutonomy/main/docs/diagrams/overview-dark.svg">
    <img alt="Current OnboardAutonomy prototype: MAVLink and camera inputs, companion runtime, console, HTTP camera preview and JSONL diagnostics." src="https://raw.githubusercontent.com/matemink/OnboardAutonomy/main/docs/diagrams/overview-light.svg" width="840">
  </picture>
</a>

[Interactive architecture](https://matemink.github.io/OnboardAutonomy/) ·
[Current scope and evidence](https://github.com/matemink/OnboardAutonomy#status-and-evidence)

### [ExpressionMesh](https://github.com/matemink/ExpressionMesh)

**Computer Vision · Machine Learning · Python**

[![ExpressionMesh CI](https://github.com/matemink/ExpressionMesh/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/ExpressionMesh/actions/workflows/ci.yml)

An end-to-end facial-expression recognition pipeline from synthetic data to
live predictions:

- Generates a labeled facial-expression dataset with Stable Diffusion.
- Trains a scikit-learn classifier on MediaPipe Face Mesh landmarks.
- Runs real-time local inference from an OpenCV webcam feed.
- Includes reproducible training, automated tests, and CI checks.

### [Goalia](https://github.com/matemink/goalia-kmp)

[![Goalia CI](https://github.com/matemink/goalia-kmp/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/matemink/goalia-kmp/actions/workflows/ci.yml)

**Kotlin Multiplatform · Compose Multiplatform · FastAPI · CatBoost**

A football prediction app with a shared Android and iOS interface:

- Displays fixtures, team crests, and prediction probabilities through a shared Compose UI.
- Loads and refreshes match data with Ktor and Kotlin Serialization.
- Uses a FastAPI/CatBoost backend to fetch fixtures and generate match predictions.

**Repositories:** [KMP client](https://github.com/matemink/goalia-kmp) · [Backend](https://github.com/matemink/goalia-backend)
