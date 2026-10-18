# PAR6 Collaborative Robot Arm — Full Project

This branch assembles the PAR6 robot-arm project with its related RCB control box and STEPFOC stepper-controller resources.

> CAUTION: PAR6 is a beta, development-stage project. This repository is not a claim of collaborative-robot safety certification. Do not operate near people until the complete machine, control system, risk assessment, protective measures, and emergency-stop behavior have been independently validated for the intended application.

## Repository map

- 3D Print Files/ — PAR6 printable parts, CAD exports and print references.
- Assembly manual/ — PAR6 assembly, wiring and supporting datasheets.
- BOM/ — PAR6 bill of materials and reference images.
- PAR6 Description/ — PAR6 project documentation.
- Photos/ — PAR6 project images.
- Integrated Components/RCB-Robot-Control-Box/ — RCB motherboard firmware source, STEP models, BOM, assembly notes, photos and upstream documentation.
- Integrated Components/STEPFOC-stepper-controller/ — STEPFOC firmware source and build configuration, firmware binary, STEP models, photos and upstream documentation.
- LICENSES/ — license copies and component attribution.

## Firmware and hardware notes

- RCB motherboard firmware and STEPFOC firmware remain separate projects; they are not merged into one firmware image.
- STEPFOC includes source and a prebuilt binary. Verify hardware revision and firmware compatibility before flashing.
- Check each component README, build configuration, wiring instructions and license before use.
- Integrated Components is a curated copy of upstream component materials, not a claim that the integration has been tested as a complete robot system.

## Safety

Read SAFETY_WARNING_AND_DISCLAIMER.md and beta_guide.md before assembly or operation. Validate grounding, power distribution, emergency stop, communications-loss behavior, motion limits, guarding and mechanical stability. Test at low speed with the workspace secured. Never rely on software alone as a personnel-protection measure.

## Licensing and attribution

This is a multi-license repository. PAR6 hardware files are under CERN-OHL-S-2.0; RCB project files include MIT-licensed materials while its motherboard firmware carries a GPL-3.0 license; STEPFOC is GPL-3.0. See LICENSES/ and the original license files retained beside each component. The root license does not override a component's license.

## Upstream sources

- PAR6 Collaborative Robot Arm: https://github.com/Source-Robotics/PAR6-Collaborative-Robot-Arm
- RCB Robot Control Box: https://github.com/Source-Robotics/RCB-Robot-Control-Box
- STEPFOC Stepper Controller: https://github.com/Source-Robotics/STEPFOC-stepper-controller

Upstream projects may change. This branch is a snapshot taken when the assembly workflow ran; rerun Assemble PAR6 Full Project from the Actions tab to refresh it.
