---
title: Surface Software Tools – Diagnostics, Calibration, Troubleshooting, and Support
description: Provides information on software repair tools
ms.service: surface
ms.localizationpriority: medium
author: bamifad00
ms.author: chauncel
ms.topic: overview
ms.date: 05/20/2025
ms.reviewer: 
manager: coravens
appliesto:
- Windows 10
- Windows 11
---

# Surface Software Tools – Diagnostics, Calibration, Troubleshooting, and Support

## Glossary of Terms

The following terms are used throughout this guide.

- **SDT** – Surface Diagnostic Toolkit

- **TDM –** Touch Display Module is the complete screen with all layers

- **BMR –** Bare Metal Recovery. Another name for the official service
  image released by Microsoft for your Surface product.

- **FRU –** Field Replaceable Units are sub-system components such as
  the SIM/rSSD door, Kickstand, and rSSD. FRUs are available only to
  ASPs. Some replaceable units will only be available as FRUs and
  therefore are only supported at an ASP.

- **Commercial Spares/CRU –** Customer Replaceable Units available to
  commercial customers for repair by a skilled technician.

- **Zip Archive –** A single file that contains one or more compressed
  files or directories.

## Software Tools & References

- How To: [<u>Update Surface device firmware and
  OS</u>](https://support.microsoft.com/help/4023505)

- Download: [<u>Surface drivers and
  firmware</u>](https://support.microsoft.com/help/4023482)

- Download: [<u>Surface Diagnostic Toolkit
  (SDT)</u>](https://www.microsoft.com/download/details.aspx?id=100440)

- Download: [<u>Surface Data
  Eraser</u>](https://msdn.microsoft.com/library/mt605308.aspx)

- Download: <u>[Surface
  Recovery](https://support.microsoft.com/surfacerecoveryimage)
  Images</u>

## Required Tools

- USB 3.0 Flash Drive – 16GB for SDT

- 2.5mm jack Headphones

- USB A Flash Drive

- USB C Flash Drive • USB-C to HDMI cable. • Monitor

- Surface Power Supply

## Service Diagnostics/Troubleshooting Overview

- For general Surface support, visit
  [support.microsoft.com](https://support.microsoft.com/)

- To troubleshoot device feature/function problems or learn more about
  Surface Pro visit
  [aka.ms/SurfaceProHelp](https://aka.ms/SurfaceProHelp)

- If you’d like to learn more about Windows, visit
  [aka.ms/WindowsHelp](https://aka.ms/WindowsHelp)

- To learn more about the accessibility features of the Surface Pro, go
  to the online user guide at
  [aka.ms/Windows-Accessibility](https://aka.ms/Windows-Accessibility)

## Prerequisite Steps – Software

 Prior to running SDT for Diagnostic or Repair purposes, please ensure
 the following tasks are completed to ensure the best possible chance
 of a successful run and accurate diagnostics.

- Ensure the device is updated to the latest OS/FW versions available
  using [<u>Windows Update.</u>](https://support.microsoft.com/windows/update-windows-3c5ae7fc-9fb6-9af1-1984-b5e0412c556a)

- The device **must** be capable of booting into a Windows user account.
  If it is unable to do so, please reimage the device using the Surface
  Recovery Image for your model.

## Surface Diagnostic Toolkit – Navigation

 This section will take you through the Surface Diagnostic Toolkit in
 detail.

### Launching the Surface Diagnostic Toolkit

- Insert the USB 3.0 Flash Drive loaded with the [<u>Surface Diagnostic
  Toolkit</u>](https://www.microsoft.com/download/details.aspx?id=46703)
  files

- Locate **Microsoft.Surface.Diagnostics.App.Wpf.exe** and double-click
  to launch the Surface Diagnostic Toolkit application on your device.

  :::image type="content" source="./images/SWTools/media/image10.jpeg" alt-text="Screenshot of the software loading and arriving at the Welcome screen.":::

  The software will launch and after a few moments of loading will arrive at the Welcome screen.

### Navigating the Welcome screen

- In the upper left corner, selecting the hamburger (menu will bring out
  the Menu sidebar detailing additional sections of the Surface
  Diagnostic Toolkit outside of the Diagnostic and Repair workflows.



- **About** – provides the user with the software information for SDT
  including build version, current language, modality, and location of
  the log file for troubleshooting purposes.

- **System Information** – provides the user with key device information
  including serial number, device model, and device specifications.

- **Battery Information** – provides the user with a read out of the
  current statistics for the battery installed in a device if the device
  has a battery installed. This includes the battery wear level, number
  of charge/discharge cycles, and current charge.

- **Save Results** – allows the user to save an output of all completed
  diagnostic information to a file on the device for review.

- **Surface warranty** – displays the devices currently warranty
  information from Microsoft based on the devices serial number.
  **Requires a connection to the internet.**

- **Settings** – Allows the user to change the display language for the
  SDT software to another supported language.



- On the right side of the screen, there is a drop-down menu that allows
  you to choose between the diagnostic workflow and the repair workflow.



- The **Diagnostic** workflow allows you to perform a series of
  diagnostic tests to determine the functionality of the devices core
  functions.

- The **Repair** workflow allows you to perform targeted calibration and
  authentication workflows as detailed in the written Service Guide to
  enable the installation of a replacement Microsoft part. **Note:**
  Both selections will take you to the same workflow selection screen.
  This is done to allow for accuracy in tracking the frequency of how
  users utilize our software.



- Select an option from the drop-down menu and select **Continue** to
  continue to the workflow selection screen.

### The Results Screen

The results screen is the end screen that appears once you have
completed the **<u>Diagnostic</u>** or **<u>Repair</u>** workflows.
This screen displays the outputs of any completed diagnostic test or
repair script.

> [!TIP]
> You can use the **Save Results** icon from the <u>Side
> Bar</u> on the left to save an output of all results in an easyto-read
> format.

:::image type="content" source="./images/SWTools/media/image13.jpeg" alt-text="Screenshot of the Surface Diagnostic Toolkit showing the Diagnostic workflow home screen.":::

- The color above the **Details** box denotes the result of the test.
  You can select the **Details** button next to each test to learn more
  details about the test outcomes and potential next steps.

  - **Green:** Tests passed. o **Yellow:** Additional details available
    – test failures, additional information, next steps.

## Surface Diagnostic Toolkit – Diagnostic Workflow

This section will detail the Diagnostic workflow in the SDT tool.
Please see <u>Navigating the Welcome Screen</u> for details on how to
access this workflow.

:::image type="content" source="./images/SWTools/media/image14.jpeg" alt-text="Illustration showing the Diagnostic workflow in the Surface Diagnostic Toolkit.":::

- Select **Diagnostic** in the drop-down menu on the welcome screen and
  select **Continue** to be brought to the Diagnostic workflow home
  screen.

  - On this screen there are two options:

    - **Run all tests** – automatically begins to run thru all
      diagnostics tests in the SDT testing suite. Useful for fully
      evaluating a device to ensure complete functionality. **Note:**
      most tests in SDT require user interaction or input to complete.

    - **Repair setup and validation** – brings the user to a screen
      where they can select from the suite of tests to run a customized
      list. Useful for targeted testing of specific components.

## Diagnostic Workflow – Test Overview

This section will provide details for each of the tests in the SDT
diagnostic suite. Please note that not every test will be present for
every model of Microsoft Surface as the test suite is tailored to the
device’s capabilities.

> [!NOTE]
> It is critical to follow the instructions for each test as
> detailed on the screen to ensure the most accurate result.

- **Battery & Charging** (User Interaction Required) – o **Action:**
  When directed, unplug the devices power supply, and plug it back in.

  - **What to look for:** the test will automatically pass or fail
    dependent on whether the device switched charging states when the
    power supply was disconnected and reconnected.

- **Modern Standby** (Automated) – o **Action:** No user action needed.
  The test will automatically pass or fail based on a series of checks
  against Modern Standby support and functionality.

- **Touch Coverage** (User Interaction Required) – o **Action:** trace
  the spiral on the screen with your finger.

  - **What to look for:** The critical item in this test is that your
    finger input is recorded on the screen with no gaps or stuttering.

- **Multi-touch detection** (User Interaction Required) – o **Action:**
  touch the screen with multiple fingers.

  - **What to look for:** the counter on the screen should begin at zero
    and count accurately with each finger you place on the screen up to
    10.

- **Phantom Touch Detection** – o **Action:** Do not touch the screen
  for 5 seconds.

  - **What to look for**: The screen will count down and no touch input
    should be detected. Any touch input detected during the 5 seconds
    will result in a failed test.

- **Brightness** (User Interaction Required) – o **Action:** the screen
  will adjust from 0% to 100% brightness.

  - **What to look for:** Ensure the screen changes brightness evenly
    and successfully.

- **Stuck or Dead Pixels** (User Interaction Required) – o **Action:**
  the screen will display a series of different colored screens and
  images. Click the trackpad to move between screens.

  - **What to look for:** Any pixels on the screen that are the wrong
    color or stuck (white/black).

- **Headphones** (User Interaction Required) – o **Action:** Plug in a
  set of headphones and listen for tones played by the software.

  - **What to look for:** Lack of sound or distorted sound when audio is
    played back.

- **Speaker** (User Interaction Required) – o **Action:** Audio will be
  played back through the left and right speaker.

  - **What to look for:** Lack of sound or distorted sound when audio is
    played back.

- **Microphone** (User Interaction Required) – o **Action:** Count down
  aloud from 5 to 1 while the device records. After recording, the audio
  will be played back.

  - **What to look for:** Lack of recorded audio or distorted audio when
    the recording is played back.

- **Keyboard** (User Interaction Required) – o **Action:** Press each
  key on the keyboard until all keys have been pressed.

  > [!NOTE]
  > It is critical that the correct keyboard language is
  > selected for your device’s keyboard to ensure an accurate test.

- **What to look for:** keys that do not register on-screen when
  pressed.

  > [!NOTE]
  > The Fn key must be toggled on to ensure all key presses are
  > recorded.

- **Touchpad Double-Click** (User Interaction Required) – o **Action:**
  Using the touchpad, double- click the icon on the screen.

  - **What to look for:** In-ability to double-click successfully on the
    icon on the screen.

- **Touchpad Touch Coverage** (User Interaction Required) – o
  **Action:** Using your finger, trace the surface of the Touchpad until
  the entire image on the screen is filled in.

  - **What to look for:** areas in the image that do not fill in when
    you run your finger over that section of the Touchpad.

- **Touchpad Drag and Drop** (User Interaction Required) – o **Action:**
  Using the touchpad, drag the document icon on the screen to the
  recycle bin icon on the screen.

  - **What to look for:** Inability to successfully drag the document
    icon to the recycle bin.

- **USB** (User Interaction Required) – o **Action:** Plug a USB flash
  drive into each USB port on the device and ensure it is detected on
  the screen. o **What to look for:** your USB device is not being
  detected when plugged into a particular USB port on the device.

- **Video Out** (User Interaction Required) – o **Action:** Connect an
  external monitor to a USB-C port on your Surface. o **What to look
  for:** the external monitor powers on and displays an image.

- **Ambient Light Sensor** (User Interaction Required) – o **Action:**
  Move your Surface device around and ensure the Ambient Light Sensor
  bar changes with the changing brightness level in the room.

  - **What to look for:** the ambient light sensor bar should move with
    the changing brightness level in the room.

- **Bluetooth** (User Interaction Required) –

  - **Action:** The test will display all Bluetooth devices detected by
    the onboard Bluetooth radio.

  - **What to look for:** the test is successful if the device displays
    any Bluetooth devices on-screen.

- **Camera** (User Interaction Required) – o **Action:** The screen will
  display an output from each camera on the device.

  - **What to look for:** Any failure to output from the device’s
    cameras or any distortion of the image.

- **Driver Health** (Automated) – o **Action:** no user action needed.
  The test will automatically pass or fail dependent on the state of the
  device’s drivers.

- **Memory** (Automated) – o **Action:** No user action needed. The test
  will automatically pass or fail dependent on the outcome of several
  memory error checks.

- **Storage** (Automated) – o **Action:** No user action needed. The
  test will automatically pass or fail dependent on several storage
  statistics with the on-board storage.

## Surface Diagnostic Toolkit – Repair Workflow

:::image type="content" source="./images/SWTools/media/image14.jpeg" alt-text="Illustration showing the Diagnostic workflow in the Surface Diagnostic Toolkit.":::

This section will detail the Diagnostic workflow in the SDT tool. Please see <u>Navigating the
Welcome Screen</u> for details on how to access this workflow.

- Select **Repair** in the drop-down menu on the welcome screen and
  select **Continue** to be brought to the Repair workflow home screen.

  - On this screen there are two options:

    - **Run all tests** – automatically begins to run thru all
      diagnostic tests in the SDT testing suite. **Does not** contain
      the repair scripts.

    - **Repair setup and validation** – brings the user to a screen
      where they can select from the suite of tests to run a customized
      list. This is where the **Repair** setup and validation scripts
      are located.

## Repair Workflow – Script Overview

This section will provide details for each of the repair scripts in
the SDT diagnostic suite. Please note that each script is only
required for specific repairs and is called out in the Service Guide
for your device.

> [!NOTE]
> It is critical to follow the instructions for each script as
> detailed on the screen to ensure a successful result.

- **Battery Repair (Setup)**- o **For:** Battery replacement o **When:**
  Prior to replacement of a battery. o **Actions:** Follow the on-screen
  instructions and allow the device to shut down when prompted.

  - **What does it do:** It prepares the device to receive a replacement
    battery.

- **Battery Repair (Validation)** - o **For:** Battery Replacement,
  PCBA/Motherboard replacement o

  **When:** First power-on after replacement of a battery OR
  PCBA/Motherboard.

- **Actions:** Follow the on-screen instructions to authenticate and
  evaluate the installed battery. o

  **What does it do:** this script checks with Microsoft to ensure the
  battery installed is an authentic Microsoft replacement Surface
  battery. It then evaluates the battery device functions to ensure all
  are within defined parameters.

  > [!NOTE]
  > Requires a connection to the internet to successfully
  > authenticate the replacement battery with Microsoft. Additionally, the
  > Surface Management Extension also needs to be installed and up to
  > date. The latest version of the Surface Management Extension can be
  > downloaded
  > [<u>here</u>.](https://www.microsoft.com/store/apps/9NCT159F4QVG)

- **Touch Display Repair (Setup)** – o **For:** Display Replacement o
  **When:** Prior to Display replacement. o **Actions:** Follow the
  on-screen instructions and allow the device to shut down when
  prompted. o **What does it do:** it gathers calibration data from the
  original display and prepares the device to receive a new display.

  > [!NOTE]
  > Not needed if you are re-using the same display. Only for
  > replacement of a defective or damaged display with a replacement
  > display.

- **Touch Display Repair (Calibration)** – o **For:** Display
  Replacement, PCBA/Motherboard replacement o **When:** first power-on
  after replacement of the display OR

  PCBA/Motherboard. o **Actions:** Follow the on-screen instructions to
  perform a calibration of the new display.

- **What does it do:** it applies a calibration dataset to the new
  display to ensure optimal operation.



- **Touch Display Repair (Validation)** – o **For:** Display Replacement
  o **When:** After calibration of the new display.

  - **Actions:** Follow the on-screen prompts to complete the targeted
    diagnostic tests to evaluate core display functionality. o **What
    does it do:** it performs a series of targeted diagnostic tests to
    ensure the new display is functioning to specification.

## Reporting Issues and Log Locations

In instances where you encounter an issue with the Surface Diagnostic
Toolkit, Microsoft may request log files to determine the root cause
of the problem.

> [!IMPORTANT]
> If you encounter a bug while running SDT, please
> complete the test completely until you reach the test summary page or
> the main page of the application. This will provide the most complete
> log files for review.

### Reporting a software error with SDT

If an error is encountered while running the Surface Diagnostic
Toolkit (SDT) on a device in for repair, the following information
must be gathered and included with the escalation to ensure proper
support.

<table>

<thead>
<tr>
<th><strong>ASP Company:</strong></th>
<th>
<p>Insert Company Name</p>
</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Site:</strong></td>
<td>
<p>Insert Partner Work /Store location</p>
</td>
</tr>
<tr>
<td><strong>Surface Device Models:</strong></td>
<td>
<p>Insert the Model of Surface device impacted</p>
</td>
</tr>
<tr>
<td><strong>Number of Impacted Devices:</strong></td>
<td>
<p>Insert the number of impacted devices experiencing the issue</p>
</td>
</tr>
<tr>
<td><p><strong>Surface Diagnostic Toolkit (SDT) Details:</strong></p>
<p>See the instructions below this table</p></td>
<td>
<p>Insert Surface Diagnostic Toolkit details found in the About
section here. Instructions are located below.</p>
</td>
</tr>
<tr>
<td><strong>Issue Description:</strong></td>
<td>
<p>Provide a quick summary of your issue and any steps to recreate
it.</p>
</td>
</tr>
<tr>
<td><p><strong>Logs Attached:</strong></p>
<p>See the instructions below this table</p></td>
<td>
<p><strong>Attach logs to this email in a ZIP format.</strong></p>
<p><strong>Additional logs are required for issues related to Display
Calibration. All Logs pertinent to your experienced issue must be
included for triage purposes.</strong></p>
</td>
</tr>
</tbody>
</table>

### Retrieving Surface Diagnostic Toolkit Details

- Launch the Surface Diagnostic Toolkit (SDT) on a device.

- At the SDT launch screen, locate the information symbol (circle
  with i) in the upper left corner of the screen, and select it to
  launch the About panel.

:::image type="content" source="./images/SWTools/media/image16.jpeg" alt-text="Illustration showing the Surface Diagnostic Toolkit details screen.":::

Select **Copy** in the lower left section of the screen and paste the
contents into the **Surface Diagnostic Toolkit** **(SDT) Details** section above.

:::image type="content" source="./images/SWTools/media/image17.jpeg" alt-text="Illustration showing the Surface Diagnostic Toolkit details section.":::

### Locating Touch/TDM Logs:

If you are experiencing an error in SDT related to the calibration of
a display pre or post-repair, also provide the calibration logs:

- Navigate to the folder directory where the Surface Diagnostic Toolkit
  executable (Microsoft.Surface.Diagnostics.App.Wpf.exe) is located.

- Locate the folder titled **"LogFiles"** and navigate to it.

- Copy the contents of the LogFiles folder and create a ZIP archive.
  Instructions for creating a ZIP archive can be found
  [<u>here</u>.](https://support.microsoft.com/windows/zip-and-unzip-files-8d28fa72-f2f9-712f-67df-f80cf89fd4e5)

- Attach the ZIP archive to this email.

  > [!NOTE]
  > The LogFiles location will only be present if a Display
  > Calibration has been attempted. If the folder does not exist or no
  > logs are present, attempt the Display Calibration again and ensure
  > Surface Diagnostic Toolkit reaches the **Results** screen before
  > exiting the program.

### Locating SDT Logs:

- General SDT logs are located at the folder location identified in the
  **About** section in SDT in the Log Location entry of the About
  section. Instructions to locate the About section can be found in the
  **Grabbing Surface Diagnostic Toolkit Details** section of this email.

- Navigate to the folder location identified and make a copy of all
  folders located in the SurfaceDiagnosticToolkit_data folder.

- Once copied, create a ZIP archive of the folders and all content.
  Instructions for creating a ZIP archive can be found
  [<u>here</u>.](https://support.microsoft.com/windows/zip-and-unzip-files-8d28fa72-f2f9-712f-67df-f80cf89fd4e5)
