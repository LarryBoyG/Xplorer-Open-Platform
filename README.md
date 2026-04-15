# Xplorer-Open-Platform
Open source tools and Android app development for XIRO Xplorer compatibility.
# XIRO Xplorer Open Platform

An open source effort focused on helping preserve and extend the usability of the XIRO Xplorer drone ecosystem through community research, Android app development, protocol probing, and tooling support.

## Overview

The XIRO Xplorer line of drones remains interesting and useful hardware, but official software support has largely disappeared. This project exists to help keep those drones usable by documenting behavior, reverse engineering communication methods, and building replacement tools where possible.

The current focus includes:

- Open source Android app development for XIRO Xplorer drones
- Research into flight telemetry and camera communication protocols
- Continued compatibility efforts for legacy XIRO Assistant workflows
- Map patching support to help preserve usability of existing ground station software
- Community documentation for testing, probing, and protocol discovery

This repository is intended for developers, reverse engineers, drone hobbyists, and owners of legacy XIRO hardware who want to contribute to preserving these systems.

## Goals

- Create an open source Android application that can communicate with XIRO Xplorer hardware
- Document camera, video, telemetry, and control protocols through observation and testing
- Preserve useful functionality from discontinued software without redistributing proprietary code
- Maintain compatibility tools and patches that support continued operation of legacy XIRO Assistant software
- Build a public knowledge base so the community can continue development even without official vendor support

## Project Scope

This project is centered on interoperability, preservation, and clean-room implementation.

That means the goal is to:

- Observe and document how the hardware and official apps behave
- Probe network traffic and device responses
- Reimplement compatible functionality from scratch
- Patch or adapt openly available map resources and support files where appropriate

This project does **not** aim to redistribute copyrighted original application packages, firmware, media assets, or proprietary vendor code.

## Current Areas of Research

### Android App Replacement
Development of a modern Android application intended to restore or replace important mobile app functionality for XIRO Xplorer drones, such as:

- Live camera view
- Camera controls
- Telemetry display
- Range extender / Wi-Fi interaction
- Basic device status and connection handling

### Protocol Research
Ongoing investigation into:

- Flight telemetry data
- Camera command endpoints
- RTSP video behavior
- Device network layout
- Range extender communication
- App-to-device and controller-to-device interactions

### XIRO Assistant Compatibility
Preservation work related to the legacy XIRO Assistant desktop software, including:

- Open source map patching workflows
- Replacement map data strategies
- Continued usability support where legally and technically practical

## Legal and Ethical Position

This project is intended for lawful interoperability, archival, research, repair, and preservation purposes.

Contributors should follow these principles:

- Do not upload or redistribute proprietary XIRO code, paid software, firmware dumps, or copyrighted assets unless you clearly have the legal right to do so
- Do not present reverse engineered reimplementations as official XIRO software
- Do not use this repository to bypass safety systems, geofencing, or lawful restrictions
- Do not use this project for unsafe, reckless, or illegal drone operation

All code contributed here should be original work unless explicitly licensed for reuse.

## Contribution Guidelines

Contributions are welcome.

Helpful contribution types include:

- Protocol documentation
- Packet captures with clear notes
- Android development
- UI/UX improvements
- Testing on legacy XIRO hardware
- Map patching documentation
- Bug reports
- Build instructions
- Hardware behavior notes from real-world testing

When contributing, please try to include:

- Device model
- App or tool version
- Test conditions
- Network setup
- Logs, packet captures, or screenshots where relevant
- Clear reproduction steps

## Suggested Repository Structure

```text
/docs               Documentation and protocol notes
/android-app        Open source Android replacement app
/tools              Utilities, patchers, parsers, converters
/captures           Sanitized packet captures and analysis notes
/maps               Open source map patching resources and instructions
/firmware-notes     Observations only, no proprietary redistribution
