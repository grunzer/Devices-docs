---
title: Surface Software repair tools
description: Provides information on software repair tools
ms.service: surface
ms.localizationpriority: medium
author: bamifad00
ms.author: chauncel
ms.topic: overview
ms.date: 03/25/2025
ms.reviewer: 
manager: frankbu
appliesto:
- Windows 10
- Windows 11
---

## Surface Software Tools – Diagnostics, Calibration, Troubleshooting, and Support

This section covers the software tools needed to support a Surface
device through problem discovery and resolution.

- How To: [Update Surface device firmware and
  OS](https://support.microsoft.com/en-us/help/4023505)

- How To: [Surface Tools
  Video](https://www.youtube.com/watch?v=H5VlA6-fuY8&t)

- How To: [Surface Diagnostic Toolkit User
  Guide](https://www.microsoft.com/en-us/download/details.aspx?id=100440)

- Download: [Surface drivers and
  firmware](https://support.microsoft.com/en-us/help/4023482)

- Download: [Surface Diagnostic Toolkit
  (SDT)](https://www.microsoft.com/en-us/download/details.aspx?id=100440)

- Download: [Surface Data
  Eraser](https://msdn.microsoft.com/en-us/library/mt605308.aspx)

- Download: [Surface Imaging
  Tools](https://support.microsoft.com/en-us/surfacerecoveryimage)

## Calibration and Authentication

Specific components require additional software calibration or
authentication after completing the installation of the component before
the part will function to full capability. The specific steps will be
called out in the pertinent repair workflows.

**Impacted Parts**

- **Display Module (TDM) –**

  - Pre-installation – requires a pre-installation repair workflow,
    completed in SDT, to put the device into repair mode.

  - Post-installation – requires a post-installation workflow, completed
    in SDT, to calibrate the display to the correct settings.

- **Battery** **–**

  - Pre-installation - requires a pre-installation repair workflow,
    completed in SDT, to put the device into repair mode.

  - Post-installation – requires a post-installation authentication
    workflow, completed in SDT, to authenticate the new battery as a
    valid Microsoft part.

- **Motherboard (PCBA)** –

  - Post-installation - requires a post-installation workflow for
    Display and an authentication for Battery, completed in SDT, to
    calibrate the display to the correct settings with the new board and
    ensure the battery is detected as an authentic part.

## Hardware Troubleshooting Approach

Microsoft recommends the following approach for troubleshooting Surface
devices:

1.  Update the device to the latest Operating System and Driver/Firmware
    versions using Windows Update.

**Important:** Ensuring your device is fully up to date is important for
ensuring the issue you are experiencing is not fixed by a software
update prior to conducting a hardware repair.

2.  Utilize the Surface Diagnostic Toolkit (SDT) after confirming the
    device is fully updated to confirm the hardware fault is still
    present prior to repair.

3.  After the repair is completed, run the Surface Diagnostic Toolkit
    (SDT) to validate the original hardware fault is resolved.

    1.  If the issue is still being experienced, it is recommended to
        reimage the device using a Surface Recovery Image (BMR) to
        return the device to a known OS/FW state. Additional repairs
        should only be conducted if the issue persists after re-imaging
        the device.

## General Support

- For general Surface support, visit
  [www.support.microsoft.com](http://www.support.microsoft.com)

- To troubleshoot device feature/function problems or learn more about
  Surface Laptops visit <https://support.microsoft.com/surface> .

- If you would like to learn more about Windows, visit
  <https://support.microsoft.com/windows>

- To learn more about the accessibility features of the Surface Laptop,
  go to the online user guide at
  [aka.ms/Windows-Accessibility](https://support.microsoft.com/windows/discover-windows-accessibility-features-8b1068e6-d3b8-4ba8-b027-133dd8911df9)