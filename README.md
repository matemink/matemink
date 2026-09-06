# Igor Kostenko

Software engineer with a production Android background, currently focused on
C++20, Embedded Linux, UAV systems, and computer vision.

## What I'm building

### [OnboardAutonomy](https://github.com/matemink/OnboardAutonomy)

**Robotics · Computer Vision · Embedded Linux · UAV Autonomy**

[![OnboardAutonomy CI](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml/badge.svg)](https://github.com/matemink/OnboardAutonomy/actions/workflows/ci.yml)

A C++20 companion-computer runtime for Raspberry Pi 5 and Pixhawk 6C,
combining MAVLink, onboard vision, and safety-supervised UAV autonomy:

- Runs a Gazebo pursuit lab with an S500 multicopter, a Skywalker X8
  fixed-wing pursuer, and a physics-backed Shahed-136 target in one scene.
- Lets the operator choose the pursuer after the scene starts; the selected
  vehicle receives MAVLink mission commands while the other remains grounded.
- Detects an airborne object through a forward camera and keeps it near the
  center of the frame with OpenCV and YOLOX/ONNX-based visual tracking.
- Exercises wind, target loss, link loss, contact response, RTL, and
  camera/serial recovery in Gazebo and automated integration tests.
- Runs the same application on a real Raspberry Pi 5 and Pixhawk 6C bench over
  USB or TELEM2 UART, with physical motion deliberately safety-gated.
- Builds and tests on desktop Linux and ARM64 with blocking static analysis.

AprilTag precision landing remains available as a separate deterministic
validation scenario. The Skywalker fixed-wing launch and sustained pursuit
path are still under active development.

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

## Current stack

[![Current stack](https://skillicons.dev/icons?i=cpp,cmake,linux,raspberrypi,py,opencv,githubactions&theme=light)](https://skillicons.dev)

## Production background

[![Production background](https://skillicons.dev/icons?i=kotlin,java,androidstudio,gradle&theme=light)](https://skillicons.dev)
