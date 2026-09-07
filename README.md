# Igor Kostenko

Software engineer with a production Android background, currently focused on
C++20, Embedded Linux, UAV systems, and computer vision.

## Current stack

[![Current stack](https://skillicons.dev/icons?i=cpp,cmake,linux,raspberrypi,py,opencv,fastapi,githubactions&theme=light)](https://skillicons.dev)

## Production background

[![Production background](https://skillicons.dev/icons?i=kotlin,java,androidstudio,gradle&theme=light)](https://skillicons.dev)

## What I'm building

### [OnboardAutonomy](https://github.com/matemink/OnboardAutonomy)

**Robotics · Computer Vision · Embedded Linux · UAV Autonomy**

[![OnboardAutonomy CI](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml)

A C++20 runtime for vision-guided UAV autonomy:

- Simulates multicopter and fixed-wing scenarios in Gazebo.
- Tracks airborne objects with OpenCV and YOLOX/ONNX.
- Controls a Pixhawk through MAVLink with safety and recovery handling.
- Runs on a Raspberry Pi 5 and Pixhawk 6C bench, with Linux and ARM64 CI.

AprilTag landing remains a validation scenario. Fixed-wing pursuit is in development.

**Demos:**
[![Precision landing](https://img.shields.io/badge/YouTube-Precision_Landing-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=rsuRYYDfZZI)
[![Wind stress test](https://img.shields.io/badge/YouTube-Wind_Stress_Test-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=eqdRw3oofTI)

### [ExpressionMesh](https://github.com/matemink/ExpressionMesh)

**Computer Vision · Machine Learning · Python**

[![ExpressionMesh CI](https://github.com/matemink/ExpressionMesh/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/ExpressionMesh/actions/workflows/ci.yml)

An end-to-end facial-expression recognition pipeline from synthetic data to
live predictions:

- Generates a labeled facial-expression dataset with Stable Diffusion.
- Trains a scikit-learn classifier on MediaPipe Face Mesh landmarks.
- Runs real-time local inference from an OpenCV webcam feed.
- Includes reproducible training, automated tests, and CI checks.

## Earlier project

### [Goalia](https://github.com/matemink/goalia-backend)

**Kotlin Multiplatform · FastAPI · CatBoost**

A FastAPI backend built for a separate Kotlin Multiplatform football app:

- Fetches scheduled matches from football-data.org and caches the responses.
- Normalizes team and competition names for consistent model input.
- Adds home-win, draw, and away-win predictions with a bundled CatBoost model.
- Exposes enriched match data through a REST endpoint.

This repository contains only the backend.
