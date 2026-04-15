# Contributing to Xplorer Open Platform

Thank you for your interest in contributing.

This project exists to help preserve and extend the usability of the XIRO Xplorer drone ecosystem through open source research, clean-room development, interoperability work, protocol documentation, and compatible tooling.

We welcome contributions from developers, testers, reverse engineers, technical writers, and XIRO hardware owners.

## Project Principles

This project is guided by a few core principles:

- **Preservation** of legacy hardware and software usability
- **Interoperability** through original research and clean-room implementation
- **Open documentation** so discoveries remain available to the community
- **Responsible use** of drones, software, and reverse engineering methods
- **Respect for intellectual property** and third-party rights

## Before You Contribute

Please read the repository `README.md` first to understand the project goals, current scope, and legal boundaries.

Before starting major work, it is a good idea to:

- Check existing issues and discussions
- Open an issue if you want to propose a major feature or structural change
- Make sure your planned contribution fits the project scope

## What Contributions Are Helpful

Helpful contributions include:

- Protocol documentation
- Packet capture analysis
- Android app development
- UI and UX improvements
- Bug fixes
- Build and setup instructions
- Testing results from XIRO hardware
- Telemetry and camera behavior notes
- Tooling for parsing, patching, or compatibility workflows
- Documentation cleanup and organization

## Preferred Contribution Types

We especially welcome:

### Clean-Room Development
Original code that reimplements compatible behavior based on observation, testing, and documentation.

### Protocol Research
Carefully documented findings about telemetry, camera control, RTSP behavior, Wi-Fi/range extender behavior, and related device communication.

### Testing and Validation
Reports from real hardware tests that include clear notes, expected behavior, observed behavior, and reproduction steps.

### Documentation
Well-organized writeups, diagrams, tables, and notes that help others understand the system and continue development.

## What Not to Contribute

Please do **not** submit any of the following unless you clearly have the legal right to do so:

- Proprietary XIRO source code
- Decompiled vendor code copied into this project
- Original APKs, IPAs, executables, or installer packages
- Copyrighted firmware images or firmware dumps
- Proprietary media assets, icons, sounds, or branding materials
- Third-party code or files that are not licensed for redistribution

This project is intended to support lawful interoperability, preservation, research, and clean-room reimplementation. Contributions must respect intellectual property rights.

## Contributor Licensing Notice

By submitting code, documentation, or other materials to this repository, you represent that:

- You have the legal right to contribute that material
- The material is your original work, or you are otherwise permitted to share it
- You agree for your contribution to be distributed under the **Apache License 2.0**

If you are not sure whether something is safe to contribute, do not submit it until it has been reviewed.

## How to Contribute

### Reporting Bugs

When reporting bugs, please include as much detail as possible:

- Device model
- Drone model
- App or tool version
- Android version or desktop OS version
- Connection method
- Network setup
- Steps to reproduce
- Expected behavior
- Actual behavior
- Relevant logs, screenshots, or captures

### Suggesting Features

Feature requests are welcome. Please describe:

- The problem you are trying to solve
- Why the feature would help
- Any known behavior from the original ecosystem
- Any technical notes that may help implementation

### Submitting Code Changes

For code contributions:

1. Fork the repository
2. Create a new branch for your change
3. Make your changes in focused commits
4. Add or update documentation where needed
5. Submit a pull request with a clear explanation of what changed and why

Try to keep pull requests focused on a single change or topic.

## Branch Naming Suggestions

Example branch naming patterns:

- `feature/telemetry-parser`
- `feature/camera-controls`
- `fix/rtsp-reconnect`
- `docs/protocol-notes`
- `tool/map-patch-workflow`

## Commit Message Suggestions

Clear commit messages make the project easier to maintain.

Examples:

- `Add initial camera command parser`
- `Fix RTSP reconnect handling`
- `Document extender Wi-Fi binding behavior`
- `Improve telemetry status display`
- `Add notes for map patch workflow`

## Pull Request Guidelines

Please include:

- A short summary of the change
- Why the change was made
- Any known limitations
- Test notes
- Screenshots or logs when relevant

Good pull requests are:

- Small enough to review clearly
- Documented
- Related to project goals
- Free of unrelated changes

## Research and Capture Submission Guidelines

If you are contributing packet captures, logs, screenshots, or protocol findings, please try to include:

- Device and hardware model
- Firmware version, if known
- App/tool version used during capture
- Exact action sequence performed
- Network topology, if relevant
- Whether the data has been sanitized

Please remove or redact sensitive information where possible before submission.

## Code Style

Consistency matters more than perfection.

General expectations:

- Keep code readable and well-named
- Prefer simple and maintainable solutions
- Add comments where behavior is not obvious
- Avoid large unrelated refactors in feature pull requests
- Update docs when behavior or workflows change

If a subproject later adopts stricter formatting or linting rules, those should be documented in that repository.

## Repository Structure

This project may be split across multiple repositories or subprojects, such as:

- Main hub / documentation
- Android app development
- XIRO Assistant compatibility tools
- Shared tooling and analysis resources

Please contribute to the repository that best matches the work being submitted.

## Safety and Responsible Use

Do not use this project to support reckless, unsafe, or unlawful drone activity.

Contributors should not use the repository to:

- Bypass lawful restrictions
- Evade safety mechanisms
- Misrepresent unofficial software as official vendor software
- Encourage unsafe flight behavior

Always follow local laws, airspace rules, and safe operating practices.

## Communication

Be respectful, constructive, and technical when possible.

Good collaboration includes:

- Clear problem descriptions
- Evidence-based discussion
- Respectful disagreement
- Helpful feedback on code and documentation

## Questions

If you are unsure whether a contribution fits the project, open an issue first and describe what you want to add.

Thanks for helping preserve and extend the XIRO Xplorer ecosystem.
