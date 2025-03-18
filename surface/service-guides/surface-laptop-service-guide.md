---
title: Surface Laptop Service Guide demo
description:  Surface Laptop Service Guide draft page.
ms.service: surface
ms.localizationpriority: medium
author: coveminer
ms.author: chauncel
ms.topic: overview
ms.date: 03/17/2025
ms.reviewer: angpatel
manager: frankbu
appliesto:
- Windows 11
---

# Microsoft Surface Laptop 7th Edition Service Guide

## Disclaimer section 

All information, content, materials, and products made available in or
with this Guide are provided by Microsoft on "as-is" and
"as available" basis, unless otherwise specified by Microsoft in
writing. Microsoft makes no representations or warranties of any kind,
express or implied, as to the information, content, materials, and
products included or otherwise made available to you or accompanying
this Guide unless specified in writing. You expressly agree that your
use of the information, content, materials, and product in or
accompanying this Guide is at your sole risk.

To the fullest extent permissible by law, Microsoft disclaims all
warranties, express or implied, including but not limited to implied
warranties of merchantability and fitness for a particular purpose. To
the fullest extent permissible by law, Microsoft shall not be liable for
damages of any kind arising from the use of information, content,
materials, or product made available in or with this
Guide, including but not limited to direct, indirect, incidental,
consequential, and/or punitive damages unless otherwise specified in
writing.

*Notice*

Microsoft and its suppliers may have patents, patent applications,
trademarks, copyrights, trade secrets and/or other intellectual property
rights covering subject matter in this document. Microsoft's furnishing
of this document to recipient doesn't grant or imply any license to any
patents, trademarks, copyrights, trade secrets or other intellectual
property rights, and recipient's permitted use of any such intellectual
property rights, if any, is solely governed by the Agreements.

This document and the information it contains are subject to change
without notice. You can find the latest information on Surface device
servicing and repair at <https://aka.ms/surfaceservicing> . Always
consult the most up-to-date information available before performing
device service or repair.

©2024 Microsoft Corporation. All rights reserved.

Document Part Number: M1318466

  ------------------------------------------------------------------------------
   **Rev**  **Date**     **Changes Made**
  --------- ------------ -------------------------------------------------------
      A     06/18/2024   Initial Release

  ------------------------------------------------------------------------------

## Table of Contents {#table-of-contents .TOC-Heading}

[Introduction [6](#introduction)](#introduction)

[Device Identity Information
[6](#device-identity-information)](#device-identity-information)

[General Information, Precautions, and Warnings
[7](#general-information-precautions-and-warnings)](#general-information-precautions-and-warnings)

[Tools [7](#tools)](#tools)

[General Safety Precautions
[9](#general-safety-precautions)](#general-safety-precautions)

[Electro-Static Discharge (ESD) Prevention
[10](#electro-static-discharge-esd-prevention)](#electro-static-discharge-esd-prevention)

[Repair-Specific Precautions and Warnings
[10](#repair-specific-precautions-and-warnings)](#repair-specific-precautions-and-warnings)

[Battery Safety [11](#battery-safety)](#battery-safety)

[Battery Warning Level
[12](#battery-warning-level)](#battery-warning-level)

[Lithium-Ion Battery Inspection
[12](#lithium-ion-battery-inspection)](#lithium-ion-battery-inspection)

[Handling Used, Damaged, or Defective Lithium-Ion Batteries
[13](#handling-used-damaged-or-defective-lithium-ion-batteries)](#handling-used-damaged-or-defective-lithium-ion-batteries)

[Actions to take in case of a Thermal Event
[13](#actions-to-take-in-case-of-a-thermal-event)](#actions-to-take-in-case-of-a-thermal-event)

[Report Battery Thermal Events to Microsoft
[13](#report-battery-thermal-events-to-microsoft)](#report-battery-thermal-events-to-microsoft)

[Illustrated Service Parts List
[15](#illustrated-service-parts-list)](#illustrated-service-parts-list)

[Software Tools -- Diagnostic, Calibration, and Troubleshooting
[21](#software-tools-diagnostic-calibration-and-troubleshooting)](#software-tools-diagnostic-calibration-and-troubleshooting)

[Genuine Microsoft Replacement Parts
[21](#genuine-microsoft-replacement-parts)](#genuine-microsoft-replacement-parts)

[General Support [21](#general-support)](#general-support)

[Software Tools [21](#software-tools)](#software-tools)

[Calibration and Authentication
[21](#calibration-and-authentication)](#calibration-and-authentication)

[Hardware Troubleshooting Approach
[22](#hardware-troubleshooting-approach)](#hardware-troubleshooting-approach)

[Component Removal and Replacement Procedures
[22](#component-removal-and-replacement-procedures)](#component-removal-and-replacement-procedures)

[Prerequisite Steps [22](#prerequisite-steps)](#prerequisite-steps)

[Feet Replacement [23](#feet-replacement)](#feet-replacement)

[Enclosure Replacement
[24](#enclosure-replacement)](#enclosure-replacement)

[Removable Solid-State Drive Replacement
[26](#removable-solid-state-drive-replacement)](#removable-solid-state-drive-replacement)

[Battery Replacement [29](#battery-replacement)](#battery-replacement)

[Audio Jack Replacement
[33](#audio-jack-replacement)](#audio-jack-replacement)

[Right Speaker Replacement
[35](#right-speaker-replacement)](#right-speaker-replacement)

[Left Speaker Replacement
[39](#left-speaker-replacement)](#left-speaker-replacement)

[Micro SD Reader Replacement
[42](#micro-sd-reader-replacement)](#micro-sd-reader-replacement)

[Display Assembly Replacement
[44](#display-assembly-replacement)](#display-assembly-replacement)

[Surface Connect Replacement
[51](#surface-connect-replacement)](#surface-connect-replacement)

[Motherboard Replacement Process
[54](#motherboard-replacement-process)](#motherboard-replacement-process)

[Keyboard Replacement Process
[64](#keyboard-replacement-process)](#keyboard-replacement-process)

[Environmental Compliance Requirements
[68](#environmental-compliance-requirements)](#environmental-compliance-requirements)

## Introduction

This Service Guide provides instructions for repairing Microsoft Surface
devices using genuine Microsoft parts. It's intended for technically
inclined individuals with the knowledge, experience, and specialized
tools required to repair Microsoft devices.

**IMPORTANT:** Read this Guide in its entirety before starting any
repairs. If at any point you're unsure or uncomfortable about
performing the repairs, as detailed in this Guide, **DO NOT** proceed.
Contact Microsoft for more support options.

![](/service-guides/images/image4.png){width="0.9069444444444444in"
height="0.19305555555555556in"}**:** 

> [!WARNING]
> Failure to follow the instructions
> in this Guide; use of non-Microsoft (nongenuine), incompatible, or modified replacement parts; and/or failure to use proper tools could result in serious personal injury, death, and/or damage to the product or other property.

## Device Identity Information

- Surface Laptop 7^th^ Edition

Support Link --
[Link](https://support.microsoft.com/en-us/hub/4295675/surface-laptop-help)

The model and serial number for Surface Laptops is on the bottom center
closest to the display hinge point.

![A white rectangular object with a blue label Description automatically
generated](/service-guides/images/image5.png){width="5.6in"
height="3.695640857392826in"}



## Illustrated Service Parts List

![A computer parts diagram showing the parts of a computer Description
automatically generated](/service-guides/images/image16.png){width="5.83in"
height="6.537898075240595in"}

**IMPORTANT:** Repair workflows may require multiple parts to be ordered
to complete the repair successfully. Please check the primary and
additional components section in each repair workflow to ensure you have
all required parts before beginning your repair.

  ----------------------------------------------------------------------------
   **Item**  **Component**                                   **SKU Part No.**
  ---------- ----------------------------------------------- -----------------
    **1**    **Feet**                                        

             Platinum                                        E0A-00001

             Graphite                                        E0A-00002

             Dune                                            E0A-00003

             Sapphire                                        E0A-00004

    **2**    **Enclosure**                                   

             Platinum -- 13"                                 C0X-00001

             Platinum -- 15"                                 C0Y-00001

             Graphite -- 13"                                 C0X-00002

             Graphite -- 15"                                 C0Y-00002

             Dune -- 13"                                     C0X-00003

             Sapphire -- 13"                                 C0X-00004

    **3**    **Removable Solid-State Drive**                 

             256GB                                           E0S-00001

             512GB                                           E0T-00001

             1TB                                             E0U-00001

    **4**    **Battery**                                     

             Battery -- 13"                                  C0A-00001

             Battery -- 15"                                  C0B-00001

    **5**    **Audio Jack**                                  

             Audio Jack                                      E0G-00001

    **6**    **Right Speaker**                               

             Right Speaker -- 13"                            E0D-00002

             Right Speaker -- 15"                            EOL-00002

    **7**    **Left Speaker**                                

             Left Speaker -- 13"                             E0D-00001

             Left Speaker -- 15"                             E0L-00001

    **8**    **Display Assembly (Includes Camera)**          

             Platinum -- 13"                                 D0K-00001

             Platinum -- 15"                                 D0L-00001

             Graphite -- 13"                                 D0K-00002

             Graphite -- 15"                                 D0L-00002

             Dune -- 13"                                     D0K-00003

             Sapphire -- 13"                                 D0K-00004

    **9**    **Surface Connect Port**                        

             Surface Connect Port - 13"                      E0B-00001

             Surface Connect Port - 15"                      E0I-00001

    **10**   **Motherboard (includes main processor and main 
             memory, and thermal module)**                   

             Plus 16GB -- 13" Commercial                     C0P-00001

             Plus 16GB -- 13"                                C0P-00002

             Elite 16GB -- 13" Commercial                    C0Q-00001

             Elite 16GB -- 13"                               C0Q-00002

             Elite 16GB -- 15" Commercial                    C0T-00001

             Elite 16GB -- 15"                               C0T-00002

             Elite 32GB -- 13" Commercial                    C0R-00001

             Elite 32GB -- 13"                               C0R-00002

             Elite 32GB -- 15" Commercial                    C0U-00001

             Elite 32GB -- 15"                               C0U-00002

             Elite 64GB -- 13"                               EP2-07971

             Elite 64GB -- 15"                               EP2-07972

    **11**   **Keyboard Assembly (includes Trackpad)**       

             Platinum -- Arabic -- 13"                       D0P-00008

             Platinum -- Arabic -- 15"                       D0Q-00008

             Graphite -- Arabic -- 13"                       D0P-00026

             Graphite -- Arabic -- 15"                       D0Q-00026

             Dune -- Arabic -- 13"                           EP2-00813

             Sapphire -- Arabic -- 13"                       EP2-00814

             Platinum -- Belgium-- 13"                       D0P-00014

             Platinum -- Belgium -- 15"                      D0Q-00014

             Graphite -- Belgium -- 13"                      D0P-00032

             Graphite -- Belgium -- 15"                      D0Q-00032

             Dune --Belgium -- 13"                           D0P-00047

             Sapphire -- Belgium-- 13"                       D0P-00058

             Platinum -- Chinese Traditional (Taiwan) -- 13" D0P-00007

             Platinum -- Chinese Traditional (Taiwan) -- 15" D0Q-00007

             Graphite -- Chinese Traditional (Taiwan) -- 13" D0P-00025

             Graphite -- Chinese Traditional (Taiwan) -- 15" D0Q-00025

             Platinum -- Canada EN/FR -- 13"                 D0P-00002

             Platinum -- Canada EN/FR -- 15"                 D0Q-00002

             Graphite -- Canada EN/FR -- 13"                 D0P-00020

             Graphite -- Canada EN/FR -- 15"                 D0Q-00020

             Platinum -- English International -- 13"        D0P-00010

             Platinum -- English International -- 15"        D0Q-00010

             Graphite -- English International -- 13"        D0P-00028

             Graphite -- English International -- 15"        D0Q-00028

             Dune -- English International -- 13"            D0P-00043

             Sapphire -- English International -- 15"        D0P-00054

             Platinum -- English UK -- 13"                   D0P-00009

             Platinum -- English UK -- 15"                   D0Q-00009

             Graphite -- English UK -- 13"                   D0P-00053

             Graphite -- English UK -- 15"                   D0Q-00028

             Dune -- English UK -- 13"                       D0P-00042

             Sapphire -- English UK -- 13"                   D0P-00053

             Platinum- English -- 13"                        D0P-00001

             Platinum -- English -- 15"                      D0Q-00001

             Graphite -- English -- 13"                      D0P-00019

             Graphite -- English -- 15"                      D0Q-00019

             Dune -- English -- 13"                          D0P-00037

             Sapphire -- English -- 13"                      D0P-00048

             Platinum -- French -- 13"                       D0P-00012

             Platinum -- French -- 15"                       D0Q-00012

             Graphite -- French -- 13"                       D0P-00030

             Graphite -- French -- 15"                       D0Q-00030

             Dune -- French -- 13"                           D0P-00045

             Sapphire -- French -- 13"                       D0P-00056

             Platinum -- German -- 13"                       D0P-00011

             Platinum -- German -- 15"                       D0Q-00011

             Graphite -- German -- 13"                       D0P-00029

             Graphite -- German -- 15"                       D0Q-00029

             Dune -- German -- 13"                           D0P-00044

             Sapphire -- German -- 13"                       D0P-00055

             Platinum -- Italian -- 13"                      D0P-00015

             Platinum -- Italian -- 15"                      D0Q-00015

             Graphite -- Italian -- 13"                      D0P-00033

             Graphite -- Italian -- 15"                      D0Q-00033

             Platinum -- Japanese -- 13"                     D0P-00004

             Platinum -- Japanese -- 15"                     D0Q-00004

             Graphite -- Japanese -- 13"                     D0P-00022

             Graphite -- Japanese -- 15"                     D0Q-00022

             Dune -- Japanese -- 13"                         D0P-00039

             Sapphire -- Japanese -- 13"                     D0P-00050

             Platinum -- Korean -- 13"                       D0P-00005

             Platinum -- Korean -- 15"                       D0Q-00005

             Graphite -- Korean -- 13"                       D0P-00023

             Graphite -- Korean -- 15"                       D0Q-00023

             Dune -- Korean -- 13"                           D0P-00040

             Sapphire -- Korean -- 13"                       D0P-00051

             Platinum -- Nordic -- 13"                       D0P-00016

             Platinum -- Nordic -- 15"                       D0Q-00018

             Graphite -- Nordic -- 13"                       D0P-00036

             Graphite -- Nordic -- 15"                       D0Q-00036

             Platinum -- Portuguese -- 13"                   D0P-00016

             Platinum -- Portuguese -- 15"                   D0Q-00016

             Graphite -- Portuguese -- 13"                   D0P-00034

             Graphite -- Portuguese -- 15"                   D0Q-00016

             Platinum -- Spanish (Mexico) -- 13"             D0P-00003

             Platinum -- Spanish (Mexico) -- 15"             D0Q-00003

             Graphite -- Spanish (Mexico) -- 13"             D0P-00021

             Graphite -- Spanish (Mexico) -15"               D0Q-00021

             Platinum -- Spanish (Spain) -- 13"              D0P-00017

             Platinum -- Spanish (Spain) -- 15"              D0Q-00017

             Graphite -- Spanish (Spain) -- 13"              D0P-00035

             Graphite -- Spanish (Spain) -- 15"              D0Q-00035

             Platinum -- Swiss/Luxembourg -- 13"             D0P-00013

             Platinum -- Swiss/Luxembourg -- 15"             D0Q-00013

             Graphite -- Swiss/Luxembourg -- 13"             D0P-00031

             Graphite -- Swiss/Luxembourg -- 15"             D0Q-00031

             Dune -- Swiss/Luxembourg -- 13"                 D0P-00046

             Sapphire -- Swiss/Luxembourg -- 13"             D0P-00057

             Platinum -- Thai -- 13"                         D0P-00006

             Platinum -- Thai -- 15"                         D0Q-00006

             Graphite -- Thai -- 13"                         D0P-00024

             Graphite -- Thai -- 15"                         D0Q-00024

    **12**   **Micro SD Card Reader**                        

             Micro SD Card Reader -- 15"                     E0J-00001
  ----------------------------------------------------------------------------

+---+------------------------------+---+------------+---+-------------------------+
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| *|                              |* |            | *|                         |
|* |                              | *|            |* |                         |
| [ |                              | [ |            | [ |                         |
| D |                              | E |            | " |                         |
| e |                              | n |            | 4 |                         |
| s |                              | t |            | , |                         |
| c |                              | e |            | 5 |                         |
| r |                              | r |            | , |                         |
| i |                              | > |            | 6 |                         |
| p |                              |   |            | " |                         |
| t |                              | K |            | > |                         |
| i |                              | e |            |   |                         |
| o |                              | y |            | K |                         |
| n |                              | ] |            | e |                         |
| ] |                              | { |            | y |                         |
| { |                              | . |            | s |                         |
| . |                              | u |            | ] |                         |
| u |                              | n |            | { |                         |
| n |                              | d |            | . |                         |
| d |                              | e |            | u |                         |
| e |                              | r |            | n |                         |
| r |                              | l |            | d |                         |
| l |                              | i |            | e |                         |
| i |                              | n |            | r |                         |
| n |                              | e |            | l |                         |
| e |                              | } |            | i |                         |
| } |                              | *|            | n |                         |
|* |                              | *|            | e |                         |
|* |                              |   |            | } |                         |
|   |                              |   |            | *|                         |
|   |                              |   |            |* |                         |
+===+==============================+===+============+===+=========================+
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| 1 |                              | ! |            | ! |                         |
| 0 |                              | [ |            | [ |                         |
| 4 |                              | A |            | A |                         |
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| E |                              | b |            | w |                         |
| n |                              | l |            | h |                         |
| g |                              | a |            | i |                         |
| l |                              | c |            | t |                         |
| i |                              | k |            | e |                         |
| s |                              | > |            | > |                         |
| h |                              |   |            |   |                         |
| , |                              | r |            | s |                         |
| > |                              | e |            | q |                         |
|   |                              | c |            | u |                         |
| U |                              | t |            | a |                         |
| S |                              | a |            | r |                         |
|   |                              | n |            | e |                         |
|   |                              | g |            | > |                         |
|   |                              | l |            |   |                         |
|   |                              | e |            | w |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | t |                         |
|   |                              | w |            | h |                         |
|   |                              | i |            | > |                         |
|   |                              | t |            |   |                         |
|   |                              | h |            | b |                         |
|   |                              | > |            | l |                         |
|   |                              |   |            | a |                         |
|   |                              | b |            | c |                         |
|   |                              | l |            | k |                         |
|   |                              | a |            | > |                         |
|   |                              | c |            |   |                         |
|   |                              | k |            | t |                         |
|   |                              | > |            | e |                         |
|   |                              |   |            | x |                         |
|   |                              | t |            | t |                         |
|   |                              | e |            | > |                         |
|   |                              | x |            |   |                         |
|   |                              | t |            | a |                         |
|   |                              | > |            | n |                         |
|   |                              |   |            | d |                         |
|   |                              | D |            | > |                         |
|   |                              | e |            |   |                         |
|   |                              | s |            | a |                         |
|   |                              | c |            | > |                         |
|   |                              | r |            |   |                         |
|   |                              | i |            | n |                         |
|   |                              | p |            | u |                         |
|   |                              | t |            | m |                         |
|   |                              | i |            | b |                         |
|   |                              | o |            | e |                         |
|   |                              | n |            | r |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | a |            | D |                         |
|   |                              | u |            | e |                         |
|   |                              | t |            | s |                         |
|   |                              | o |            | c |                         |
|   |                              | m |            | r |                         |
|   |                              | a |            | i |                         |
|   |                              | t |            | p |                         |
|   |                              | i |            | t |                         |
|   |                              | c |            | i |                         |
|   |                              | a |            | o |                         |
|   |                              | l |            | n |                         |
|   |                              | l |            | > |                         |
|   |                              | y |            |   |                         |
|   |                              | > |            | a |                         |
|   |                              |   |            | u |                         |
|   |                              | g |            | t |                         |
|   |                              | e |            | o |                         |
|   |                              | n |            | m |                         |
|   |                              | e |            | a |                         |
|   |                              | r |            | t |                         |
|   |                              | a |            | i |                         |
|   |                              | t |            | c |                         |
|   |                              | e |            | a |                         |
|   |                              | d |            | l |                         |
|   |                              | ] |            | l |                         |
|   |                              | ( |            | y |                         |
|   |                              | . |            | > |                         |
|   |                              | / |            |   |                         |
|   |                              | L |            | g |                         |
|   |                              | T |            | e |                         |
|   |                              | 7 |            | n |                         |
|   |                              | p |            | e |                         |
|   |                              | n |            | r |                         |
|   |                              | g |            | a |                         |
|   |                              | / |            | t |                         |
|   |                              | m |            | e |                         |
|   |                              | e |            | d |                         |
|   |                              | d |            | ] |                         |
|   |                              | i |            | ( |                         |
|   |                              | a |            | . |                         |
|   |                              | / |            | / |                         |
|   |                              | i |            | L |                         |
|   |                              | m |            | T |                         |
|   |                              | a |            | 7 |                         |
|   |                              | g |            | p |                         |
|   |                              | e |            | n |                         |
|   |                              | 1 |            | g |                         |
|   |                              | 7 |            | / |                         |
|   |                              | . |            | m |                         |
|   |                              | p |            | e |                         |
|   |                              | n |            | d |                         |
|   |                              | g |            | i |                         |
|   |                              | ) |            | a |                         |
|   |                              | { |            | / |                         |
|   |                              | w |            | i |                         |
|   |                              | i |            | m |                         |
|   |                              | d |            | a |                         |
|   |                              | t |            | g |                         |
|   |                              | h |            | e |                         |
|   |                              | = |            | 1 |                         |
|   |                              | " |            | 8 |                         |
|   |                              | 0 |            | . |                         |
|   |                              | . |            | p |                         |
|   |                              | 8 |            | n |                         |
|   |                              | 3 |            | g |                         |
|   |                              | 6 |            | ) |                         |
|   |                              | 1 |            | { |                         |
|   |                              | 5 |            | w |                         |
|   |                              | 9 |            | i |                         |
|   |                              | 2 |            | d |                         |
|   |                              | 3 |            | t |                         |
|   |                              | 0 |            | h |                         |
|   |                              | 0 |            | = |                         |
|   |                              | 9 |            | " |                         |
|   |                              | 6 |            | 1 |                         |
|   |                              | 2 |            | . |                         |
|   |                              | 3 |            | 8 |                         |
|   |                              | 7 |            | 5 |                         |
|   |                              | 9 |            | 9 |                         |
|   |                              | i |            | 3 |                         |
|   |                              | n |            | 2 |                         |
|   |                              | " |            | 0 |                         |
|   |                              | > |            | 8 |                         |
|   |                              |   |            | 6 |                         |
|   |                              | h |            | 6 |                         |
|   |                              | e |            | 1 |                         |
|   |                              | i |            | 4 |                         |
|   |                              | g |            | 1 |                         |
|   |                              | h |            | 7 |                         |
|   |                              | t |            | 3 |                         |
|   |                              | = |            | 2 |                         |
|   |                              | " |            | 2 |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | n |                         |
|   |                              | 5 |            | " |                         |
|   |                              | 0 |            | > |                         |
|   |                              | 4 |            |   |                         |
|   |                              | 1 |            | h |                         |
|   |                              | 6 |            | e |                         |
|   |                              | 5 |            | i |                         |
|   |                              | 5 |            | g |                         |
|   |                              | 7 |            | h |                         |
|   |                              | 3 |            | t |                         |
|   |                              | 0 |            | = |                         |
|   |                              | 5 |            | " |                         |
|   |                              | 3 |            | 0 |                         |
|   |                              | 3 |            | . |                         |
|   |                              | 6 |            | 5 |                         |
|   |                              | 8 |            | 3 |                         |
|   |                              | 3 |            | 4 |                         |
|   |                              | i |            | 9 |                         |
|   |                              | n |            | 9 |                         |
|   |                              | " |            | 8 |                         |
|   |                              | } |            | 9 |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 8 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 7 |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 7 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| 1 |                              | ! |            | ! |                         |
| 0 |                              | [ |            | [ |                         |
| 5 |                              | A |            | A |                         |
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| C |                              | b |            | w |                         |
| a |                              | l |            | h |                         |
| n |                              | a |            | i |                         |
| a |                              | c |            | t |                         |
| d |                              | k |            | e |                         |
| i |                              | > |            | > |                         |
| a |                              |   |            |   |                         |
| n |                              | a |            | s |                         |
| , |                              | n |            | q |                         |
| > |                              | d |            | u |                         |
|   |                              | > |            | a |                         |
| B |                              |   |            | r |                         |
| i |                              | w |            | e |                         |
| l |                              | h |            | > |                         |
| i |                              | i |            |   |                         |
| n |                              | t |            | w |                         |
| g |                              | e |            | i |                         |
| u |                              | > |            | t |                         |
| a |                              |   |            | h |                         |
| l |                              | d |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | a |            | b |                         |
|   |                              | g |            | l |                         |
|   |                              | r |            | a |                         |
|   |                              | a |            | c |                         |
|   |                              | m |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | D |            | t |                         |
|   |                              | e |            | e |                         |
|   |                              | s |            | x |                         |
|   |                              | c |            | t |                         |
|   |                              | r |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | p |            | D |                         |
|   |                              | t |            | e |                         |
|   |                              | i |            | s |                         |
|   |                              | o |            | c |                         |
|   |                              | n |            | r |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | p |                         |
|   |                              | a |            | t |                         |
|   |                              | u |            | i |                         |
|   |                              | t |            | o |                         |
|   |                              | o |            | n |                         |
|   |                              | m |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | t |            | a |                         |
|   |                              | i |            | u |                         |
|   |                              | c |            | t |                         |
|   |                              | a |            | o |                         |
|   |                              | l |            | m |                         |
|   |                              | l |            | a |                         |
|   |                              | y |            | t |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | c |                         |
|   |                              | g |            | a |                         |
|   |                              | e |            | l |                         |
|   |                              | n |            | l |                         |
|   |                              | e |            | y |                         |
|   |                              | r |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | t |            | g |                         |
|   |                              | e |            | e |                         |
|   |                              | d |            | n |                         |
|   |                              | ] |            | e |                         |
|   |                              | ( |            | r |                         |
|   |                              | . |            | a |                         |
|   |                              | / |            | t |                         |
|   |                              | L |            | e |                         |
|   |                              | T |            | d |                         |
|   |                              | 7 |            | ] |                         |
|   |                              | p |            | ( |                         |
|   |                              | n |            | . |                         |
|   |                              | g |            | / |                         |
|   |                              | / |            | L |                         |
|   |                              | m |            | T |                         |
|   |                              | e |            | 7 |                         |
|   |                              | d |            | p |                         |
|   |                              | i |            | n |                         |
|   |                              | a |            | g |                         |
|   |                              | / |            | / |                         |
|   |                              | i |            | m |                         |
|   |                              | m |            | e |                         |
|   |                              | a |            | d |                         |
|   |                              | g |            | i |                         |
|   |                              | e |            | a |                         |
|   |                              | 1 |            | / |                         |
|   |                              | 9 |            | i |                         |
|   |                              | . |            | m |                         |
|   |                              | p |            | a |                         |
|   |                              | n |            | g |                         |
|   |                              | g |            | e |                         |
|   |                              | ) |            | 2 |                         |
|   |                              | { |            | 0 |                         |
|   |                              | w |            | . |                         |
|   |                              | i |            | j |                         |
|   |                              | d |            | p |                         |
|   |                              | t |            | e |                         |
|   |                              | h |            | g |                         |
|   |                              | = |            | ) |                         |
|   |                              | " |            | { |                         |
|   |                              | 0 |            | w |                         |
|   |                              | . |            | i |                         |
|   |                              | 4 |            | d |                         |
|   |                              | 8 |            | t |                         |
|   |                              | 4 |            | h |                         |
|   |                              | 2 |            | = |                         |
|   |                              | 9 |            | " |                         |
|   |                              | 2 |            | 1 |                         |
|   |                              | 4 |            | . |                         |
|   |                              | 3 |            | 8 |                         |
|   |                              | 2 |            | 7 |                         |
|   |                              | 1 |            | 4 |                         |
|   |                              | 9 |            | 3 |                         |
|   |                              | 5 |            | 6 |                         |
|   |                              | 9 |            | 1 |                         |
|   |                              | 7 |            | 3 |                         |
|   |                              | 5 |            | 2 |                         |
|   |                              | 5 |            | 9 |                         |
|   |                              | i |            | 8 |                         |
|   |                              | n |            | 3 |                         |
|   |                              | " |            | 3 |                         |
|   |                              | > |            | 7 |                         |
|   |                              |   |            | 7 |                         |
|   |                              | h |            | 0 |                         |
|   |                              | e |            | 7 |                         |
|   |                              | i |            | i |                         |
|   |                              | g |            | n |                         |
|   |                              | h |            | " |                         |
|   |                              | t |            | > |                         |
|   |                              | = |            |   |                         |
|   |                              | " |            | h |                         |
|   |                              | 0 |            | e |                         |
|   |                              | . |            | i |                         |
|   |                              | 8 |            | g |                         |
|   |                              | 3 |            | h |                         |
|   |                              | 9 |            | t |                         |
|   |                              | 5 |            | = |                         |
|   |                              | 8 |            | " |                         |
|   |                              | 3 |            | 0 |                         |
|   |                              | 3 |            | . |                         |
|   |                              | 3 |            | 5 |                         |
|   |                              | 3 |            | 4 |                         |
|   |                              | 3 |            | 3 |                         |
|   |                              | 3 |            | 7 |                         |
|   |                              | 3 |            | 4 |                         |
|   |                              | 3 |            | 8 |                         |
|   |                              | 3 |            | 9 |                         |
|   |                              | 3 |            | 0 |                         |
|   |                              | 3 |            | 6 |                         |
|   |                              | i |            | 3 |                         |
|   |                              | n |            | 8 |                         |
|   |                              | " |            | 6 |                         |
|   |                              | } |            | 7 |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 7 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| 1 |                              | ! |            | ! |                         |
| 0 |                              | [ |            | [ |                         |
| 9 |                              | A |            | A |                         |
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| J |                              | w |            | w |                         |
| a |                              | h |            | h |                         |
| p |                              | i |            | i |                         |
| a |                              | t |            | t |                         |
| n |                              | e |            | e |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | r |            | s |                         |
|   |                              | e |            | q |                         |
|   |                              | c |            | u |                         |
|   |                              | t |            | a |                         |
|   |                              | a |            | r |                         |
|   |                              | n |            | e |                         |
|   |                              | g |            | > |                         |
|   |                              | u |            |   |                         |
|   |                              | l |            | w |                         |
|   |                              | a |            | i |                         |
|   |                              | r |            | t |                         |
|   |                              | > |            | h |                         |
|   |                              |   |            | > |                         |
|   |                              | o |            |   |                         |
|   |                              | b |            | b |                         |
|   |                              | j |            | l |                         |
|   |                              | e |            | a |                         |
|   |                              | c |            | c |                         |
|   |                              | t |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | w |            | t |                         |
|   |                              | i |            | e |                         |
|   |                              | t |            | x |                         |
|   |                              | h |            | t |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | a |            | D |                         |
|   |                              | > |            | e |                         |
|   |                              |   |            | s |                         |
|   |                              | b |            | c |                         |
|   |                              | l |            | r |                         |
|   |                              | a |            | i |                         |
|   |                              | c |            | p |                         |
|   |                              | k |            | t |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | o |                         |
|   |                              | a |            | n |                         |
|   |                              | r |            | > |                         |
|   |                              | r |            |   |                         |
|   |                              | o |            | a |                         |
|   |                              | w |            | u |                         |
|   |                              | > |            | t |                         |
|   |                              |   |            | o |                         |
|   |                              | D |            | m |                         |
|   |                              | e |            | a |                         |
|   |                              | s |            | t |                         |
|   |                              | c |            | i |                         |
|   |                              | r |            | c |                         |
|   |                              | i |            | a |                         |
|   |                              | p |            | l |                         |
|   |                              | t |            | l |                         |
|   |                              | i |            | y |                         |
|   |                              | o |            | > |                         |
|   |                              | n |            |   |                         |
|   |                              | > |            | g |                         |
|   |                              |   |            | e |                         |
|   |                              | a |            | n |                         |
|   |                              | u |            | e |                         |
|   |                              | t |            | r |                         |
|   |                              | o |            | a |                         |
|   |                              | m |            | t |                         |
|   |                              | a |            | e |                         |
|   |                              | t |            | d |                         |
|   |                              | i |            | ] |                         |
|   |                              | c |            | ( |                         |
|   |                              | a |            | . |                         |
|   |                              | l |            | / |                         |
|   |                              | l |            | L |                         |
|   |                              | y |            | T |                         |
|   |                              | > |            | 7 |                         |
|   |                              |   |            | p |                         |
|   |                              | g |            | n |                         |
|   |                              | e |            | g |                         |
|   |                              | n |            | / |                         |
|   |                              | e |            | m |                         |
|   |                              | r |            | e |                         |
|   |                              | a |            | d |                         |
|   |                              | t |            | i |                         |
|   |                              | e |            | a |                         |
|   |                              | d |            | / |                         |
|   |                              | ] |            | i |                         |
|   |                              | ( |            | m |                         |
|   |                              | . |            | a |                         |
|   |                              | / |            | g |                         |
|   |                              | L |            | e |                         |
|   |                              | T |            | 2 |                         |
|   |                              | 7 |            | 2 |                         |
|   |                              | p |            | . |                         |
|   |                              | n |            | p |                         |
|   |                              | g |            | n |                         |
|   |                              | / |            | g |                         |
|   |                              | m |            | ) |                         |
|   |                              | e |            | { |                         |
|   |                              | d |            | w |                         |
|   |                              | i |            | i |                         |
|   |                              | a |            | d |                         |
|   |                              | / |            | t |                         |
|   |                              | i |            | h |                         |
|   |                              | m |            | = |                         |
|   |                              | a |            | " |                         |
|   |                              | g |            | 1 |                         |
|   |                              | e |            | . |                         |
|   |                              | 2 |            | 9 |                         |
|   |                              | 1 |            | 3 |                         |
|   |                              | . |            | 7 |                         |
|   |                              | j |            | 9 |                         |
|   |                              | p |            | 4 |                         |
|   |                              | e |            | 9 |                         |
|   |                              | g |            | 4 |                         |
|   |                              | ) |            | 7 |                         |
|   |                              | { |            | 5 |                         |
|   |                              | w |            | 0 |                         |
|   |                              | i |            | 6 |                         |
|   |                              | d |            | 5 |                         |
|   |                              | t |            | 6 |                         |
|   |                              | h |            | 1 |                         |
|   |                              | = |            | 6 |                         |
|   |                              | " |            | 8 |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | n |                         |
|   |                              | 5 |            | " |                         |
|   |                              | 1 |            | > |                         |
|   |                              | 5 |            |   |                         |
|   |                              | 6 |            | h |                         |
|   |                              | 2 |            | e |                         |
|   |                              | 6 |            | i |                         |
|   |                              | 6 |            | g |                         |
|   |                              | 4 |            | h |                         |
|   |                              | 0 |            | t |                         |
|   |                              | 4 |            | = |                         |
|   |                              | 1 |            | " |                         |
|   |                              | 9 |            | 0 |                         |
|   |                              | 9 |            | . |                         |
|   |                              | 4 |            | 5 |                         |
|   |                              | 7 |            | 5 |                         |
|   |                              | 5 |            | 7 |                         |
|   |                              | i |            | 2 |                         |
|   |                              | n |            | 9 |                         |
|   |                              | " |            | 1 |                         |
|   |                              | > |            | 1 |                         |
|   |                              |   |            | 1 |                         |
|   |                              | h |            | 9 |                         |
|   |                              | e |            | 8 |                         |
|   |                              | i |            | 6 |                         |
|   |                              | g |            | 0 |                         |
|   |                              | h |            | 0 |                         |
|   |                              | t |            | 1 |                         |
|   |                              | = |            | 7 |                         |
|   |                              | " |            | 4 |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | n |                         |
|   |                              | 8 |            | " |                         |
|   |                              | 6 |            | } |                         |
|   |                              | 8 |            |   |                         |
|   |                              | 7 |            |   |                         |
|   |                              | 5 |            |   |                         |
|   |                              | i |            |   |                         |
|   |                              | n |            |   |                         |
|   |                              | " |            |   |                         |
|   |                              | } |            |   |                         |
+---+------------------------------+---+------------+---+-------------------------+
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| 1 |                              | ! |            | ! |                         |
| 0 |                              | [ |            | [ |                         |
| 5 |                              | A |            | A |                         |
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| A |                              | b |            | w |                         |
| u |                              | l |            | h |                         |
| s |                              | a |            | i |                         |
| t |                              | c |            | t |                         |
| r |                              | k |            | e |                         |
| i |                              | > |            | > |                         |
| a |                              |   |            |   |                         |
| / |                              | a |            | s |                         |
| G |                              | n |            | q |                         |
| e |                              | d |            | u |                         |
| r |                              | > |            | a |                         |
| m |                              |   |            | r |                         |
| a |                              | w |            | e |                         |
| n |                              | h |            | > |                         |
| y |                              | i |            |   |                         |
|   |                              | t |            | w |                         |
|   |                              | e |            | i |                         |
|   |                              | > |            | t |                         |
|   |                              |   |            | h |                         |
|   |                              | d |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | a |            | b |                         |
|   |                              | g |            | l |                         |
|   |                              | r |            | a |                         |
|   |                              | a |            | c |                         |
|   |                              | m |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | D |            | t |                         |
|   |                              | e |            | e |                         |
|   |                              | s |            | x |                         |
|   |                              | c |            | t |                         |
|   |                              | r |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | p |            | a |                         |
|   |                              | t |            | n |                         |
|   |                              | i |            | d |                         |
|   |                              | o |            | > |                         |
|   |                              | n |            |   |                         |
|   |                              | > |            | n |                         |
|   |                              |   |            | u |                         |
|   |                              | a |            | m |                         |
|   |                              | u |            | b |                         |
|   |                              | t |            | e |                         |
|   |                              | o |            | r |                         |
|   |                              | m |            | s |                         |
|   |                              | a |            | > |                         |
|   |                              | t |            |   |                         |
|   |                              | i |            | D |                         |
|   |                              | c |            | e |                         |
|   |                              | a |            | s |                         |
|   |                              | l |            | c |                         |
|   |                              | l |            | r |                         |
|   |                              | y |            | i |                         |
|   |                              | > |            | p |                         |
|   |                              |   |            | t |                         |
|   |                              | g |            | i |                         |
|   |                              | e |            | o |                         |
|   |                              | n |            | n |                         |
|   |                              | e |            | > |                         |
|   |                              | r |            |   |                         |
|   |                              | a |            | a |                         |
|   |                              | t |            | u |                         |
|   |                              | e |            | t |                         |
|   |                              | d |            | o |                         |
|   |                              | ] |            | m |                         |
|   |                              | ( |            | a |                         |
|   |                              | . |            | t |                         |
|   |                              | / |            | i |                         |
|   |                              | L |            | c |                         |
|   |                              | T |            | a |                         |
|   |                              | 7 |            | l |                         |
|   |                              | p |            | l |                         |
|   |                              | n |            | y |                         |
|   |                              | g |            | > |                         |
|   |                              | / |            |   |                         |
|   |                              | m |            | g |                         |
|   |                              | e |            | e |                         |
|   |                              | d |            | n |                         |
|   |                              | i |            | e |                         |
|   |                              | a |            | r |                         |
|   |                              | / |            | a |                         |
|   |                              | i |            | t |                         |
|   |                              | m |            | e |                         |
|   |                              | a |            | d |                         |
|   |                              | g |            | ] |                         |
|   |                              | e |            | ( |                         |
|   |                              | 1 |            | . |                         |
|   |                              | 9 |            | / |                         |
|   |                              | . |            | L |                         |
|   |                              | p |            | T |                         |
|   |                              | n |            | 7 |                         |
|   |                              | g |            | p |                         |
|   |                              | ) |            | n |                         |
|   |                              | { |            | g |                         |
|   |                              | w |            | / |                         |
|   |                              | i |            | m |                         |
|   |                              | d |            | e |                         |
|   |                              | t |            | d |                         |
|   |                              | h |            | i |                         |
|   |                              | = |            | a |                         |
|   |                              | " |            | / |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | m |                         |
|   |                              | 4 |            | a |                         |
|   |                              | 8 |            | g |                         |
|   |                              | 4 |            | e |                         |
|   |                              | 2 |            | 2 |                         |
|   |                              | 9 |            | 3 |                         |
|   |                              | 2 |            | . |                         |
|   |                              | 4 |            | p |                         |
|   |                              | 3 |            | n |                         |
|   |                              | 2 |            | g |                         |
|   |                              | 1 |            | ) |                         |
|   |                              | 9 |            | { |                         |
|   |                              | 5 |            | w |                         |
|   |                              | 9 |            | i |                         |
|   |                              | 7 |            | d |                         |
|   |                              | 5 |            | t |                         |
|   |                              | 5 |            | h |                         |
|   |                              | i |            | = |                         |
|   |                              | n |            | " |                         |
|   |                              | " |            | 1 |                         |
|   |                              | > |            | . |                         |
|   |                              |   |            | 8 |                         |
|   |                              | h |            | 9 |                         |
|   |                              | e |            | 8 |                         |
|   |                              | i |            | 3 |                         |
|   |                              | g |            | 3 |                         |
|   |                              | h |            | 0 |                         |
|   |                              | t |            | 0 |                         |
|   |                              | = |            | 5 |                         |
|   |                              | " |            | 2 |                         |
|   |                              | 0 |            | 4 |                         |
|   |                              | . |            | 9 |                         |
|   |                              | 8 |            | 3 |                         |
|   |                              | 3 |            | 4 |                         |
|   |                              | 9 |            | 3 |                         |
|   |                              | 5 |            | 8 |                         |
|   |                              | 8 |            | 3 |                         |
|   |                              | 2 |            | i |                         |
|   |                              | 2 |            | n |                         |
|   |                              | 3 |            | " |                         |
|   |                              | 9 |            | > |                         |
|   |                              | 7 |            |   |                         |
|   |                              | 2 |            | h |                         |
|   |                              | 0 |            | e |                         |
|   |                              | 0 |            | i |                         |
|   |                              | 3 |            | g |                         |
|   |                              | 5 |            | h |                         |
|   |                              | i |            | t |                         |
|   |                              | n |            | = |                         |
|   |                              | " |            | " |                         |
|   |                              | } |            | 0 |                         |
|   |                              |   |            | . |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 2 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 9 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| 1 |                              | ! |            | ! |                         |
| 0 |                              | [ |            | [ |                         |
| 5 |                              | A |            | A |                         |
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| B |                              | b |            | w |                         |
| e |                              | l |            | h |                         |
| l |                              | a |            | i |                         |
| g |                              | c |            | t |                         |
| i |                              | k |            | e |                         |
| u |                              | > |            | > |                         |
| m |                              |   |            |   |                         |
| > |                              | a |            | s |                         |
|   |                              | n |            | q |                         |
| A |                              | d |            | u |                         |
| Z |                              | > |            | a |                         |
| E |                              |   |            | r |                         |
| R |                              | w |            | e |                         |
| T |                              | h |            | > |                         |
| Y |                              | i |            |   |                         |
|   |                              | t |            | w |                         |
|   |                              | e |            | i |                         |
|   |                              | > |            | t |                         |
|   |                              |   |            | h |                         |
|   |                              | d |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | a |            | b |                         |
|   |                              | g |            | l |                         |
|   |                              | r |            | a |                         |
|   |                              | a |            | c |                         |
|   |                              | m |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | D |            | n |                         |
|   |                              | e |            | u |                         |
|   |                              | s |            | m |                         |
|   |                              | c |            | b |                         |
|   |                              | r |            | e |                         |
|   |                              | i |            | r |                         |
|   |                              | p |            | s |                         |
|   |                              | t |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | o |            | a |                         |
|   |                              | n |            | n |                         |
|   |                              | > |            | d |                         |
|   |                              |   |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | u |            | a |                         |
|   |                              | t |            | > |                         |
|   |                              | o |            |   |                         |
|   |                              | m |            | w |                         |
|   |                              | a |            | h |                         |
|   |                              | t |            | i |                         |
|   |                              | i |            | t |                         |
|   |                              | c |            | e |                         |
|   |                              | a |            | > |                         |
|   |                              | l |            |   |                         |
|   |                              | l |            | b |                         |
|   |                              | y |            | a |                         |
|   |                              | > |            | c |                         |
|   |                              |   |            | k |                         |
|   |                              | g |            | g |                         |
|   |                              | e |            | r |                         |
|   |                              | n |            | o |                         |
|   |                              | e |            | u |                         |
|   |                              | r |            | n |                         |
|   |                              | a |            | d |                         |
|   |                              | t |            | > |                         |
|   |                              | e |            |   |                         |
|   |                              | d |            | D |                         |
|   |                              | ] |            | e |                         |
|   |                              | ( |            | s |                         |
|   |                              | . |            | c |                         |
|   |                              | / |            | r |                         |
|   |                              | L |            | i |                         |
|   |                              | T |            | p |                         |
|   |                              | 7 |            | t |                         |
|   |                              | p |            | i |                         |
|   |                              | n |            | o |                         |
|   |                              | g |            | n |                         |
|   |                              | / |            | > |                         |
|   |                              | m |            |   |                         |
|   |                              | e |            | a |                         |
|   |                              | d |            | u |                         |
|   |                              | i |            | t |                         |
|   |                              | a |            | o |                         |
|   |                              | / |            | m |                         |
|   |                              | i |            | a |                         |
|   |                              | m |            | t |                         |
|   |                              | a |            | i |                         |
|   |                              | g |            | c |                         |
|   |                              | e |            | a |                         |
|   |                              | 1 |            | l |                         |
|   |                              | 9 |            | l |                         |
|   |                              | . |            | y |                         |
|   |                              | p |            | > |                         |
|   |                              | n |            |   |                         |
|   |                              | g |            | g |                         |
|   |                              | ) |            | e |                         |
|   |                              | { |            | n |                         |
|   |                              | w |            | e |                         |
|   |                              | i |            | r |                         |
|   |                              | d |            | a |                         |
|   |                              | t |            | t |                         |
|   |                              | h |            | e |                         |
|   |                              | = |            | d |                         |
|   |                              | " |            | ] |                         |
|   |                              | 0 |            | ( |                         |
|   |                              | . |            | . |                         |
|   |                              | 4 |            | / |                         |
|   |                              | 8 |            | L |                         |
|   |                              | 4 |            | T |                         |
|   |                              | 2 |            | 7 |                         |
|   |                              | 9 |            | p |                         |
|   |                              | 1 |            | n |                         |
|   |                              | 3 |            | g |                         |
|   |                              | 3 |            | / |                         |
|   |                              | 8 |            | m |                         |
|   |                              | 5 |            | e |                         |
|   |                              | 8 |            | d |                         |
|   |                              | 2 |            | i |                         |
|   |                              | 6 |            | a |                         |
|   |                              | 7 |            | / |                         |
|   |                              | 7 |            | i |                         |
|   |                              | 1 |            | m |                         |
|   |                              | 4 |            | a |                         |
|   |                              | i |            | g |                         |
|   |                              | n |            | e |                         |
|   |                              | " |            | 2 |                         |
|   |                              | > |            | 4 |                         |
|   |                              |   |            | . |                         |
|   |                              | h |            | p |                         |
|   |                              | e |            | n |                         |
|   |                              | i |            | g |                         |
|   |                              | g |            | ) |                         |
|   |                              | h |            | { |                         |
|   |                              | t |            | w |                         |
|   |                              | = |            | i |                         |
|   |                              | " |            | d |                         |
|   |                              | 0 |            | t |                         |
|   |                              | . |            | h |                         |
|   |                              | 8 |            | = |                         |
|   |                              | 3 |            | " |                         |
|   |                              | 9 |            | 1 |                         |
|   |                              | 5 |            | . |                         |
|   |                              | 8 |            | 9 |                         |
|   |                              | 2 |            | 7 |                         |
|   |                              | 2 |            | 6 |                         |
|   |                              | 3 |            | 3 |                         |
|   |                              | 9 |            | 2 |                         |
|   |                              | 7 |            | 2 |                         |
|   |                              | 2 |            | 1 |                         |
|   |                              | 0 |            | 7 |                         |
|   |                              | 0 |            | 8 |                         |
|   |                              | 3 |            | 4 |                         |
|   |                              | 5 |            | 7 |                         |
|   |                              | i |            | 7 |                         |
|   |                              | n |            | 6 |                         |
|   |                              | " |            | 9 |                         |
|   |                              | } |            | 0 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              |   |            | h |                         |
|   |                              |   |            | e |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | g |                         |
|   |                              |   |            | h |                         |
|   |                              |   |            | t |                         |
|   |                              |   |            | = |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | . |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 8 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 7 |                         |
|   |                              |   |            | 2 |                         |
|   |                              |   |            | 2 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 9 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 7 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| 1 |                              | ! |            | ! |                         |
| 0 |                              | [ |            | [ |                         |
| 5 |                              | A |            | A |                         |
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| N |                              | b |            | w |                         |
| o |                              | l |            | h |                         |
| r |                              | a |            | i |                         |
| d |                              | c |            | t |                         |
| i |                              | k |            | e |                         |
| c |                              | > |            | > |                         |
| > |                              |   |            |   |                         |
|   |                              | a |            | s |                         |
| D |                              | n |            | q |                         |
| e |                              | d |            | u |                         |
| n |                              | > |            | a |                         |
| m |                              |   |            | r |                         |
| a |                              | w |            | e |                         |
| r |                              | h |            | > |                         |
| k |                              | i |            |   |                         |
| , |                              | t |            | w |                         |
| > |                              | e |            | i |                         |
|   |                              | > |            | t |                         |
| F |                              |   |            | h |                         |
| i |                              | d |            | > |                         |
| n |                              | i |            |   |                         |
| l |                              | a |            | b |                         |
| a |                              | g |            | l |                         |
| n |                              | r |            | a |                         |
| d |                              | a |            | c |                         |
| , |                              | m |            | k |                         |
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| N |                              | D |            | t |                         |
| o |                              | e |            | e |                         |
| r |                              | s |            | x |                         |
| w |                              | c |            | t |                         |
| a |                              | r |            | > |                         |
| y |                              | i |            |   |                         |
| , |                              | p |            | a |                         |
| > |                              | t |            | n |                         |
|   |                              | i |            | d |                         |
| S |                              | o |            | > |                         |
| w |                              | n |            |   |                         |
| e |                              | > |            | n |                         |
| d |                              |   |            | u |                         |
| e |                              | a |            | m |                         |
| n |                              | u |            | b |                         |
|   |                              | t |            | e |                         |
|   |                              | o |            | r |                         |
|   |                              | m |            | s |                         |
|   |                              | a |            | > |                         |
|   |                              | t |            |   |                         |
|   |                              | i |            | D |                         |
|   |                              | c |            | e |                         |
|   |                              | a |            | s |                         |
|   |                              | l |            | c |                         |
|   |                              | l |            | r |                         |
|   |                              | y |            | i |                         |
|   |                              | > |            | p |                         |
|   |                              |   |            | t |                         |
|   |                              | g |            | i |                         |
|   |                              | e |            | o |                         |
|   |                              | n |            | n |                         |
|   |                              | e |            | > |                         |
|   |                              | r |            |   |                         |
|   |                              | a |            | a |                         |
|   |                              | t |            | u |                         |
|   |                              | e |            | t |                         |
|   |                              | d |            | o |                         |
|   |                              | ] |            | m |                         |
|   |                              | ( |            | a |                         |
|   |                              | . |            | t |                         |
|   |                              | / |            | i |                         |
|   |                              | L |            | c |                         |
|   |                              | T |            | a |                         |
|   |                              | 7 |            | l |                         |
|   |                              | p |            | l |                         |
|   |                              | n |            | y |                         |
|   |                              | g |            | > |                         |
|   |                              | / |            |   |                         |
|   |                              | m |            | g |                         |
|   |                              | e |            | e |                         |
|   |                              | d |            | n |                         |
|   |                              | i |            | e |                         |
|   |                              | a |            | r |                         |
|   |                              | / |            | a |                         |
|   |                              | i |            | t |                         |
|   |                              | m |            | e |                         |
|   |                              | a |            | d |                         |
|   |                              | g |            | ] |                         |
|   |                              | e |            | ( |                         |
|   |                              | 1 |            | . |                         |
|   |                              | 9 |            | / |                         |
|   |                              | . |            | L |                         |
|   |                              | p |            | T |                         |
|   |                              | n |            | 7 |                         |
|   |                              | g |            | p |                         |
|   |                              | ) |            | n |                         |
|   |                              | { |            | g |                         |
|   |                              | w |            | / |                         |
|   |                              | i |            | m |                         |
|   |                              | d |            | e |                         |
|   |                              | t |            | d |                         |
|   |                              | h |            | i |                         |
|   |                              | = |            | a |                         |
|   |                              | " |            | / |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | m |                         |
|   |                              | 4 |            | a |                         |
|   |                              | 8 |            | g |                         |
|   |                              | 4 |            | e |                         |
|   |                              | 2 |            | 2 |                         |
|   |                              | 9 |            | 5 |                         |
|   |                              | 1 |            | . |                         |
|   |                              | 3 |            | p |                         |
|   |                              | 3 |            | n |                         |
|   |                              | 8 |            | g |                         |
|   |                              | 5 |            | ) |                         |
|   |                              | 8 |            | { |                         |
|   |                              | 2 |            | w |                         |
|   |                              | 6 |            | i |                         |
|   |                              | 7 |            | d |                         |
|   |                              | 7 |            | t |                         |
|   |                              | 1 |            | h |                         |
|   |                              | 4 |            | = |                         |
|   |                              | i |            | " |                         |
|   |                              | n |            | 1 |                         |
|   |                              | " |            | . |                         |
|   |                              | > |            | 9 |                         |
|   |                              |   |            | 3 |                         |
|   |                              | h |            | 7 |                         |
|   |                              | e |            | 4 |                         |
|   |                              | i |            | 7 |                         |
|   |                              | g |            | 5 |                         |
|   |                              | h |            | 9 |                         |
|   |                              | t |            | 4 |                         |
|   |                              | = |            | 0 |                         |
|   |                              | " |            | 5 |                         |
|   |                              | 0 |            | 0 |                         |
|   |                              | . |            | 7 |                         |
|   |                              | 8 |            | 4 |                         |
|   |                              | 3 |            | 3 |                         |
|   |                              | 9 |            | 6 |                         |
|   |                              | 5 |            | 7 |                         |
|   |                              | 8 |            | i |                         |
|   |                              | 2 |            | n |                         |
|   |                              | 2 |            | " |                         |
|   |                              | 3 |            | > |                         |
|   |                              | 9 |            |   |                         |
|   |                              | 7 |            | h |                         |
|   |                              | 2 |            | e |                         |
|   |                              | 0 |            | i |                         |
|   |                              | 0 |            | g |                         |
|   |                              | 3 |            | h |                         |
|   |                              | 5 |            | t |                         |
|   |                              | i |            | = |                         |
|   |                              | n |            | " |                         |
|   |                              | " |            | 0 |                         |
|   |                              | } |            | . |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 7 |                         |
|   |                              |   |            | 2 |                         |
|   |                              |   |            | 9 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 9 |                         |
|   |                              |   |            | 8 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 7 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| 1 |                              | ! |            | ! |                         |
| 0 |                              | [ |            | [ |                         |
| 5 |                              | A |            | A |                         |
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| F |                              | b |            | w |                         |
| r |                              | l |            | h |                         |
| e |                              | a |            | i |                         |
| n |                              | c |            | t |                         |
| c |                              | k |            | e |                         |
| h |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | a |            | s |                         |
|   |                              | n |            | q |                         |
|   |                              | d |            | u |                         |
|   |                              | > |            | a |                         |
|   |                              |   |            | r |                         |
|   |                              | w |            | e |                         |
|   |                              | h |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | t |            | w |                         |
|   |                              | e |            | i |                         |
|   |                              | > |            | t |                         |
|   |                              |   |            | h |                         |
|   |                              | d |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | a |            | b |                         |
|   |                              | g |            | l |                         |
|   |                              | r |            | a |                         |
|   |                              | a |            | c |                         |
|   |                              | m |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | D |            | n |                         |
|   |                              | e |            | u |                         |
|   |                              | s |            | m |                         |
|   |                              | c |            | b |                         |
|   |                              | r |            | e |                         |
|   |                              | i |            | r |                         |
|   |                              | p |            | s |                         |
|   |                              | t |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | o |            | a |                         |
|   |                              | n |            | n |                         |
|   |                              | > |            | d |                         |
|   |                              |   |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | u |            | a |                         |
|   |                              | t |            | > |                         |
|   |                              | o |            |   |                         |
|   |                              | m |            | w |                         |
|   |                              | a |            | h |                         |
|   |                              | t |            | i |                         |
|   |                              | i |            | t |                         |
|   |                              | c |            | e |                         |
|   |                              | a |            | > |                         |
|   |                              | l |            |   |                         |
|   |                              | l |            | b |                         |
|   |                              | y |            | a |                         |
|   |                              | > |            | c |                         |
|   |                              |   |            | k |                         |
|   |                              | g |            | g |                         |
|   |                              | e |            | r |                         |
|   |                              | n |            | o |                         |
|   |                              | e |            | u |                         |
|   |                              | r |            | n |                         |
|   |                              | a |            | d |                         |
|   |                              | t |            | > |                         |
|   |                              | e |            |   |                         |
|   |                              | d |            | D |                         |
|   |                              | ] |            | e |                         |
|   |                              | ( |            | s |                         |
|   |                              | . |            | c |                         |
|   |                              | / |            | r |                         |
|   |                              | L |            | i |                         |
|   |                              | T |            | p |                         |
|   |                              | 7 |            | t |                         |
|   |                              | p |            | i |                         |
|   |                              | n |            | o |                         |
|   |                              | g |            | n |                         |
|   |                              | / |            | > |                         |
|   |                              | m |            |   |                         |
|   |                              | e |            | a |                         |
|   |                              | d |            | u |                         |
|   |                              | i |            | t |                         |
|   |                              | a |            | o |                         |
|   |                              | / |            | m |                         |
|   |                              | i |            | a |                         |
|   |                              | m |            | t |                         |
|   |                              | a |            | i |                         |
|   |                              | g |            | c |                         |
|   |                              | e |            | a |                         |
|   |                              | 1 |            | l |                         |
|   |                              | 9 |            | l |                         |
|   |                              | . |            | y |                         |
|   |                              | p |            | > |                         |
|   |                              | n |            |   |                         |
|   |                              | g |            | g |                         |
|   |                              | ) |            | e |                         |
|   |                              | { |            | n |                         |
|   |                              | w |            | e |                         |
|   |                              | i |            | r |                         |
|   |                              | d |            | a |                         |
|   |                              | t |            | t |                         |
|   |                              | h |            | e |                         |
|   |                              | = |            | d |                         |
|   |                              | " |            | ] |                         |
|   |                              | 0 |            | ( |                         |
|   |                              | . |            | . |                         |
|   |                              | 4 |            | / |                         |
|   |                              | 8 |            | L |                         |
|   |                              | 4 |            | T |                         |
|   |                              | 2 |            | 7 |                         |
|   |                              | 9 |            | p |                         |
|   |                              | 1 |            | n |                         |
|   |                              | 3 |            | g |                         |
|   |                              | 3 |            | / |                         |
|   |                              | 8 |            | m |                         |
|   |                              | 5 |            | e |                         |
|   |                              | 8 |            | d |                         |
|   |                              | 2 |            | i |                         |
|   |                              | 6 |            | a |                         |
|   |                              | 7 |            | / |                         |
|   |                              | 7 |            | i |                         |
|   |                              | 1 |            | m |                         |
|   |                              | 4 |            | a |                         |
|   |                              | i |            | g |                         |
|   |                              | n |            | e |                         |
|   |                              | " |            | 2 |                         |
|   |                              | > |            | 6 |                         |
|   |                              |   |            | . |                         |
|   |                              | h |            | p |                         |
|   |                              | e |            | n |                         |
|   |                              | i |            | g |                         |
|   |                              | g |            | ) |                         |
|   |                              | h |            | { |                         |
|   |                              | t |            | w |                         |
|   |                              | = |            | i |                         |
|   |                              | " |            | d |                         |
|   |                              | 0 |            | t |                         |
|   |                              | . |            | h |                         |
|   |                              | 8 |            | = |                         |
|   |                              | 3 |            | " |                         |
|   |                              | 9 |            | 1 |                         |
|   |                              | 5 |            | . |                         |
|   |                              | 8 |            | 8 |                         |
|   |                              | 2 |            | 9 |                         |
|   |                              | 2 |            | 8 |                         |
|   |                              | 3 |            | 1 |                         |
|   |                              | 9 |            | 2 |                         |
|   |                              | 7 |            | 1 |                         |
|   |                              | 2 |            | 1 |                         |
|   |                              | 0 |            | 7 |                         |
|   |                              | 0 |            | 2 |                         |
|   |                              | 3 |            | 3 |                         |
|   |                              | 5 |            | 5 |                         |
|   |                              | i |            | 3 |                         |
|   |                              | n |            | 4 |                         |
|   |                              | " |            | 5 |                         |
|   |                              | } |            | 6 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              |   |            | h |                         |
|   |                              |   |            | e |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | g |                         |
|   |                              |   |            | h |                         |
|   |                              |   |            | t |                         |
|   |                              |   |            | = |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | . |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 2 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 9 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| 1 |                              | ! |            | ! |                         |
| 0 |                              | [ |            | [ |                         |
| 5 |                              | A |            | A |                         |
| > |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
| E |                              | b |            | w |                         |
| n |                              | l |            | h |                         |
| g |                              | a |            | i |                         |
| l |                              | c |            | t |                         |
| i |                              | k |            | e |                         |
| s |                              | > |            | > |                         |
| h |                              |   |            |   |                         |
| , |                              | a |            | s |                         |
| > |                              | n |            | q |                         |
|   |                              | d |            | u |                         |
| U |                              | > |            | a |                         |
| K |                              |   |            | r |                         |
| > |                              | w |            | e |                         |
|   |                              | h |            | > |                         |
| I |                              | i |            |   |                         |
| r |                              | t |            | w |                         |
| e |                              | e |            | i |                         |
| l |                              | > |            | t |                         |
| a |                              |   |            | h |                         |
| n |                              | d |            | > |                         |
| d |                              | i |            |   |                         |
|   |                              | a |            | b |                         |
|   |                              | g |            | l |                         |
|   |                              | r |            | a |                         |
|   |                              | a |            | c |                         |
|   |                              | m |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | D |            | t |                         |
|   |                              | e |            | e |                         |
|   |                              | s |            | x |                         |
|   |                              | c |            | t |                         |
|   |                              | r |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | p |            | a |                         |
|   |                              | t |            | n |                         |
|   |                              | i |            | d |                         |
|   |                              | o |            | > |                         |
|   |                              | n |            |   |                         |
|   |                              | > |            | n |                         |
|   |                              |   |            | u |                         |
|   |                              | a |            | m |                         |
|   |                              | u |            | b |                         |
|   |                              | t |            | e |                         |
|   |                              | o |            | r |                         |
|   |                              | m |            | s |                         |
|   |                              | a |            | > |                         |
|   |                              | t |            |   |                         |
|   |                              | i |            | D |                         |
|   |                              | c |            | e |                         |
|   |                              | a |            | s |                         |
|   |                              | l |            | c |                         |
|   |                              | l |            | r |                         |
|   |                              | y |            | i |                         |
|   |                              | > |            | p |                         |
|   |                              |   |            | t |                         |
|   |                              | g |            | i |                         |
|   |                              | e |            | o |                         |
|   |                              | n |            | n |                         |
|   |                              | e |            | > |                         |
|   |                              | r |            |   |                         |
|   |                              | a |            | a |                         |
|   |                              | t |            | u |                         |
|   |                              | e |            | t |                         |
|   |                              | d |            | o |                         |
|   |                              | ] |            | m |                         |
|   |                              | ( |            | a |                         |
|   |                              | . |            | t |                         |
|   |                              | / |            | i |                         |
|   |                              | L |            | c |                         |
|   |                              | T |            | a |                         |
|   |                              | 7 |            | l |                         |
|   |                              | p |            | l |                         |
|   |                              | n |            | y |                         |
|   |                              | g |            | > |                         |
|   |                              | / |            |   |                         |
|   |                              | m |            | g |                         |
|   |                              | e |            | e |                         |
|   |                              | d |            | n |                         |
|   |                              | i |            | e |                         |
|   |                              | a |            | r |                         |
|   |                              | / |            | a |                         |
|   |                              | i |            | t |                         |
|   |                              | m |            | e |                         |
|   |                              | a |            | d |                         |
|   |                              | g |            | ] |                         |
|   |                              | e |            | ( |                         |
|   |                              | 1 |            | . |                         |
|   |                              | 9 |            | / |                         |
|   |                              | . |            | L |                         |
|   |                              | p |            | T |                         |
|   |                              | n |            | 7 |                         |
|   |                              | g |            | p |                         |
|   |                              | ) |            | n |                         |
|   |                              | { |            | g |                         |
|   |                              | w |            | / |                         |
|   |                              | i |            | m |                         |
|   |                              | d |            | e |                         |
|   |                              | t |            | d |                         |
|   |                              | h |            | i |                         |
|   |                              | = |            | a |                         |
|   |                              | " |            | / |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | m |                         |
|   |                              | 4 |            | a |                         |
|   |                              | 9 |            | g |                         |
|   |                              | 9 |            | e |                         |
|   |                              | 4 |            | 2 |                         |
|   |                              | 6 |            | 7 |                         |
|   |                              | 5 |            | . |                         |
|   |                              | 2 |            | p |                         |
|   |                              | 2 |            | n |                         |
|   |                              | 3 |            | g |                         |
|   |                              | 0 |            | ) |                         |
|   |                              | 9 |            | { |                         |
|   |                              | 7 |            | w |                         |
|   |                              | 1 |            | i |                         |
|   |                              | 1 |            | d |                         |
|   |                              | 2 |            | t |                         |
|   |                              | 9 |            | h |                         |
|   |                              | i |            | = |                         |
|   |                              | n |            | " |                         |
|   |                              | " |            | 1 |                         |
|   |                              | > |            | . |                         |
|   |                              |   |            | 8 |                         |
|   |                              | h |            | 9 |                         |
|   |                              | e |            | 9 |                         |
|   |                              | i |            | 3 |                         |
|   |                              | g |            | 9 |                         |
|   |                              | h |            | 9 |                         |
|   |                              | t |            | 6 |                         |
|   |                              | = |            | 0 |                         |
|   |                              | " |            | 6 |                         |
|   |                              | 0 |            | 2 |                         |
|   |                              | . |            | 9 |                         |
|   |                              | 8 |            | 9 |                         |
|   |                              | 6 |            | 2 |                         |
|   |                              | 6 |            | 1 |                         |
|   |                              | 6 |            | 2 |                         |
|   |                              | 6 |            | 7 |                         |
|   |                              | 6 |            | i |                         |
|   |                              | 6 |            | n |                         |
|   |                              | 6 |            | " |                         |
|   |                              | 6 |            | > |                         |
|   |                              | 6 |            |   |                         |
|   |                              | 6 |            | h |                         |
|   |                              | 6 |            | e |                         |
|   |                              | 6 |            | i |                         |
|   |                              | 6 |            | g |                         |
|   |                              | 6 |            | h |                         |
|   |                              | 7 |            | t |                         |
|   |                              | i |            | = |                         |
|   |                              | n |            | " |                         |
|   |                              | " |            | 0 |                         |
|   |                              | } |            | . |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 2 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 9 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| [ |                              | > |            | [ |                         |
| D |                              |   |            | " |                         |
| e |                              | [ |            | 4 |                         |
| s |                              | E |            | , |                         |
| c |                              | n |            | 5 |                         |
| r |                              | t |            | , |                         |
| i |                              | e |            | 6 |                         |
| p |                              | r |            | " |                         |
| t |                              | > |            | K |                         |
| i |                              |   |            | e |                         |
| o |                              | K |            | y |                         |
| n |                              | e |            | s |                         |
| ] |                              | y |            | ] |                         |
| { |                              | ] |            | { |                         |
| . |                              | { |            | . |                         |
| u |                              | . |            | u |                         |
| n |                              | u |            | n |                         |
| d |                              | n |            | d |                         |
| e |                              | d |            | e |                         |
| r |                              | e |            | r |                         |
| l |                              | r |            | l |                         |
| i |                              | l |            | i |                         |
| n |                              | i |            | n |                         |
| e |                              | n |            | e |                         |
| } |                              | e |            | } |                         |
|   |                              | } |            |   |                         |
+---+------------------------------+---+------------+---+-------------------------+
| 1 |                              | > |            | > |                         |
| 0 |                              |   |            |   |                         |
| 5 |                              | ! |            | ! |                         |
| I |                              | [ |            | [ |                         |
| t |                              | A |            | A |                         |
| a |                              | > |            | > |                         |
| l |                              |   |            |   |                         |
| y |                              | b |            | w |                         |
|   |                              | l |            | h |                         |
|   |                              | a |            | i |                         |
|   |                              | c |            | t |                         |
|   |                              | k |            | e |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | a |            | s |                         |
|   |                              | n |            | q |                         |
|   |                              | d |            | u |                         |
|   |                              | > |            | a |                         |
|   |                              |   |            | r |                         |
|   |                              | w |            | e |                         |
|   |                              | h |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | t |            | w |                         |
|   |                              | e |            | i |                         |
|   |                              | > |            | t |                         |
|   |                              |   |            | h |                         |
|   |                              | d |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | a |            | b |                         |
|   |                              | g |            | l |                         |
|   |                              | r |            | a |                         |
|   |                              | a |            | c |                         |
|   |                              | m |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | D |            | t |                         |
|   |                              | e |            | e |                         |
|   |                              | s |            | x |                         |
|   |                              | c |            | t |                         |
|   |                              | r |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | p |            | D |                         |
|   |                              | t |            | e |                         |
|   |                              | i |            | s |                         |
|   |                              | o |            | c |                         |
|   |                              | n |            | r |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | p |                         |
|   |                              | a |            | t |                         |
|   |                              | u |            | i |                         |
|   |                              | t |            | o |                         |
|   |                              | o |            | n |                         |
|   |                              | m |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | t |            | a |                         |
|   |                              | i |            | u |                         |
|   |                              | c |            | t |                         |
|   |                              | a |            | o |                         |
|   |                              | l |            | m |                         |
|   |                              | l |            | a |                         |
|   |                              | y |            | t |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | c |                         |
|   |                              | g |            | a |                         |
|   |                              | e |            | l |                         |
|   |                              | n |            | l |                         |
|   |                              | e |            | y |                         |
|   |                              | r |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | t |            | g |                         |
|   |                              | e |            | e |                         |
|   |                              | d |            | n |                         |
|   |                              | ] |            | e |                         |
|   |                              | ( |            | r |                         |
|   |                              | . |            | a |                         |
|   |                              | / |            | t |                         |
|   |                              | L |            | e |                         |
|   |                              | T |            | d |                         |
|   |                              | 7 |            | ] |                         |
|   |                              | p |            | ( |                         |
|   |                              | n |            | . |                         |
|   |                              | g |            | / |                         |
|   |                              | / |            | L |                         |
|   |                              | m |            | T |                         |
|   |                              | e |            | 7 |                         |
|   |                              | d |            | p |                         |
|   |                              | i |            | n |                         |
|   |                              | a |            | g |                         |
|   |                              | / |            | / |                         |
|   |                              | i |            | m |                         |
|   |                              | m |            | e |                         |
|   |                              | a |            | d |                         |
|   |                              | g |            | i |                         |
|   |                              | e |            | a |                         |
|   |                              | 1 |            | / |                         |
|   |                              | 9 |            | i |                         |
|   |                              | . |            | m |                         |
|   |                              | p |            | a |                         |
|   |                              | n |            | g |                         |
|   |                              | g |            | e |                         |
|   |                              | ) |            | 2 |                         |
|   |                              | { |            | 8 |                         |
|   |                              | w |            | . |                         |
|   |                              | i |            | p |                         |
|   |                              | d |            | n |                         |
|   |                              | t |            | g |                         |
|   |                              | h |            | ) |                         |
|   |                              | = |            | { |                         |
|   |                              | " |            | w |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | d |                         |
|   |                              | 4 |            | t |                         |
|   |                              | 9 |            | h |                         |
|   |                              | 9 |            | = |                         |
|   |                              | 8 |            | " |                         |
|   |                              | 7 |            | 1 |                         |
|   |                              | 8 |            | . |                         |
|   |                              | 6 |            | 9 |                         |
|   |                              | 0 |            | 3 |                         |
|   |                              | 8 |            | 7 |                         |
|   |                              | 9 |            | 4 |                         |
|   |                              | 2 |            | 7 |                         |
|   |                              | 3 |            | 1 |                         |
|   |                              | 8 |            | 5 |                         |
|   |                              | 8 |            | 6 |                         |
|   |                              | 4 |            | 6 |                         |
|   |                              | 5 |            | 0 |                         |
|   |                              | i |            | 5 |                         |
|   |                              | n |            | 4 |                         |
|   |                              | " |            | 2 |                         |
|   |                              | > |            | 4 |                         |
|   |                              |   |            | 3 |                         |
|   |                              | h |            | 2 |                         |
|   |                              | e |            | i |                         |
|   |                              | i |            | n |                         |
|   |                              | g |            | " |                         |
|   |                              | h |            | > |                         |
|   |                              | t |            |   |                         |
|   |                              | = |            | h |                         |
|   |                              | " |            | e |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | g |                         |
|   |                              | 8 |            | h |                         |
|   |                              | 6 |            | t |                         |
|   |                              | 6 |            | = |                         |
|   |                              | 6 |            | " |                         |
|   |                              | 6 |            | 0 |                         |
|   |                              | 5 |            | . |                         |
|   |                              | 5 |            | 5 |                         |
|   |                              | 7 |            | 5 |                         |
|   |                              | 3 |            | 7 |                         |
|   |                              | 0 |            | 2 |                         |
|   |                              | 5 |            | 9 |                         |
|   |                              | 3 |            | 1 |                         |
|   |                              | 3 |            | 1 |                         |
|   |                              | 6 |            | 1 |                         |
|   |                              | 8 |            | 9 |                         |
|   |                              | 3 |            | 8 |                         |
|   |                              | i |            | 6 |                         |
|   |                              | n |            | 0 |                         |
|   |                              | " |            | 0 |                         |
|   |                              | } |            | 1 |                         |
|   |                              |   |            | 7 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| 1 |                              | > |            | > |                         |
| 0 |                              |   |            |   |                         |
| 5 |                              | ! |            | ! |                         |
| S |                              | [ |            | [ |                         |
| w |                              | A |            | A |                         |
| i |                              | > |            | > |                         |
| t |                              |   |            |   |                         |
| z |                              | b |            | w |                         |
| e |                              | l |            | h |                         |
| r |                              | a |            | i |                         |
| l |                              | c |            | t |                         |
| a |                              | k |            | e |                         |
| n |                              | > |            | > |                         |
| d |                              |   |            |   |                         |
| , |                              | a |            | s |                         |
| L |                              | n |            | q |                         |
| u |                              | d |            | u |                         |
| x |                              | > |            | a |                         |
| e |                              |   |            | r |                         |
| m |                              | w |            | e |                         |
| b |                              | h |            | > |                         |
| o |                              | i |            |   |                         |
| u |                              | t |            | w |                         |
| r |                              | e |            | i |                         |
| g |                              | > |            | t |                         |
|   |                              |   |            | h |                         |
|   |                              | d |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | a |            | b |                         |
|   |                              | g |            | l |                         |
|   |                              | r |            | a |                         |
|   |                              | a |            | c |                         |
|   |                              | m |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | D |            | t |                         |
|   |                              | e |            | e |                         |
|   |                              | s |            | x |                         |
|   |                              | c |            | t |                         |
|   |                              | r |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | p |            | a |                         |
|   |                              | t |            | n |                         |
|   |                              | i |            | d |                         |
|   |                              | o |            | > |                         |
|   |                              | n |            |   |                         |
|   |                              | > |            | n |                         |
|   |                              |   |            | u |                         |
|   |                              | a |            | m |                         |
|   |                              | u |            | b |                         |
|   |                              | t |            | e |                         |
|   |                              | o |            | r |                         |
|   |                              | m |            | s |                         |
|   |                              | a |            | > |                         |
|   |                              | t |            |   |                         |
|   |                              | i |            | D |                         |
|   |                              | c |            | e |                         |
|   |                              | a |            | s |                         |
|   |                              | l |            | c |                         |
|   |                              | l |            | r |                         |
|   |                              | y |            | i |                         |
|   |                              | > |            | p |                         |
|   |                              |   |            | t |                         |
|   |                              | g |            | i |                         |
|   |                              | e |            | o |                         |
|   |                              | n |            | n |                         |
|   |                              | e |            | > |                         |
|   |                              | r |            |   |                         |
|   |                              | a |            | a |                         |
|   |                              | t |            | u |                         |
|   |                              | e |            | t |                         |
|   |                              | d |            | o |                         |
|   |                              | ] |            | m |                         |
|   |                              | ( |            | a |                         |
|   |                              | . |            | t |                         |
|   |                              | / |            | i |                         |
|   |                              | L |            | c |                         |
|   |                              | T |            | a |                         |
|   |                              | 7 |            | l |                         |
|   |                              | p |            | l |                         |
|   |                              | n |            | y |                         |
|   |                              | g |            | > |                         |
|   |                              | / |            |   |                         |
|   |                              | m |            | g |                         |
|   |                              | e |            | e |                         |
|   |                              | d |            | n |                         |
|   |                              | i |            | e |                         |
|   |                              | a |            | r |                         |
|   |                              | / |            | a |                         |
|   |                              | i |            | t |                         |
|   |                              | m |            | e |                         |
|   |                              | a |            | d |                         |
|   |                              | g |            | ] |                         |
|   |                              | e |            | ( |                         |
|   |                              | 1 |            | . |                         |
|   |                              | 9 |            | / |                         |
|   |                              | . |            | L |                         |
|   |                              | p |            | T |                         |
|   |                              | n |            | 7 |                         |
|   |                              | g |            | p |                         |
|   |                              | ) |            | n |                         |
|   |                              | { |            | g |                         |
|   |                              | w |            | / |                         |
|   |                              | i |            | m |                         |
|   |                              | d |            | e |                         |
|   |                              | t |            | d |                         |
|   |                              | h |            | i |                         |
|   |                              | = |            | a |                         |
|   |                              | " |            | / |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | m |                         |
|   |                              | 4 |            | a |                         |
|   |                              | 9 |            | g |                         |
|   |                              | 9 |            | e |                         |
|   |                              | 9 |            | 2 |                         |
|   |                              | 4 |            | 9 |                         |
|   |                              | 8 |            | . |                         |
|   |                              | 6 |            | p |                         |
|   |                              | 0 |            | n |                         |
|   |                              | 0 |            | g |                         |
|   |                              | 1 |            | ) |                         |
|   |                              | 7 |            | { |                         |
|   |                              | 4 |            | w |                         |
|   |                              | 9 |            | i |                         |
|   |                              | 7 |            | d |                         |
|   |                              | 8 |            | t |                         |
|   |                              | 1 |            | h |                         |
|   |                              | i |            | = |                         |
|   |                              | n |            | " |                         |
|   |                              | " |            | 1 |                         |
|   |                              | > |            | . |                         |
|   |                              |   |            | 8 |                         |
|   |                              | h |            | 9 |                         |
|   |                              | e |            | 8 |                         |
|   |                              | i |            | 1 |                         |
|   |                              | g |            | 3 |                         |
|   |                              | h |            | 5 |                         |
|   |                              | t |            | 3 |                         |
|   |                              | = |            | 8 |                         |
|   |                              | " |            | 9 |                         |
|   |                              | 0 |            | 3 |                         |
|   |                              | . |            | 2 |                         |
|   |                              | 8 |            | 6 |                         |
|   |                              | 6 |            | 3 |                         |
|   |                              | 6 |            | 3 |                         |
|   |                              | 6 |            | 4 |                         |
|   |                              | 6 |            | 2 |                         |
|   |                              | 5 |            | i |                         |
|   |                              | 5 |            | n |                         |
|   |                              | 7 |            | " |                         |
|   |                              | 3 |            | > |                         |
|   |                              | 0 |            |   |                         |
|   |                              | 5 |            | h |                         |
|   |                              | 3 |            | e |                         |
|   |                              | 3 |            | i |                         |
|   |                              | 6 |            | g |                         |
|   |                              | 8 |            | h |                         |
|   |                              | 3 |            | t |                         |
|   |                              | i |            | = |                         |
|   |                              | n |            | " |                         |
|   |                              | " |            | 0 |                         |
|   |                              | } |            | . |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 0 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 2 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 3 |                         |
|   |                              |   |            | 5 |                         |
|   |                              |   |            | 9 |                         |
|   |                              |   |            | 6 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| 1 |                              | > |            | > |                         |
| 0 |                              |   |            |   |                         |
| 4 |                              | ! |            | ! |                         |
| E |                              | [ |            | [ |                         |
| n |                              | A |            | A |                         |
| g |                              | > |            | > |                         |
| l |                              |   |            |   |                         |
| i |                              | w |            | w |                         |
| s |                              | h |            | h |                         |
| h |                              | i |            | i |                         |
| , |                              | t |            | t |                         |
| I |                              | e |            | e |                         |
| n |                              | > |            | > |                         |
| t |                              |   |            |   |                         |
| e |                              | r |            | s |                         |
| r |                              | e |            | q |                         |
| n |                              | c |            | u |                         |
| a |                              | t |            | a |                         |
| t |                              | a |            | r |                         |
| i |                              | n |            | e |                         |
| o |                              | g |            | > |                         |
| n |                              | u |            |   |                         |
| a |                              | l |            | w |                         |
| l |                              | a |            | i |                         |
| N |                              | r |            | t |                         |
| e |                              | > |            | h |                         |
| t |                              |   |            | > |                         |
| h |                              | s |            |   |                         |
| e |                              | i |            | b |                         |
| r |                              | g |            | l |                         |
| l |                              | n |            | a |                         |
| a |                              | > |            | c |                         |
| n |                              |   |            | k |                         |
| d |                              | w |            | > |                         |
| s |                              | i |            |   |                         |
|   |                              | t |            | t |                         |
|   |                              | h |            | e |                         |
|   |                              | > |            | x |                         |
|   |                              |   |            | t |                         |
|   |                              | b |            | > |                         |
|   |                              | l |            |   |                         |
|   |                              | a |            | D |                         |
|   |                              | c |            | e |                         |
|   |                              | k |            | s |                         |
|   |                              | > |            | c |                         |
|   |                              |   |            | r |                         |
|   |                              | t |            | i |                         |
|   |                              | e |            | p |                         |
|   |                              | x |            | t |                         |
|   |                              | t |            | i |                         |
|   |                              | > |            | o |                         |
|   |                              |   |            | n |                         |
|   |                              | D |            | > |                         |
|   |                              | e |            |   |                         |
|   |                              | s |            | a |                         |
|   |                              | c |            | u |                         |
|   |                              | r |            | t |                         |
|   |                              | i |            | o |                         |
|   |                              | p |            | m |                         |
|   |                              | t |            | a |                         |
|   |                              | i |            | t |                         |
|   |                              | o |            | i |                         |
|   |                              | n |            | c |                         |
|   |                              | > |            | a |                         |
|   |                              |   |            | l |                         |
|   |                              | a |            | l |                         |
|   |                              | u |            | y |                         |
|   |                              | t |            | > |                         |
|   |                              | o |            |   |                         |
|   |                              | m |            | g |                         |
|   |                              | a |            | e |                         |
|   |                              | t |            | n |                         |
|   |                              | i |            | e |                         |
|   |                              | c |            | r |                         |
|   |                              | a |            | a |                         |
|   |                              | l |            | t |                         |
|   |                              | l |            | e |                         |
|   |                              | y |            | d |                         |
|   |                              | > |            | ] |                         |
|   |                              |   |            | ( |                         |
|   |                              | g |            | . |                         |
|   |                              | e |            | / |                         |
|   |                              | n |            | L |                         |
|   |                              | e |            | T |                         |
|   |                              | r |            | 7 |                         |
|   |                              | a |            | p |                         |
|   |                              | t |            | n |                         |
|   |                              | e |            | g |                         |
|   |                              | d |            | / |                         |
|   |                              | ] |            | m |                         |
|   |                              | ( |            | e |                         |
|   |                              | . |            | d |                         |
|   |                              | / |            | i |                         |
|   |                              | L |            | a |                         |
|   |                              | T |            | / |                         |
|   |                              | 7 |            | i |                         |
|   |                              | p |            | m |                         |
|   |                              | n |            | a |                         |
|   |                              | g |            | g |                         |
|   |                              | / |            | e |                         |
|   |                              | m |            | 3 |                         |
|   |                              | e |            | 1 |                         |
|   |                              | d |            | . |                         |
|   |                              | i |            | p |                         |
|   |                              | a |            | n |                         |
|   |                              | / |            | g |                         |
|   |                              | i |            | ) |                         |
|   |                              | m |            | { |                         |
|   |                              | a |            | w |                         |
|   |                              | g |            | i |                         |
|   |                              | e |            | d |                         |
|   |                              | 3 |            | t |                         |
|   |                              | 0 |            | h |                         |
|   |                              | . |            | = |                         |
|   |                              | p |            | " |                         |
|   |                              | n |            | 1 |                         |
|   |                              | g |            | . |                         |
|   |                              | ) |            | 8 |                         |
|   |                              | { |            | 6 |                         |
|   |                              | w |            | 0 |                         |
|   |                              | i |            | 6 |                         |
|   |                              | d |            | 9 |                         |
|   |                              | t |            | 7 |                         |
|   |                              | h |            | 7 |                         |
|   |                              | = |            | 2 |                         |
|   |                              | " |            | 5 |                         |
|   |                              | 0 |            | 2 |                         |
|   |                              | . |            | 8 |                         |
|   |                              | 9 |            | 4 |                         |
|   |                              | 3 |            | 3 |                         |
|   |                              | 1 |            | 3 |                         |
|   |                              | 9 |            | 9 |                         |
|   |                              | 9 |            | 5 |                         |
|   |                              | 2 |            | i |                         |
|   |                              | 5 |            | n |                         |
|   |                              | 6 |            | " |                         |
|   |                              | 3 |            | > |                         |
|   |                              | 4 |            |   |                         |
|   |                              | 2 |            | h |                         |
|   |                              | 9 |            | e |                         |
|   |                              | 5 |            | i |                         |
|   |                              | 7 |            | g |                         |
|   |                              | 1 |            | h |                         |
|   |                              | 3 |            | t |                         |
|   |                              | i |            | = |                         |
|   |                              | n |            | " |                         |
|   |                              | " |            | 0 |                         |
|   |                              | > |            | . |                         |
|   |                              |   |            | 5 |                         |
|   |                              | h |            | 3 |                         |
|   |                              | e |            | 4 |                         |
|   |                              | i |            | 9 |                         |
|   |                              | g |            | 9 |                         |
|   |                              | h |            | 8 |                         |
|   |                              | t |            | 9 |                         |
|   |                              | = |            | 0 |                         |
|   |                              | " |            | 6 |                         |
|   |                              | 0 |            | 3 |                         |
|   |                              | . |            | 8 |                         |
|   |                              | 4 |            | 6 |                         |
|   |                              | 7 |            | 7 |                         |
|   |                              | 2 |            | 0 |                         |
|   |                              | 4 |            | 1 |                         |
|   |                              | 9 |            | 7 |                         |
|   |                              | 8 |            | i |                         |
|   |                              | 9 |            | n |                         |
|   |                              | 0 |            | " |                         |
|   |                              | 6 |            | } |                         |
|   |                              | 3 |            |   |                         |
|   |                              | 8 |            |   |                         |
|   |                              | 6 |            |   |                         |
|   |                              | 7 |            |   |                         |
|   |                              | 0 |            |   |                         |
|   |                              | 1 |            |   |                         |
|   |                              | 6 |            |   |                         |
|   |                              | 7 |            |   |                         |
|   |                              | i |            |   |                         |
|   |                              | n |            |   |                         |
|   |                              | " |            |   |                         |
|   |                              | } |            |   |                         |
+---+------------------------------+---+------------+---+-------------------------+
| 1 |                              | > |            | > |                         |
| 0 |                              |   |            |   |                         |
| 5 |                              | ! |            | ! |                         |
| P |                              | [ |            | [ |                         |
| o |                              | A |            | A |                         |
| r |                              | > |            | > |                         |
| t |                              |   |            |   |                         |
| u |                              | b |            | w |                         |
| g |                              | l |            | h |                         |
| u |                              | a |            | i |                         |
| e |                              | c |            | t |                         |
| s |                              | k |            | e |                         |
| e |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | a |            | s |                         |
|   |                              | n |            | q |                         |
|   |                              | d |            | u |                         |
|   |                              | > |            | a |                         |
|   |                              |   |            | r |                         |
|   |                              | w |            | e |                         |
|   |                              | h |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | t |            | w |                         |
|   |                              | e |            | i |                         |
|   |                              | > |            | t |                         |
|   |                              |   |            | h |                         |
|   |                              | d |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | a |            | b |                         |
|   |                              | g |            | l |                         |
|   |                              | r |            | a |                         |
|   |                              | a |            | c |                         |
|   |                              | m |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | D |            | t |                         |
|   |                              | e |            | e |                         |
|   |                              | s |            | x |                         |
|   |                              | c |            | t |                         |
|   |                              | r |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | p |            | D |                         |
|   |                              | t |            | e |                         |
|   |                              | i |            | s |                         |
|   |                              | o |            | c |                         |
|   |                              | n |            | r |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | p |                         |
|   |                              | a |            | t |                         |
|   |                              | u |            | i |                         |
|   |                              | t |            | o |                         |
|   |                              | o |            | n |                         |
|   |                              | m |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | t |            | a |                         |
|   |                              | i |            | u |                         |
|   |                              | c |            | t |                         |
|   |                              | a |            | o |                         |
|   |                              | l |            | m |                         |
|   |                              | l |            | a |                         |
|   |                              | y |            | t |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | c |                         |
|   |                              | g |            | a |                         |
|   |                              | e |            | l |                         |
|   |                              | n |            | l |                         |
|   |                              | e |            | y |                         |
|   |                              | r |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | t |            | g |                         |
|   |                              | e |            | e |                         |
|   |                              | d |            | n |                         |
|   |                              | ] |            | e |                         |
|   |                              | ( |            | r |                         |
|   |                              | . |            | a |                         |
|   |                              | / |            | t |                         |
|   |                              | L |            | e |                         |
|   |                              | T |            | d |                         |
|   |                              | 7 |            | ] |                         |
|   |                              | p |            | ( |                         |
|   |                              | n |            | . |                         |
|   |                              | g |            | / |                         |
|   |                              | / |            | L |                         |
|   |                              | m |            | T |                         |
|   |                              | e |            | 7 |                         |
|   |                              | d |            | p |                         |
|   |                              | i |            | n |                         |
|   |                              | a |            | g |                         |
|   |                              | / |            | / |                         |
|   |                              | i |            | m |                         |
|   |                              | m |            | e |                         |
|   |                              | a |            | d |                         |
|   |                              | g |            | i |                         |
|   |                              | e |            | a |                         |
|   |                              | 1 |            | / |                         |
|   |                              | 9 |            | i |                         |
|   |                              | . |            | m |                         |
|   |                              | p |            | a |                         |
|   |                              | n |            | g |                         |
|   |                              | g |            | e |                         |
|   |                              | ) |            | 3 |                         |
|   |                              | { |            | 2 |                         |
|   |                              | w |            | . |                         |
|   |                              | i |            | p |                         |
|   |                              | d |            | n |                         |
|   |                              | t |            | g |                         |
|   |                              | h |            | ) |                         |
|   |                              | = |            | { |                         |
|   |                              | " |            | w |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | d |                         |
|   |                              | 4 |            | t |                         |
|   |                              | 9 |            | h |                         |
|   |                              | 9 |            | = |                         |
|   |                              | 6 |            | " |                         |
|   |                              | 4 |            | 1 |                         |
|   |                              | 2 |            | . |                         |
|   |                              | 3 |            | 9 |                         |
|   |                              | 8 |            | 7 |                         |
|   |                              | 8 |            | 6 |                         |
|   |                              | 4 |            | 0 |                         |
|   |                              | 5 |            | 7 |                         |
|   |                              | 1 |            | 5 |                         |
|   |                              | 4 |            | 0 |                         |
|   |                              | 4 |            | 2 |                         |
|   |                              | 3 |            | 1 |                         |
|   |                              | 5 |            | 8 |                         |
|   |                              | 4 |            | 7 |                         |
|   |                              | i |            | 2 |                         |
|   |                              | n |            | 2 |                         |
|   |                              | " |            | 6 |                         |
|   |                              | > |            | 6 |                         |
|   |                              |   |            | i |                         |
|   |                              | h |            | n |                         |
|   |                              | e |            | " |                         |
|   |                              | i |            | > |                         |
|   |                              | g |            |   |                         |
|   |                              | h |            | h |                         |
|   |                              | t |            | e |                         |
|   |                              | = |            | i |                         |
|   |                              | " |            | g |                         |
|   |                              | 0 |            | h |                         |
|   |                              | . |            | t |                         |
|   |                              | 8 |            | = |                         |
|   |                              | 6 |            | " |                         |
|   |                              | 6 |            | 0 |                         |
|   |                              | 6 |            | . |                         |
|   |                              | 6 |            | 5 |                         |
|   |                              | 5 |            | 6 |                         |
|   |                              | 5 |            | 3 |                         |
|   |                              | 7 |            | 1 |                         |
|   |                              | 3 |            | 2 |                         |
|   |                              | 0 |            | 4 |                         |
|   |                              | 5 |            | 4 |                         |
|   |                              | 3 |            | 5 |                         |
|   |                              | 3 |            | 3 |                         |
|   |                              | 6 |            | 1 |                         |
|   |                              | 8 |            | 9 |                         |
|   |                              | 3 |            | 3 |                         |
|   |                              | i |            | 3 |                         |
|   |                              | n |            | 5 |                         |
|   |                              | " |            | 0 |                         |
|   |                              | } |            | 8 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+
| 1 |                              | > |            | > |                         |
| 0 |                              |   |            |   |                         |
| 5 |                              | ! |            | ! |                         |
| S |                              | [ |            | [ |                         |
| p |                              | A |            | A |                         |
| a |                              | > |            | > |                         |
| n |                              |   |            |   |                         |
| i |                              | b |            | w |                         |
| s |                              | l |            | h |                         |
| h |                              | a |            | i |                         |
| , |                              | c |            | t |                         |
| E |                              | k |            | e |                         |
| u |                              | > |            | > |                         |
| r |                              |   |            |   |                         |
| o |                              | a |            | s |                         |
| p |                              | n |            | q |                         |
| e |                              | d |            | u |                         |
| a |                              | > |            | a |                         |
| n |                              |   |            | r |                         |
|   |                              | w |            | e |                         |
|   |                              | h |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | t |            | w |                         |
|   |                              | e |            | i |                         |
|   |                              | > |            | t |                         |
|   |                              |   |            | h |                         |
|   |                              | d |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | a |            | b |                         |
|   |                              | g |            | l |                         |
|   |                              | r |            | a |                         |
|   |                              | a |            | c |                         |
|   |                              | m |            | k |                         |
|   |                              | > |            | > |                         |
|   |                              |   |            |   |                         |
|   |                              | D |            | t |                         |
|   |                              | e |            | e |                         |
|   |                              | s |            | x |                         |
|   |                              | c |            | t |                         |
|   |                              | r |            | > |                         |
|   |                              | i |            |   |                         |
|   |                              | p |            | D |                         |
|   |                              | t |            | e |                         |
|   |                              | i |            | s |                         |
|   |                              | o |            | c |                         |
|   |                              | n |            | r |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | p |                         |
|   |                              | a |            | t |                         |
|   |                              | u |            | i |                         |
|   |                              | t |            | o |                         |
|   |                              | o |            | n |                         |
|   |                              | m |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | t |            | a |                         |
|   |                              | i |            | u |                         |
|   |                              | c |            | t |                         |
|   |                              | a |            | o |                         |
|   |                              | l |            | m |                         |
|   |                              | l |            | a |                         |
|   |                              | y |            | t |                         |
|   |                              | > |            | i |                         |
|   |                              |   |            | c |                         |
|   |                              | g |            | a |                         |
|   |                              | e |            | l |                         |
|   |                              | n |            | l |                         |
|   |                              | e |            | y |                         |
|   |                              | r |            | > |                         |
|   |                              | a |            |   |                         |
|   |                              | t |            | g |                         |
|   |                              | e |            | e |                         |
|   |                              | d |            | n |                         |
|   |                              | ] |            | e |                         |
|   |                              | ( |            | r |                         |
|   |                              | . |            | a |                         |
|   |                              | / |            | t |                         |
|   |                              | L |            | e |                         |
|   |                              | T |            | d |                         |
|   |                              | 7 |            | ] |                         |
|   |                              | p |            | ( |                         |
|   |                              | n |            | . |                         |
|   |                              | g |            | / |                         |
|   |                              | / |            | L |                         |
|   |                              | m |            | T |                         |
|   |                              | e |            | 7 |                         |
|   |                              | d |            | p |                         |
|   |                              | i |            | n |                         |
|   |                              | a |            | g |                         |
|   |                              | / |            | / |                         |
|   |                              | i |            | m |                         |
|   |                              | m |            | e |                         |
|   |                              | a |            | d |                         |
|   |                              | g |            | i |                         |
|   |                              | e |            | a |                         |
|   |                              | 1 |            | / |                         |
|   |                              | 9 |            | i |                         |
|   |                              | . |            | m |                         |
|   |                              | p |            | a |                         |
|   |                              | n |            | g |                         |
|   |                              | g |            | e |                         |
|   |                              | ) |            | 3 |                         |
|   |                              | { |            | 3 |                         |
|   |                              | w |            | . |                         |
|   |                              | i |            | p |                         |
|   |                              | d |            | n |                         |
|   |                              | t |            | g |                         |
|   |                              | h |            | ) |                         |
|   |                              | = |            | { |                         |
|   |                              | " |            | w |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | d |                         |
|   |                              | 4 |            | t |                         |
|   |                              | 8 |            | h |                         |
|   |                              | 4 |            | = |                         |
|   |                              | 3 |            | " |                         |
|   |                              | 0 |            | 1 |                         |
|   |                              | 0 |            | . |                         |
|   |                              | 0 |            | 9 |                         |
|   |                              | 8 |            | 3 |                         |
|   |                              | 7 |            | 6 |                         |
|   |                              | 4 |            | 9 |                         |
|   |                              | 8 |            | 0 |                         |
|   |                              | 9 |            | 6 |                         |
|   |                              | 0 |            | 1 |                         |
|   |                              | 6 |            | 6 |                         |
|   |                              | 3 |            | 7 |                         |
|   |                              | 9 |            | 9 |                         |
|   |                              | i |            | 7 |                         |
|   |                              | n |            | 9 |                         |
|   |                              | " |            | 0 |                         |
|   |                              | > |            | 0 |                         |
|   |                              |   |            | 2 |                         |
|   |                              | h |            | 7 |                         |
|   |                              | e |            | i |                         |
|   |                              | i |            | n |                         |
|   |                              | g |            | " |                         |
|   |                              | h |            | > |                         |
|   |                              | t |            |   |                         |
|   |                              | = |            | h |                         |
|   |                              | " |            | e |                         |
|   |                              | 0 |            | i |                         |
|   |                              | . |            | g |                         |
|   |                              | 8 |            | h |                         |
|   |                              | 3 |            | t |                         |
|   |                              | 9 |            | = |                         |
|   |                              | 5 |            | " |                         |
|   |                              | 8 |            | 0 |                         |
|   |                              | 2 |            | . |                         |
|   |                              | 2 |            | 5 |                         |
|   |                              | 3 |            | 5 |                         |
|   |                              | 9 |            | 7 |                         |
|   |                              | 7 |            | 2 |                         |
|   |                              | 2 |            | 9 |                         |
|   |                              | 0 |            | 1 |                         |
|   |                              | 0 |            | 1 |                         |
|   |                              | 3 |            | 1 |                         |
|   |                              | 5 |            | 9 |                         |
|   |                              | i |            | 8 |                         |
|   |                              | n |            | 6 |                         |
|   |                              | " |            | 0 |                         |
|   |                              | } |            | 0 |                         |
|   |                              |   |            | 1 |                         |
|   |                              |   |            | 7 |                         |
|   |                              |   |            | 4 |                         |
|   |                              |   |            | i |                         |
|   |                              |   |            | n |                         |
|   |                              |   |            | " |                         |
|   |                              |   |            | } |                         |
+---+------------------------------+---+------------+---+-------------------------+

### Software Tools -- Diagnostic, Calibration, and Troubleshooting

This section covers the software tools required to support a Surface
device through problem discovery and resolution.

### Genuine Microsoft Replacement Parts

- Genuine Microsoft replacement parts can be obtained directly from
    Microsoft on
    [Microsoft.com](https://www.microsoft.com/en-us/store/b/surface-repair-parts).

- Genuine Microsoft replacement parts are also available on the
    partner sites below:

  - [iFixit](https://www.ifixit.com/collaborations/microsoft)

### General Support

- For general Surface support, visit
    [www.support.microsoft.com](http://www.support.microsoft.com)

- To troubleshoot device feature/function problems or learn more about
    Surface Laptops visit <https://support.microsoft.com/surface> .

- If you would like to learn more about Windows, visit
    <https://support.microsoft.com/windows>

- To learn more about the accessibility features of the Surface
    Laptop, go to the online user guide at
    [aka.ms/Windows-Accessibility](https://support.microsoft.com/windows/discover-windows-accessibility-features-8b1068e6-d3b8-4ba8-b027-133dd8911df9)

### Software Tools

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

### Calibration and Authentication

Specific components require additional software calibration or
authentication after completing the installation of the component before
the part will function to full capability. The specific steps will be
called out in the pertinent repair workflows.

**Impacted Parts**

- **Display (TDM) --**

  - Pre-installation -- requires a pre-installation repair workflow,
        completed in SDT, to put the device into repair mode.

  - Post-installation -- requires a post-installation workflow,
        completed in SDT, to calibrate the display to the correct
        settings.

- **Battery** **--**

  - Pre-installation - requires a pre-installation repair workflow,
        completed in SDT, to put the device into repair mode.

  - Post-installation -- requires a post-installation authentication
        workflow, completed in SDT, to authenticate the new battery as a
        valid Microsoft part.

- **Motherboard (PCBA)** --

  - Post-installation - requires a post-installation workflow for
        Display and an authentication for Battery, completed in SDT, to
        calibrate the display to the correct settings with the new board
        and ensure the battery is detected as an authentic part.

### Hardware Troubleshooting Approach

Microsoft recommends the following approach for troubleshooting Surface
devices:

1. Update the device to the latest Operating System and Driver/Firmware
    versions using Windows Update.

**Important:** Ensuring your device is fully up to date is important for
ensuring the issue you're experiencing isn't fixed by a software
update prior to conducting a hardware repair.

2. Utilize the Surface Diagnostic Toolkit (SDT) after confirming the
    device is fully updated to confirm the hardware fault is still
    present prior to repair.

3. After the repair is completed, run the Surface Diagnostic Toolkit
    (SDT) to validate the original hardware fault is resolved.

    a.  If the issue is still being experienced, it's recommended to
        reimage the device using a Surface Recovery Image (BMR) to
        return the device to a known OS/FW state. Additional repairs
        should only be conducted if the issue persists after re-imaging
        the device.

## Component Removal and Replacement Procedures

### Prerequisite Steps

Steps outlined in this section should be conducted prior to starting any
repair on a Surface device.

- **Power off device --** Ensure the device is powered off completely
    and the battery has been fully discharged. Refer to the
    [Repair-Specific Precautions and Warnings
    section](#general-information-precautions-and-warnings) for details.
    Once discharged, the device should be disconnected from all power
    sources.

- **ESD Prevention --** Ensure ESD prevention steps and general
    guidelines are followed prior to opening the device. Refer to the
    [ESD Prevention section](#electro-static-discharge-esd-prevention)
    for details.

- **Position Device --** To prevent damage to the device, ensure the
    device is placed on a clean surface free of debris.

### Feet Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Required Tools**

- Plastic Opening Pick

- Soft ESD-Safe Mat

**Primary Components**

- Feet (Refer to the Illustrated Service Parts List)

**Additional Components (Ordered Separately)**

- N/A

**Procedure--Removal (Feet)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

![The back of a computer Description automatically
generated](//service-guides/images/image34.jpeg)

2. **Remove the Feet --** Using the Nylon Spudger, carefully pry up all
    four feet to expose the screws.

![A drawing of a person cutting a piece of paper Description
automatically generated](//service-guides/images/image35.png){width="2.6in"
height="1.2131944444444445in"}

**Procedure -- Installation (Feet)**

1. **Install the Feet -** Line up the posts on the Foot to the matching
    hole pattern on the Enclosure. Press firmly until the foot clicks
    into place. Repeat for the other 3 feet.

![A close up of a hole in a metal surface Description automatically
generated](//service-guides/images/image36.jpeg){width="2.6in"
height="1.95208552055993in"}

### Enclosure Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

- **Device Serial Number Notation --** The replacement Enclosure
    supplied for repair will not have a serial number. To ensure the
    customer has the best experience with future Microsoft support
    cases, it's recommended to create a notation of the device serial
    number and provide it to the customer upon completion of the repair.

**Required Tools**

- Plastic Opening Pick

- Soft ESD-Safe Mat

- 5IP (Torx-Plus) Driver

**Primary Components**

- Enclosure (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure--Removal (Enclosure)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure--Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure screws --** Using a 5IP (Torx-Plus) driver,
    uninstall each of the 4 screws from under the feet.

![The back of a computer Description automatically
generated](/service-guides/images/image34.jpeg){width="2.6in"
height="1.9486078302712162in"}

4. **Separate the Enclosure from the Device--Carefully insert the
    tip of a Plastic Opening Pick into the space between the Enclosure
    and the Keyboard Assembly as shown below. Move the Plastic Opening
    Pick around the perimeter of the device to create a gap. Using both
    hands, carefully lift the Enclosure off the device and place it on a
    soft ESD-Safe mat.

![A close up of a computer Description automatically
generated](/service-guides/images/image37.png){width="5.388888888888889in"
height="1.3125in"}

**Caution: Do Not** lift the Enclosure from the black plastic antenna.

**Procedure -- Installation (Enclosure)**

1. **Check for unexpected items within the Device -** Perform a through
    visual inspection of the device interior, or Enclosure if re-using,
    for any loose articles that may be present. Of specific importance
    are the magnets (identified below).

![A close up of a computer Description automatically
generated](/service-guides/images/image38.png){width="2.6in"
height="1.9291218285214349in"}

2. **Install the Enclosure -** Using both hands, carefully lower the
    top or bottom edge of the Enclosure onto the device ensuring you
    line it up against the top edge as shown below. Once aligned, lower
    the Enclosure into place on to the Device. Finally, adjust the
    position of the Enclosure so that the gaps are even on all sides,
    and none of the sides are catching when you press the Enclosure down
    flat.

![Close-up of a silver computer Description automatically
generated](/service-guides/images/image39.jpeg){width="2.6in"
height="1.5161592300962379in"}

3. **Fasten the Enclosure -** Using a 5IP (Torx-Plus) driver, install
    the 4 screws into the foot wells on the Enclosure. Each screw should
    be tightened until snug, and then turned another 45-degrees (1/8^th^
    turn) to fully fasten. Adjust the position of the Enclosure as you
    go to ensure even gaps around the perimeter.

> **Caution:** Ensure that the Enclosure is not stuck on a ledge as you
> are installing the screws. Shift the Enclosure as needed to avoid this
> condition.

4. **Install the Feet--Refer to the [Procedure -- Installation
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

### Removable Solid-State Drive Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Required Tools**

- Plastic Opening Pick

- Soft ESD-Safe Mat

- 5IP (Torx-Plus) Driver

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

**Primary Components**

- Removable Solid-State Drive (Refer to the Illustrated Service Parts
    List)

  - M1301718 Screws x 4 (Foot screws)

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure--Removal (Removable Solid-State Drive)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the tape -** Carefully peel up and completely remove the
    tape covering the Removable Solid-State Drive and the corresponding
    receptable. The gray spacer will also be removed along with the
    tape. Clean the top surfaces of the Removable Solid-State Drive and
    receptacle with IPA to remove any residual adhesive.

5. **Remove the Removable Solid-State Drive --** Using a 5IP
    (Torx-Plus) driver, remove the screw (![A number with a white
    background Description automatically
    generated](/service-guides/images/image40.png){width="0.2766765091863517in"
    height="0.1in"}) holding the Removable Solid-State Drive onto the
    Motherboard. Lift the drive out of the device and place it on a soft
    ESD-Safe mat.

![A close up of a computer chip Description automatically
generated](/service-guides/images/image41.png){width="2.6in"
height="3.3465715223097114in"}

**Procedure -- Installation (Removable Solid-State Drive)**

1. **Insert the Removable Solid-State Drive --** Carefully insert the
    connector end of the Removable Solid-State Drive into the receptable
    on the motherboard while keeping the Removable Solid-State Drive as
    close as possible to horizontal.

**CAUTION:** Ensure that the Speaker wire doesn't get caught or trapped
when fastening the Removable Solid-State Drive to the Motherboard.

![A close up of a computer chip Description automatically
generated](/service-guides/images/image42.jpeg){width="2.6in"
height="1.95208552055993in"}

2. **Install Removable Solid-State Drive screw --** Using a 5IP
    (Torx-Plus) driver, install the 1 new rSSD screw (![A number with a
    white background Description automatically
    generated](/service-guides/images/image40.png){width="0.3873468941382327in"
    height="0.14in"}) until the screw is just snug. Then turn the screw
    an additional 45-degrees (1/8^th^ turn) until screw is fully
    fastened.

> ![A close-up of a screwdriver Description automatically
> generated](/service-guides/images/image43.png){width="3.8in"
> height="2.137311898512686in"}

3. **Install Black Tape on Motherboard Receptacle --** Carefully place
    a new tape on the receptacle, making sure the cutout on the tape
    matches the shape of the raised flange on the receptacle.

![A close up of a circuit board Description automatically
generated](/service-guides/images/image44.png){width="2.6in"
height="2.520136701662292in"}

4. **Install Spacer --** Place a new spacer on top of the Black Tape,
    parallel and as close as possible to the silver flange on the
    connector receptacle. Ensure the dot on one end of the spacer is
    oriented towards the display hinge and that the spacer is centered
    lengthwise with the silver flange.

> ![A close up of a circuit board Description automatically
> generated](/service-guides/images/image45.png){width="2.6in"
> height="2.474482720909886in"}

5. **Install Enclosure -** Refer to the [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

6. **Power on device --** Carefully place the device with the screen
    side facing up. Connect the device to a power supply and open the
    Display.

7. **Image the device --** Reinstall the operating system and all
    drivers/firmware by using a USB-drive containing the latest Surface
    BMR for your model. Please see [the Software Tools -- Diagnostic,
    Calibration, and
    Troubleshooting](#software-tools-diagnostic-calibration-and-troubleshooting)
    section for links to instructions on how to get the latest image and
    install it.

8. **Run the Surface Diagnostic Toolkit (SDT) --** With Windows
    installed and sitting at the desktop, insert the USB drive
    containing SDT and launch the program. Run all diagnostics to ensure
    the device is functioning as expected before moving forward.

9. **Power off the device --** Once the SDT tests have completed, power
    down the device and close the display. Invert the device so that the
    bottom of the device is facing up.

10. **Install the Feet -** Refer to the [Procedure -- Installation
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

### Battery Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**WARNING:** Prior to handling the battery, the operator must remove all
jewelry, wear gloves and safety glasses, and have a bucket of sand
prepared in case of any battery event.

**WARNING:** In the case of a battery event, submerge the entire device
in sand. **DO NOT** attempt to pick up the device.

**Required Tools**

- Plastic Opening Pick

- Nylon Spudger

- ESD-Safe Tweezers

- Soft ESD-Safe Mat

- 5IP (Torx-Plus) Driver

- 3IP (Torx-Plus) Driver

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

- 4 Gallon Bucket

- 2.0 Gallons of Clean Sand

**Primary Components**

- Battery (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

  - M1266593 Screws x 2 (Battery FPC Bracket) ![A black text with a
        white background Description automatically
        generated](/service-guides/images/image46.png){width="0.5in"
        height="0.10371062992125984in"}

  - M1272782 Screws x 8 (Battery) ![A black and white logo
        Description automatically
        generated](/service-guides/images/image47.png){width="0.5in"
        height="9.496062992125984e-2in"}

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure -- Preparation (Battery)**

**Important:** This section is only for instances where you're
replacing the battery. If the battery is being reused, then this
section isn't required.

1. **Connect USB --** Connect USB with the Surface Diagnostic Toolkit
    (SDT) loaded to an available USB port on the device under repair.

2. **Power on device --** Connect a power supply to the device. Press
    the power button on the device to power the device on. Allow it to
    boot to the Windows Desktop before continuing.

3. **Launch SDT --** From the Windows Desktop, use Windows Explorer to
    navigate to the USB drive. Select the SDT executable (.exe) to
    launch the Surface Diagnostic Toolkit.

4. **Run Battery Repair (Setup) --** From the SDT launch screen, select
    **Repair** from the drop-down menu. Next, select **Repair Setup and
    Validation** to enter the selection screen. Run the **Battery Repair
    (Setup)** to put your device into repair mode. Follow all on-screen
    instructions and allow the device to shut down when prompted.
    Disconnect the Power Supply and remove the USB drive before
    proceeding forward.

**Procedure -- Removal (Battery)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the Removable Solid-State Drive -** Refer to the [Procedure
    -- Removal (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Remove the Battery Connector Metal Bracket --** Using a 3IP
    (Torx-Plus) driver, remove the 2 screws
    (![](/service-guides/images/image48.png){width="0.3700524934383202in"
    height="0.1in"}) securing the metal bracket to the motherboard. Lift
    the metal bracket out of the device to expose the Battery FPC.

![A close up of a device Description automatically
generated](/service-guides/images/image49.png){width="2.6in"
height="1.9701859142607174in"}

6. **Disconnect the Battery FPC -** Using a Nylon Spudger, pry the
    Battery FPC connector, starting from the side of the connector, from
    the Motherboard.

![A hand holding a black plastic device Description automatically
generated](/service-guides/images/image50.jpeg){width="3.8in"
height="2.137688101487314in"}

7. **Remove the Battery Screws -** Using a 5IP (Torx-Plus) driver,
    remove the 8 screws (![A black and white logo Description
    automatically generated](/service-guides/images/image47.png){width="0.5in"
    height="9.496062992125984e-2in"}) securing the Battery.

![A close up of a computer Description automatically
generated](/service-guides/images/image51.png){width="3.8in"
height="2.3027351268591425in"}

8. **Remove the battery from the device -** Using your hands, grab the
    battery at the four points identified below and carefully lift the
    battery out of the device. Place the battery on a clean ESD-Safe Mat
    free of any debris.

![A close up of a computer Description automatically
generated](/service-guides/images/image52.png){width="3.8in"
height="1.9439326334208225in"}

**WARNING:** Only handle the battery by the plastic frame. Bending,
twisting, or impacting the battery may damage the battery, the device,
and/or result in severe personal injury or property damage. Always use
two hands when handling the battery.

**Important:** Place the battery somewhere where the battery can't
accidentally be contacted or damaged. **DO NOT** place anything on top
of the battery.

**Important:** When disposing of the battery, ensure you're recycling
according to local laws.

**Important:** The Motherboard Module and Battery are extremely
sensitive to ESD and can be easily damaged. It is critical that you
ensure proper grounding before performing any work on these parts.

**WARNING:** In the instance of a battery event, submerge the entire
device in a 4-gallon bucket filled with 2.0 gallons of clean sand.
Ensure the entire device is submerged. **DO NOT** attempt to pick up the
device.

**Procedure -- Installation (Battery)**

1. **Pre-installation device inspection --** Check the device interior
    for any loose articles that may be present.

    a.  Check and remove any foreign objects that the magnets may have
        attracted.

    b.  Pay special attention to the magnetized areas around the edges
        of the interior.

    c.  Verify that all removed screws are accounted for and have not
        been misplaced inside the device.

    d.  Loose screws should never be stored on the magnetic areas of the
        bucket.

**Important:** Verify the battery's condition. Batteries exhibiting any
damage indicated in the Lithium-Ion Battery Inspection section must be
replaced.

2. **Insert the Battery -** Using the attached loops, carefully lower
    the battery into the new device.

**Important:** Only handle new batteries with the plastic loops that
come attached. If reusing a battery, handle by the frame as indicated in
the battery removal instructions. Bending, twisting, or impacting the
battery may damage the battery, the device, and/or result in severe
personal injury or property damage. Always use two hands when handling
the battery.

3. **Install the Battery screws -** Using a 5IP screwdriver, install
    the 8 battery frame screws (![A black and white logo Description
    automatically generated](/service-guides/images/image47.png){width="0.5in"
    height="9.496062992125984e-2in"}) until the screws are just snug,
    then tighten each by an additional 45-degrees (1/8^th^ turn).

**Important:** Don't overtighten the screws on the battery frame or
battery. If the frame is cracked, the battery must not be used.

4. **Assemble the Battery FPC and FPC Bracket -** Assemble the Battery
    FPC to the Motherboard. Using a 3IP (Torx-Plus) driver, install 2
    FPC Bracket screws
    (![](/service-guides/images/image48.png){width="0.3700524934383202in"
    height="0.1in"}) until the screws are just snug. Turn each screw an
    additional 45-degrees (1/8^th^ turn) until fully fastened.

5. **Install the Removable Solid-State Drive --** Refer to [Procedure
    -- Installation (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

6. **Install the Enclosure --** Refer to [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

**Procedure -- Finalize (Battery)**

1. **Power on Device --** Connect a Power Supply to the device and
    power it on until it reaches the Windows Desktop.

2. **Connect USB --** Connect USB with the Surface Diagnostic Toolkit
    (SDT) loaded to an available USB port on the device under repair.

3. **Launch SDT --** From the Windows Desktop, use Windows Explorer to
    navigate to the USB drive. Select the SDT executable (.exe) to
    launch the Surface Diagnostic Toolkit.

4. **Allow the Battery to charge --** With the device connected to a
    power supply, allow the battery to charge until the battery icon in
    Windows reads at least 50% remaining battery charge.

5. **Run Battery Authentication --** From the SDT launch screen, select
    **Repair** from the drop-down menu. Next, select **Repair Setup and
    Validation** to enter the selection screen. Select the **Battery
    Repair (Validation)** tool and follow the on-screen prompts until a
    successful authentication is completed.

**Important:** Battery authentication requires a stable internet
connection and the latest version of the [Surface Management
Extension](https://apps.microsoft.com/detail/9NCT159F4QVG?hl=en-US&gl=US).
If the battery validation tool fails or is not detected properly,
install the Surface Management Extension, reboot the device, and try
again with a new internet connection. If failures continue, reach out to
Microsoft Support.

6. **Run the Surface Diagnostic Toolkit (SDT) --** Run all diagnostics
    to ensure the device is functioning as expected before moving
    forward.

7. **Install Feet--Refer to [Procedure -- Installation
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

### Audio Jack Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Required Tools**

- Plastic Opening Pick

- Nylon Spudger

- ESD-Safe Tweezers

- Soft ESD-Safe Mat

- 6IP (Torx-Plus) Driver

- 5IP (Torx-Plus) Driver

- 3IP (Torx-Plus) Driver

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

**Primary Components**

- Audio Jack (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

  - M1265600 Screws x 1 (Hinge & Chassis) ![A black number six on a
        white background Description automatically
        generated](/service-guides/images/image53.png){width="0.30601924759405075in"
        height="0.1in"}

  - M1212080 Screws x 2 (Audio Jack Bridge) ![A black number on a
        white background Description automatically
        generated](/service-guides/images/image54.png){width="0.5in"
        height="9.563867016622922e-2in"}

  - M1263960 Screws x 1 (Audio Jack) ![A black text with letters
        Description automatically
        generated](/service-guides/images/image55.png){width="0.5in"
        height="8.962270341207348e-2in"}

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure -- Removal (Audio Jack)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the Removable Solid-State Drive -** Refer to the [Procedure
    -- Removal (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Remove the Audio Jack Bridge --** Using a 3IP (Torx-Plus) and 6IP
    (Torx-Plus) driver, remove the 3 screws securing the Audio Jack
    Bridge to the interior. Lift the Audio Jack Bridge out of the
    device.

![A close up of a device Description automatically
generated](/service-guides/images/image56.png){width="2.6in"
height="2.218101487314086in"}

6. **Remove the Audio Jack --**

    a.  Using a 3IP (Torx-Plus) screwdriver, remove the 1 screw securing
        the Audio Jack to the Motherboard.

![A close up of a device Description automatically
generated](/service-guides/images/image57.png){width="2.6in"
height="2.081220472440945in"}

b.  Using a Nylon Spudger, flip the latch on the Motherboard to
    disengage the lock on the Audio Jack FPC. Remove the Audio Jack FPC
    from the connector on the Motherboard.

c.  Lift the Audio Jack out of the device.

**Procedure -- Installation (Audio Jack)**

1. **Install the Audio Jack --**

    a.  Place the Audio Jack into its position on the Motherboard.

    b.  Make sure the latch on the Motherboard receptacle is in the
        vertical position.

    c.  Insert the Audio Jack FPC into the receptacle and flip the latch
        down.

    d.  Using a 3IP (Torx-Plus) driver to install a new Audio Jack screw
        (![A black text with letters Description automatically
        generated](/service-guides/images/image55.png){width="0.6in"
        height="0.10754702537182852in"}) until just snug. Then turn the
        screw an additional 45-degrees (1/8^th^ turn) until fully
        fastened.

2. **Install the Audio Jack Bridge -** Install the previously removed
    Audio Jack Bridge into its position over the Audio Jack. Using a 3IP
    (Torx-Plus) and 6IP (Torx-Plus) driver, install 3 new screws (2 x
    ![A black number on a white background Description automatically
    generated](/service-guides/images/image54.png){width="0.6in"
    height="0.11476706036745407in"}, 1 x ![A black number six on a white
    background Description automatically
    generated](/service-guides/images/image53.png){width="0.30601924759405075in"
    height="0.1in"}). All screws should be tightened until just snug,
    and then turned another 45-degrees (1/8^th^ turn) until fully
    fastened.

3. **Install the Removable Solid-State Drive --** Refer to [Procedure
    -- Installation (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

4. **Install the Enclosure --** Refer to [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

5. **Power on device --** Carefully place the device with the screen
    side facing up. Connect the device to a power supply and open the
    Display.

6. **Run the Surface Diagnostic Toolkit (SDT) --** Sitting at the
    desktop, insert the USB drive containing SDT and launch the program.
    Run all diagnostics to ensure the device is functioning as expected
    before moving forward.

7. **Power off the device --** Once the SDT tests have completed, power
    down the device and close the display. Invert the device so that the
    bottom of the device is facing up.

8. **Install the Feet -** Refer to the [Procedure -- Installation
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

### Right Speaker Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Required Tools**

- Plastic Opening Pick

- Nylon Spudger

- ESD-Safe Tweezers

- Soft ESD-Safe Mat

- 5IP (Torx-Plus) Driver

- 3IP (Torx-Plus) Driver

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

**Primary Components**

- Right Speaker (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

  - M1211914 Screws x 2 (Speaker)

  - M1167842 Tape x 1 (Right Speaker Tape)

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure -- Removal (Right Speaker)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the Removable Solid-State Drive -** Refer to the [Procedure
    -- Removal (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Remove the Speaker tape --** Remove the tape and clean the surface
    with IPA to remove any residual adhesive.

![A close up of a fan Description automatically
generated](/service-guides/images/image58.png){width="2.6in"
height="2.3083530183727032in"}

6. **Remove the Right Speaker screws --** Using a 3IP (Torx-Plus)
    driver to remove the 2 screws securing the Right Speaker (which is
    on the left side when working on the device) to the Chassis.

![A close up of a device Description automatically
generated](/service-guides/images/image59.png){width="2.6in"
height="2.8113287401574802in"}

7. **Remove the Right Speaker --** Remove the Right Speaker from the
    Chassis and de-route the cable. To remove the connector from the
    Motherboard, pull up vertically on the wireless until the connector
    comes free.

**Procedure -- Installation (Right Speaker)**

1. **Install the Right Speaker -** Place the new Right Speaker into the
    Chassis. Using a 3IP (Torx-Plus) driver, install 2 new screws. All
    screws should be installed until just snug, and then turned another
    45-degress (1/8^th^ turn) until fully fastened.

![A close up of a device Description automatically
generated](/service-guides/images/image59.png){width="2.6in"
height="2.8113287401574802in"}

2. **Route and connect the Right Speaker wire --** Route the Right
    Speaker wire as shown below. Install the speaker connector into the
    receptacle on the Motherboard by pressing vertically until a snap is
    felt.

**NOTE:** The connector will have 2 visible gold contacts if it's
oriented in the correct direction.

![A close up of a fan Description automatically
generated](/service-guides/images/image60.png){width="6.5in"
height="2.2993055555555557in"}

3. **Place new Speaker Tape -** Place a new Tape over the speaker wire
    as shown below.

![A close up of a fan Description automatically
generated](/service-guides/images/image58.png){width="2.6in"
height="2.3083530183727032in"}

4. **Install the Removable Solid-State Drive --** Refer to [Procedure
    -- Installation (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Install the Enclosure --** Refer to [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

6. **Power on device --** Carefully place the device with the screen
    side facing up. Connect the device to a power supply and open the
    Display.

7. **Run the Surface Diagnostic Toolkit (SDT) --** Sitting at the
    desktop, insert the USB drive containing SDT and launch the program.
    Run all diagnostics to ensure the device is functioning as expected
    before moving forward.

8. **Power off the device --** Once the SDT tests have completed, power
    down the device and close the display. Invert the device so that the
    bottom of the device is facing up.

9. **Install the Feet -** Refer to the [Procedure -- Installation
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

### Left Speaker Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Required Tools**

- Plastic Opening Pick

- Nylon Spudger

- ESD-Safe Tweezers

- Soft ESD-Safe Mat

- 5IP (Torx-Plus) Driver

- 3IP (Torx-Plus) Driver

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

**Primary Components**

- Right Speaker (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

  - M1211914 Screws x 2 (Speaker)

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure -- Removal (Left Speaker)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the Removable Solid-State Drive -** Refer to the [Procedure
    -- Removal (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Remove the Left Speaker Screws --** Using a 3IP (Torx-Plus),
    remove the 2 screws securing the Left Speaker, located on the Right
    side of the device when working on it, to the Chassis.

![A close up of a device Description automatically
generated](/service-guides/images/image61.png){width="2.6in"
height="2.6141054243219597in"}

6. **Remove the Left Speaker --** Remove the Left Speaker from the
    Chassis. To Remove the connector from the Motherboard, pull up
    vertically on the wires until the connector comes free.

**Procedure -- Installation (Left Speaker)**

1. **Install the Left Speaker --** Place the new Left Speaker into the
    Chassis. Using a 3IP (Torx-Plus) driver to install 2 new screws. All
    screws should be installed until just snug, and then turned another
    45-degrees (1/8^th^ turn) until fully fastened.

2. **Connect the Left Speaker --** Insert the speaker connector into
    the receptable on the Motherboard by pressing vertically until a
    snap is felt.

**NOTE:** The connector will have 2 visible gold contacts if it's
oriented in the correct direction.

![A close up of a device Description automatically
generated](/service-guides/images/image62.png){width="2.6in"
height="2.533333333333333in"}

3. **Install the Removable Solid-State Drive --** Refer to [Procedure
    -- Installation (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

4. **Install the Enclosure --** Refer to [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

5. **Power on device --** Carefully place the device with the screen
    side facing up. Connect the device to a power supply and open the
    Display.

6. **Run the Surface Diagnostic Toolkit (SDT) --** Sitting at the
    desktop, insert the USB drive containing SDT and launch the program.
    Run all diagnostics to ensure the device is functioning as expected
    before moving forward.

7. **Power off the device --** Once the SDT tests have completed, power
    down the device and close the display. Invert the device so that the
    bottom of the device is facing up.

8. **Install the Feet -** Refer to the [Procedure -- Installation
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

### Micro SD Reader Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Required Tools**

- Plastic Opening Pick

- Nylon Spudger

- ESD-Safe Tweezers

- Soft ESD-Safe Mat

- 5IP (Torx-Plus) Driver

- 3IP (Torx-Plus) Driver

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

**Primary Components**

- Micro SD (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

  - M1235998 Screws x 2 (Micro SD) ![A black number on a white
        background Description automatically
        generated](/service-guides/images/image63.png){width="0.2790048118985127in"
        height="0.1in"}

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure -- Removal (Micro SD Reader)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the Removable Solid-State Drive -** Refer to the [Procedure
    -- Removal (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Disconnect the Micro SD Reader Cable --** Using a Nylon Spudger,
    flip up the latch on the Micro SD Reader board and disconnect the
    connector.

6. **Remove the Micro SD Reader --** Using a 3IP (Torx-Plus) driver,
    remove the 2 screws holding the Micro SD Reader into the Chassis and
    lift the Micro SD Reader out of the device.

![A close up of a computer Description automatically
generated](/service-guides/images/image64.png){width="2.6in"
height="2.349842519685039in"}

**Procedure -- Installation (Micro SD Reader)**

1. **Install the Micro SD Reader --**

    a.  Carefully place the new Micro SD Reader into the device chassis.

    b.  Verify that the reader is aligned with the opening on the
        outside of the device chassis.

    c.  Using a 3IP (Torx-Plus) driver, install 2 new screws (![A black
        number on a white background Description automatically
        generated](/service-guides/images/image63.png){width="0.2790048118985127in"
        height="0.1in"}) until just snug and then turn each another
        45-degrees (1/8^th^ turn) until fully fastened.

> ![A close up of a computer Description automatically
> generated](/service-guides/images/image64.png){width="2.6in"
> height="2.349842519685039in"}

2. **Connect the Micro SD Reader Cable -** Insert the Micro SD Reader
    cable into the receptacle on the Micro SD Reader board and close the
    latch. There should be a lick if the connector is inserted
    correctly, and the latch is fully closed.

3. **Install the Removable Solid-State Drive --** Refer to [Procedure
    -- Installation (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

4. **Install the Enclosure --** Refer to [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

5. **Power on device --** Carefully place the device with the screen
    side facing up. Connect the device to a power supply and open the
    Display.

6. **Run the Surface Diagnostic Toolkit (SDT) --** Sitting at the
    desktop, insert the USB drive containing SDT and launch the program.
    Run all diagnostics to ensure the device is functioning as expected
    before moving forward.

7. **Power off the device --** Once the SDT tests have completed, power
    down the device and close the display. Invert the device so that the
    bottom of the device is facing up.

8. **Install the Feet -** Refer to the [Procedure -- Installation
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

### Display Assembly Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Required Tools**

- Plastic Opening Pick

- Nylon Spudger

- ESD-Safe Tweezers

- Soft ESD-Safe Mat

- 6IP (Torx-Plus) Driver

- 5IP (Torx-Plus) Driver

- 3IP (Torx-Plus) Driver

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

**Primary Components**

- Display Assembly (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

  - M1265600 Screws x 8 (Hinge & Chassis)

  - M1274578 Screws x 12 (Antenna)

  - M1212080 Screws x 1 (Audio Jack Bridge)

  - M1263960 Screws x 2 (Audio Jack)

  - M1235995 Screws x 1 (Motherboard)

  - M1265416 Shield x 2 (Coax Cable Lid)

  - M1271924 Shield x 1 (T3 Shield)

  - M1288973 Foam x 1 (T3 Shield Foam #1)

  - M1288974 Foam x 1 (T3 Shield Foam #2)

  - M1291196 Tape x 1 (Display Assembly FPC Tape)

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure -- Preparation (Display Assembly)**

**Important:** This section is only for instances where you're
replacing the Display. If the Display is being re-used, then this
section is not required. If Display is unusable due to damage or fault,
connect an external monitor to the device to perform these steps.

1. **Connect USB --** Connect USB with the Surface Diagnostic Toolkit
    (SDT) loaded to an available USB port on the device under repair.

2. **Power on device --** Connect a power supply to the device. Press
    the power button on the device to power the device on. Allow it to
    boot to the Windows Desktop before continuing.

3. **Launch SDT --** From the Windows Desktop, use Windows Explorer to
    navigate to the USB drive. Select the SDT executable (.exe) to
    launch the Surface Diagnostic Toolkit.

4. **Run Touch Display Setup --** From the SDT launch screen, select
    **Repair** from the drop-down menu. Next, select **Repair Setup and
    Validation** to enter the selection screen. Run the **Touch Display
    (Setup)** tool to prepare your device for Display replacement.
    Follow all on-screen instructions and allow the device to shut down
    when prompted. Disconnect the Power Supply and remove the USB drive
    before proceeding forward.

**Procedure -- Removal (Display Assembly)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the Removable Solid-State Drive -** Refer to the [Procedure
    -- Removal (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Remove the Audio Jack -** Refer to the [Procedure -- Removal
    (Audio](#audio-jack-replacement) Jack) section of this document for
    detailed instructions.

6. **Remove the Antenna --**

    a)  Using a Nylon Spudger, pry up the 2 Coax Cable Lids.

> ![A person using a stylus to fix a device Description automatically
> generated](/service-guides/images/image65.jpeg){width="2.6in"
> height="1.4626279527559054in"}![A close-up of a computer chip
> Description automatically
> generated](/service-guides/images/image66.jpeg){width="2.6in"
> height="1.4626279527559054in"}

b)  Using a Nylon Spudger, disconnect the 2 Coax Cables.

> ![A close-up of a device Description automatically
> generated](/service-guides/images/image67.jpeg){width="2.6in"
> height="1.4626290463692038in"}![A close-up of a device Description
> automatically generated](/service-guides/images/image68.jpeg){width="2.6in"
> height="1.4626290463692038in"}

c)  Using a 3IP (Torx-Plus) driver, remove the 11 screws from the
    antenna.

> ![A close up of a computer Description automatically
> generated](/service-guides/images/image69.png){width="4.8in"
> height="1.944815179352581in"}

d)  Lift the Antenna out of the Chassis.

<!-- -->

7. **Remove the T3 Shield Lid --**

    a)  Using a Nylon Spudger, pry up the T3 Shield Lid starting with
        the right edge.

> ![A black tool on a black device Description automatically generated
> with medium
> confidence](/service-guides/images/image70.jpeg){width="3.799665354330709in"
> height="1.5541666666666667in"}

**NOTE:** Remove the Motherboard screw next to the T3 Shield can give
better access for removal of the shield.

b)  Slide the Nylon Spudger under the shield moving right to left. Pause
    and shift the shield up and down as you work your way left as the
    shield will get stuck on its latches.

> ![A black object on a white surface Description automatically
> generated](/service-guides/images/image71.jpeg){width="2.5993055555555555in"
> height="0.9693121172353456in"}![A hand holding a film strip
> Description automatically
> generated](/service-guides/images/image72.jpeg){width="2.599770341207349in"
> height="0.9694444444444444in"}

**Caution:** Ensure that the shield doesn't damage the Display FPC's
during removal.

8. **Disconnect the Display Assembly FPCs -** Using a Nylon Spudger,
    pry up the connectors from the side and gently wiggle them free. If
    the connectors start giving resistance as they are being pried up,
    lightly push the edge being pried back down.

**Caution:** Don't force the connector if it starts to give resistance.
Rock the connector back in the other direction to remove.

![A hand holding a tweezers Description automatically
generated](/service-guides/images/image73.jpeg){width="2.599770341207349in"
height="1.0944444444444446in"}![A close up of a device Description
automatically generated](/service-guides/images/image74.jpeg){width="2.6in"
height="1.09in"}

9. **Reorient the Device --**

    a)  Open the Display Assembly to 90 Degrees.

    b)  Place the backside of the Display Assembly on the ESD-Safe Mat
        with the screen and keyboard facing up.

> ![](/service-guides/images/image75.jpeg){width="2.6in"
> height="2.9442793088363954in"}

10. **Remove the Left Hinge Screws -- With** one hand holding the device
    still, use a 6IP (Torx-Plus) driver to remove the 3 screws on the
    Left Hinge.

![A close up of a computer Description automatically
generated](/service-guides/images/image76.jpeg){width="2.6in"
height="3.6407983377077864in"}

11. **Remove the Right Hinge Screws -** With one hand holding the device
    still, use a 6IP (Torx-Plus) driver to remove the 4 screws on the
    Right Hinge.

12. **Remove the Display Assembly from the Device -** Carefully lift the
    Chassis from the Display Assembly. Place the Display Assembly on an
    ESD-Safe mat.

**Procedure -- Installation (Display Assembly)**

1. **Orient Display Assembly --** Place the backside of the new Display
    Assembly on the ESD mat with each of the hinges set at 90-degree
    angles.

2. **Install the new Display Assembly --** Carefully align the hinges
    into the packets on the device Enclosure.

**Important:** Ensure the Enclosure doesn't impact on the display
assembly glass.

3. **Pre-fasten the right hinge screws -** Using a 6IP (Torx-Plus)
    driver, install 4 new right side hinge screws (![A black number six
    on a white background Description automatically
    generated](/service-guides/images/image53.png){width="0.4284273840769904in"
    height="0.14in"}) and tighten until it's just snug.

4. **Pre-fasten the left hinge screws -** Using a 6IP (Torx-Plus)
    driver, install 3 new left side hinge screws (![A black number six
    on a white background Description automatically
    generated](/service-guides/images/image53.png){width="0.4284273840769904in"
    height="0.14in"}) and tighten until just snug.

5. **Check alignment --**

    a.  Close the device.

    b.  Loosen all 8 hinge screws 90 degrees (1/4^th^ turn).

    c.  Adjust the alignment until the gap between the Display Assembly
        and the Chassis is as even as possible.

> ![Close-up of a black electronic device Description automatically
> generated](/service-guides/images/image77.jpeg){width="2.6in"
> height="1.4626279527559054in"}![A close-up of a computer Description
> automatically generated](/service-guides/images/image78.jpeg){width="2.6in"
> height="1.4626290463692038in"}

d.  Tighten down 1 screw on the left hinge until snug. Adjust to the
    right side so that the Chassis surface is flush with the Display
    Assembly.

e.  Tighten down 1 screw on the right hinge. Loosen the screw that was
    tightened down on the left hinge. Adjust the left side so that the
    Chassis surface is flush with the Display Assembly.

f.  Repeat as necessary until the left and right gaps are even and the
    back surfaces are flush.

<!-- -->

6. **Tighten all hinge screws -** Tighten all 7 hinge screws until they
    are snug, and then tighten an additional 90 degrees (1/4 turn) to
    ensure they are securely fastened.

7. **Connect the Display Assembly FPCs to the Motherboard -** Attach
    the display module cables to the receptacles on the Motherboard.

8. **Place the Display Assembly FPC Tape --** Place the Display
    Assembly FPC Tape to the Display Assembly FPC as shown.

**Important:** Tape should be applied only to the Display Assembly FPC.

![A close up of a device Description automatically
generated](/service-guides/images/image79.png){width="2.6in"
height="1.5892880577427821in"}

9. **Install the T3 Shield Foams (as needed) --**

    a.  If the Display Assembly being installed has 2 FPCs, inspect the
        shield fence for foams. If the foams are not present, install
        the supplied foams as shown.

> ![A close up of a device Description automatically
> generated](/service-guides/images/image80.png){width="2.6in"
> height="1.5921150481189852in"}

b.  If the Display Assembly being installed has 4 FPCs, inspect the
    shield fence for foams. Any foams on the shield fence should be
    removed.

**Important:** New Display Assemblies will only have 2 FPCs. The
remaining 2 connections on the Motherboard will remain empty. This is by
design.

10. **Install the Motherboard screw -** Using a 3IP (Torx-Plus) driver,
    install 1 new Motherboard screw (![A black text with a white
    background Description automatically
    generated](/service-guides/images/image81.png){width="0.32757108486439196in"
    height="0.1in"}) until just snug and seated, and then turn another
    45-degrees (1/8^th^ turn) until fully fastened.

11. **Install the Antenna --**

    a.  Install the previously removed Antenna. Using a 3IP (Torx-Plus)
        driver, install 12 new screws (![A black number with a white
        background Description automatically
        generated](/service-guides/images/image82.png){width="0.3170494313210849in"
        height="0.1in"}). All screws should be installed until just
        snug, and then turned another 45-degrees (1/8^th^ turn) until
        fully fastened.

> ![A close up of a computer Description automatically
> generated](/service-guides/images/image69.png){width="4.8in"
> height="1.944815179352581in"}

b.  Connect the 2 Coax Cables to the Motherboard by aligning each with
    the socket, and pressing down until a click is felt.

c.  Install 2 new Coax Cable Lids to the Motherboard over the Coax
    Cables. Align and press into place until a click is felt.

> ![A close-up of a device Description automatically
> generated](/service-guides/images/image83.jpeg){width="2.6in"
> height="1.2420997375328084in"}

12. **Install the Audio Jack --** Refer to [Procedure -- Installation
    (Audio Jack)](#audio-jack-replacement) section of this document for
    detailed instructions.

13. **Install the Removable Solid-State Drive --** Refer to [Procedure
    -- Installation (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

14. **Install the Enclosure --** Refer to [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

15. **Power on device --** Carefully place the device with the screen
    side facing up. Connect the device to a power supply and open the
    Display.

**Procedure -- Finalize (Display Assembly)**

**Important:** This section is only for instances where you're
replacing the Display. If the Display is being re-used, then this
section is not required. If Display is unusable due to damage or fault,
connect an external monitor to the device to perform these steps.

1. **Connect USB --** Connect USB with the Surface Diagnostic Toolkit
    (SDT) loaded to an available USB port on the device under repair.

2. **Launch SDT --** From the Windows Desktop, use Windows Explorer to
    navigate to the USB drive. Select the SDT executable (.exe) to
    launch the Surface Diagnostic Toolkit.

3. **Run Touch Display Calibration --** From the SDT launch screen,
    select **Repair** from the drop-down menu. Next, select **Repair
    Setup and Validation** to enter the selection screen. Run the
    **Touch Display (Calibration)** tool to calibrate your new Display.
    Follow all on-screen instructions and allow the device to restart
    when prompted.

**Important:** If the calibration fails, reboot the device, and attempt
again. If the failure continues, then the Display may be faulty and
require replacement.

4. **Launch SDT --** Once the device has rebooted and is at the Windows
    Desktop, use Windows Explorer to navigate to the USB drive. Select
    the SDT executable (.exe) to launch the Surface Diagnostic Toolkit.

5. **Run the Surface Diagnostic Toolkit (SDT) --** Run all diagnostics
    to ensure the device is functioning as expected before moving
    forward.

6. **Install Feet--Refer to [Procedure -- Installation
    (Feet)](#_Feet_Replacement_Process) for steps to install Feet.

### Surface Connect Replacement

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Required Tools**

- Plastic Opening Pick

- Nylon Spudger

- ESD-Safe Tweezers

- Soft ESD-Safe Mat

- 5IP (Torx-Plus) Driver

- 3IP (Torx-Plus) Driver

- Isopropyl alcohol (91% or greater)

- Cleaning swabs

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

**Primary Components**

- Surface Connect (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

  - M1277572 Screws x 2 (Surface Connect)

  - M1301902 PSA x 1 (Surface Connect & Fan)

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure -- Removal (Surface Connect)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the Removable Solid-State Drive -** Refer to the [Procedure
    -- Removal (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Disconnect the Surface Connect connector --** Using a Nylon
    Spudger, flip up the latch on the Motherboard, and disconnect the
    Surface Connect connector from the Motherboard.

![A close up of a fan Description automatically
generated](/service-guides/images/image84.png){width="2.6in"
height="1.9313888888888888in"}

6. **Remove the Surface Connect Cable -** Using a 3IP (Torx-Plus)
    driver, remove the 2 screws securing the Surface Connect port to the
    Motherboard. Lift the cable out of the device and place it on an
    ESD-Safe mat.

![A fan with a black band Description automatically generated with
medium confidence](/service-guides/images/image85.png){width="2.6in"
height="1.9841666666666666in"}

7. **Remove residual adhesive -** Gently peel up the PSA
    (pressure-sensitive adhesive) under the Surface Connect Cable (on
    the Fan) and remove. Clean up the surface with IPA and cleaning
    swabs until all residual adhesive has been removed and the surface
    is clean.

**Procedure -- Installation (Surface Connect)**

1. **Install new PSA -** Place a new piece of PSA down onto the Fan as
    shown.

![A close up of a fan Description automatically
generated](/service-guides/images/image86.png){width="2.6in" height="2.6in"}

2. **Install the Surface Connect Cable --**

    a.  Insert the connector of the Surface Connect Cable into the
        receptacle on the Motherboard and close the latch to secure it.
        There should be a click if the connector is inserted correct and
        the latch is fully closed.

    b.  Toe in the Surface Connect connector into the device chassis
        ensuring that the plastic housing is flush with the outside
        surface of the chassis. The port should be fully aligned with
        the external opening.

> ![](/service-guides/images/image87.jpeg){width="2.6in"
> height="1.2666666666666666in"}

c.  Using a 3IP (Torx-Plus) driver, install the 2 new Surface Connect
    screws until the screw is just snug and seated, and then turn each
    another 45-degrees (1/8^th^ turn) until fully fastened.

d.  Lightly press the cable into the PSA to adhere the cable to the fan.

<!-- -->

3. **Install the Removable Solid-State Drive --** Refer to [Procedure
    -- Installation (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

4. **Install the Enclosure --** Refer to [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

5. **Power on device --** Carefully place the device with the screen
    side facing up. Connect the device to a power supply and open the
    Display.

6. **Run the Surface Diagnostic Toolkit (SDT) --** Sitting at the
    desktop, insert the USB drive containing SDT and launch the program.
    Run all diagnostics to ensure the device is functioning as expected
    before moving forward.

7. **Power off the device --** Once the SDT tests have completed, power
    down the device and close the display. Invert the device so that the
    bottom of the device is facing up.

8. **Install the Feet -** Refer to the [Procedure -- Installation
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

### Motherboard Replacement Process

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Important:** If replacing both the Motherboard and the Display
Assembly -- complete the Motherboard replacement prior to performing the
Display Assembly Replacement to ensure proper part operation.

**Required Tools**

- Plastic Opening Pick

- Nylon Spudger

- ESD-Safe Tweezers

- Soft ESD-Safe Mat

- 6IP (Torx-Plus) Driver

- 5IP (Torx-Plus) Driver

- 3IP (Torx-Plus) Driver

- Isopropyl alcohol (91% or greater)

- Cleaning swabs

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

**Primary Components**

- Motherboard (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

  - M1266593 Screws x 2 (Battery FPC Bracket) ![A black text with a
        white background Description automatically
        generated](/service-guides/images/image46.png){width="0.6in"
        height="0.12445319335083115in"}

  - M1272782 Screws x 8 (Battery) ![A black and white logo
        Description automatically
        generated](/service-guides/images/image47.png){width="0.6in"
        height="0.11395341207349081in"}

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

  - M1265600 Screws x 1 (Hinge & Chassis) ![A black number six on a
        white background Description automatically
        generated](/service-guides/images/image53.png){width="0.30601924759405075in"
        height="0.1in"}

  - M1274578 Screws x 14 (Antenna) ![A black number with a white
        background Description automatically
        generated](/service-guides/images/image82.png){width="0.3170494313210849in"
        height="0.1in"}

  - M1212080 Screws x 1 (Audio Jack Bridge) ![A black number on a
        white background Description automatically
        generated](/service-guides/images/image54.png){width="0.6in"
        height="0.11476706036745407in"}

  - M1263960 Screws x 2 (Audio Jack) ![A black text with letters
        Description automatically
        generated](/service-guides/images/image55.png){width="0.6in"
        height="0.10754702537182852in"}

  - M1235995 Screws x 8 (Motherboard) ![A black text with a white
        background Description automatically
        generated](/service-guides/images/image81.png){width="0.6in"
        height="0.12844160104986876in"}

  - M1263961 Screws x 2 (Motherboard) ![A black letter with a white
        background Description automatically
        generated](/service-guides/images/image88.png){width="0.6in"
        height="0.12033683289588801in"}

  - M1277573 Screws x 1 (Motherboard) ![A black letter with a white
        background Description automatically
        generated](/service-guides/images/image89.png){width="0.6in"
        height="0.11994969378827647in"}

  - M1265416 Shield x 2 (Coax Cable Lid)

  - M1271279 Shield x 1 (T1 Shield

  - M1271924 Shield x 1 (T3 Shield)

  - M1288973 Foam x 1 (T3 Shield Foam #1)

  - M1288974 Foam x 1 (T3 Shield Foam #2)

  - M1287120 Tape x 1 (Touchpad FPC Tape)

  - M1019757 Syringe x 1 (Thermal Paste)

  - M1301902 PSA x 1 (Surface Connect & Fan)

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure -- Removal (Motherboard)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the Removable Solid-State Drive -** Refer to the [Procedure
    -- Removal (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Remove the Audio Jack -** Refer to the [Procedure -- Removal
    (Audio](#audio-jack-replacement) Jack) section of this document for
    detailed instructions.

6. **Remove the Battery --** Refer to the [Procedure -- Removal
    (Battery)](#battery-replacement) section of this document for
    detailed instructions.

7. **Remove the Antenna --**

    a.  Using a Nylon Spudger, pry up the 2 Coax Cable Lids.

> ![A person using a stylus to fix a device Description automatically
> generated](/service-guides/images/image65.jpeg){width="2.6in"
> height="1.4626279527559054in"}![A close-up of a computer chip
> Description automatically
> generated](/service-guides/images/image66.jpeg){width="2.6in"
> height="1.4626279527559054in"}

b.  Using a Nylon Spudger, disconnect the 2 Coax Cables.

> ![A close-up of a device Description automatically
> generated](/service-guides/images/image67.jpeg){width="2.6in"
> height="1.4626290463692038in"}![A close-up of a device Description
> automatically generated](/service-guides/images/image68.jpeg){width="2.6in"
> height="1.4626290463692038in"}

c.  Using a 3IP (Torx-Plus) driver, remove the 11 screws from the
    antenna.

d.  Lift the Antenna out of the Chassis.

<!-- -->

8. **Remove the T3 Shield Lid --**

    a.  Using a Nylon Spudger, pry up the T3 Shield Lid starting with
        the right edge.

> ![A black tool on a black device Description automatically generated
> with medium
> confidence](/service-guides/images/image70.jpeg){width="3.799665354330709in"
> height="1.3111111111111111in"}

**NOTE:** Remove the Motherboard screw next to the T3 Shield can give
better access for removal of the shield.

b.  Slide the Nylon Spudger under the shield moving right to left. Pause
    and shift the shield up and down as you work your way left as the
    shield will get stuck on its latches.

> ![A black object on a white surface Description automatically
> generated](/service-guides/images/image71.jpeg){width="2.599770341207349in"
> height="0.9763888888888889in"}![A hand holding a film strip
> Description automatically
> generated](/service-guides/images/image72.jpeg){width="2.599770341207349in"
> height="0.9694444444444444in"}

**Caution:** Ensure that the shield doesn't damage the Display FPC's
during removal.

9. **Disconnect the Display Assembly FPCs -** Using a Nylon Spudger,
    pry up the connectors from the side and gently wiggle them free. If
    the connectors start giving resistance as they are being pried up,
    lightly push the edge being pried back down.

**Caution:** Don't force the connector if it starts to give resistance.
Rock the connector back in the other direction to remove.

![A hand holding a tweezers Description automatically
generated](/service-guides/images/image73.jpeg){width="2.6in"
height="1.4626290463692038in"}![A close up of a device Description
automatically generated](/service-guides/images/image74.jpeg){width="2.6in"
height="1.4626290463692038in"}

10. **Remove the T1 Shield --** Using a Nylon Spudger or ESD-Safe
    Tweezers, peel up the corner of the shield. Pry up the rest of the
    shield and remove.

11. **Remove the T5 Shield -** Using a Nylon Spudger or ESD-Safe
    Tweezers, peel up the corner of the shield. Pry up the rest of the
    shield and remove.

12. **Disconnect the Surface Connect Cable --** Using a Nylon Spudger,
    flip up the latch on the Motherboard and disconnect the Surface
    Connect connector from the Motherboard.

13. **Disconnect the Microsoft SD Reader Cable --** Using a Nylon
    Spudger, flip up the latch on the Micro SD Reader board and
    disconnect the connector from the Motherboard.

14. **Remove Microsoft SD Reader Cable PSA on Fan -** Peel up the Micro
    SD Reader cable from the Fan. Peel up and remove the PSA on the fan.
    Clean the surface with IPA and cleaning swabs until all residual
    adhesive is removed.

15. **Remove the Surface Connect PSA on Fan -** Peel up the Surface
    Connect cable from the Fan. Peel up and remove the PSA on the fan.
    Clean the surface with IPA and cleaning swabs until all residual
    adhesive is removed.

16. **Disconnect the Fan FPC -** Flip the latch on the Motherboard to
    disengage the lock on the Fan FPC. Remove the Fan FPC from the
    connector on the Motherboard.

![A close up of a computer Description automatically
generated](/service-guides/images/image90.png){width="2.6in"
height="2.6668678915135606in"}

17. **Disconnect the Keyboard FPC -** Flip the latch on the Motherboard
    to disengage the lock on the Keyboard FPC. Remove the Keyboard FPC
    from the connector on the Motherboard.

![A close up of a computer circuit board Description automatically
generated](/service-guides/images/image91.png){width="2.6in"
height="3.465028433945757in"}

18. **Disconnect the Touch FPC --**

    a.  Remove the black tape covering the Touchpad FPC and the
        connector. Clean the surface with IPA and cleaning swabs to
        ensure all residual adhesive is removed.

> ![A close up of a computer Description automatically
> generated](/service-guides/images/image92.png){width="2.6in"
> height="3.454361329833771in"}

b.  Flip the latch on the Motherboard to disengage the lock on the
    Touchpad FPC. Remove the Touchpad FPC from the connector on the
    Motherboard.

<!-- -->

19. **Disconnect the Keyboard Backlight FPC -** Flip the latch on the
    Motherboard to disengage the lock on the Keyboard Backlight FPC.
    Remove the Keyboard Backlight FPC from the connector on the
    Motherboard.

![A close up of a computer circuit board Description automatically
generated](/service-guides/images/image93.png){width="2.6in" height="1.935in"}

20. **Disconnect the Left Speaker -** To remove the connector from the
    Motherboard, pull up vertically on the wires until the connector
    comes free.

21. **Disconnect the Right Speaker -** To remove the connector from the
    Motherboard, pull up vertically on the wires until the connector
    comes free.

22. **Remove the Motherboard Steel Bracket --** Using a 3IP (Torx-Plus)
    Driver, remove the 1 screw holding the Motherboard Steel Bracket to
    the Enclosure.

![A close up of a device Description automatically
generated](/service-guides/images/image94.png){width="2.944595363079615in"
height="1.3820155293088363in"}

23. **Remove the Motherboard Shields--** Using ESD-Safe Tweezers,
    carefully remove the two metal shields identified below to expose
    the Motherboard screws underneath.

![A close up of a circuit board Description automatically
generated](/service-guides/images/image95.png){width="2.6in"
height="1.194821741032371in"}

24. **Remove the Motherboard Screws -** Using a 3IP (Torx-Plus) driver,
    remove the 10 screws holding the Motherboard to the Chassis.

![A close up of a circuit board Description automatically
generated](/service-guides/images/image96.png){width="4.8in"
height="2.569744094488189in"}

25. **Remove the Motherboard --** Using both hands, carefully lift the
    Motherboard out and up, taking care to avoid pulling on the thermal
    module or any connectors.

**Procedure -- Installation (Motherboard)**

1. **Install the Micro SD Reader Cable --** Insert the Micro SD Reader
    Cable into the connector on the bottom side of the Motherboard.

2. **Install the Motherboard --**

**Important:** The Thermal Module should be installed onto the
Motherboard. Take caution during installation of the Motherboard to
avoid damage to the Thermal Module. Damage to the Thermal Module will
require replacement of the Motherboard or device.

a.  Lower the Motherboard USB-C side first into the device chassis.
    Ensure that the USB-C connectors fit in the corresponding holes in
    the Chassis.

b.  Lower the left side of the Motherboard and use your other hand to
    keep the component FPCs out of the way.

c.  Adjust the position of the Motherboard until all the hole's line up
    with the screw bosses.

d.  Using a 3IP (Torx-Plus) driver, install 8 new Motherboard screws
    (![A black text with a white background Description automatically
    generated](/service-guides/images/image81.png){width="0.6in"
    height="0.12844160104986876in"}) until just snug. Turn each screw
    another 45-degrees (1/8^th^ turn) until fully fastened.

> ![A close up of a circuit board Description automatically
> generated](/service-guides/images/image96.png){width="4.8in"
> height="2.569744094488189in"}

e.  Using a 3IP (Torx-Plus) driver, install 2 new Motherboard screws
    (![A black letter with a white background Description automatically
    generated](/service-guides/images/image88.png){width="0.6in"
    height="0.12033683289588801in"}) until just snug. Turn each screw
    another 45-degrees (1/8^th^ turn) until fully fastened.

> ![A close up of a circuit board Description automatically
> generated](/service-guides/images/image97.png){width="2.6in"
> height="2.078788276465442in"}

**Important:** Ensure that the slots next to the thermal module screws
sit over the posts in the device chassis.

3. **Assemble the T1 Shield --**

    a.  Using the provided syringe of thermal paste, apply the
        equivalent of 2 tick marks (marked on the side of the syringe)
        of thermal paste to the component marked below.

> ![A close up of a circuit board Description automatically
> generated](/service-guides/images/image98.png){width="1.7570352143482064in"
> height="2.3195636482939634in"}

b.  Using the same syringe of thermal paste, apply the equivalent of ½
    ticket mark (marked on the side of the syringe) of thermal paste to
    the component marked below.

> ![A close up of a circuit board Description automatically
> generated](/service-guides/images/image99.png){width="1.8750962379702538in"
> height="2.340398075240595in"}

c.  Assemble and install a new T1 Shield.

<!-- -->

4. **Assemble the Motherboard Steel Bracket -** Using a 3IP (Torx-Plus)
    driver, install 1 new screw (![A black letter with a white
    background Description automatically
    generated](/service-guides/images/image89.png){width="0.6in"
    height="0.11994969378827647in"}) until just snug, and then turn
    another 45-degrees (1/8^th^ turn) until fully fastened.

![A close up of a device Description automatically
generated](/service-guides/images/image94.png){width="2.944595363079615in"
height="1.3820155293088363in"}

5. **Install the Removable Solid-State Drive --** Refer to [Procedure
    -- Installation (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

6. **Connect the Fan FPC -** Ensure the latch on the Motherboard
    receptable for the Fan FPC is in a vertical position before
    inserting the Fan FPC. Flip the latch on the Motherboard down to
    secure the Fan FPC.

7. **Connect the Left Speaker wire -** Insert the speaker connector
    into the receptable on the Motherboard by pressing vertically until
    a snap is felt.

8. **Connect the Right Speaker wire -** Insert the speaker connector
    into the receptable on the Motherboard by pressing vertically until
    a snap is felt.

9. **Connect the Touchpad FPC -**

    a.  Ensure the latch on the Motherboard connector for the Touchpad
        FPC is in the vertical position before inserting the Touchpad
        FPC. Flip the latch on the Motherboard down to secure the
        Touchpad FPC.

    b.  Apply a new Touchpad FPC Tape across the FPC and the Motherboard
        connector.

> ![A close up of a computer Description automatically
> generated](/service-guides/images/image92.png){width="2.6in"
> height="3.454361329833771in"}

10. **Connect the Keyboard FPC -** Ensure the latch on the Motherboard
    connector for the Keyboard FPC is in a vertical position before
    inserting the Keyboard FPC. Flip the latch on the Motherboard down
    to secure the Keyboard FPC.

11. **Connect the Keyset Backlight FPC -** Ensure the latch on the
    Motherboard connector for the Keyset Backlight FPC is in a vertical
    position before inserting the Keyset Backlight FPC. Flip the latch
    on the Motherboard down to secure the Keyset Backlight FPC.

12. **Connect the Audio Jack FPC -** Ensure the latch on the Motherboard
    connector for the Audio Jack FPC is in the vertical position before
    inserting the Audio Jack FPC. Flip the latch on the Motherboard down
    to secure the Audio Jack FPC.

13. **Install new PSA -** Place a new piece of PSA down onto the Fan as
    shown.

![A close up of a fan Description automatically
generated](/service-guides/images/image86.png){width="2.6in" height="2.6in"}

14. **Install the Surface Connect Cable --** Insert the connector of the
    Surface Connect Cable into the receptacle on the Motherboard and
    close the latch to secure it. There should be a click if the
    connector is inserted correct and the latch is fully closed.

15. **Install the Display Assembly FPC's, T3 Shield, and Antenna -**
    Refer to the [Procedure -- Installation (Display
    Assembly)](#display-assembly-replacement) section of this document
    for detailed instructions.

16. **Install the Audio Jack -** Refer to the [Procedure -- Installation
    (Audio Jack)](#audio-jack-replacement) section of this document for
    detailed instructions.

17. **Install the Battery - Refer** to the [Procedure -- Installation
    (Battery)](#battery-replacement) section of this document for
    detailed instructions.

18. **Install the Enclosure --** Refer to [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

**Procedure -- Finalize (Motherboard)**

**Important:** If replacing both the Motherboard Module and the Display
Assembly -- complete the Motherboard Module replacement prior to
performing the Display Assembly Replacement to ensure proper part
operation.

1. **Power on Device --** Connect a Power Supply to the device and
    power it on until it reaches the Windows Desktop.

2. **Connect USB --** Connect USB with the Surface Diagnostic Toolkit
    (SDT) loaded to an available USB port on the device under repair.

3. **Launch SDT --** From the Windows Desktop, use Windows Explorer to
    navigate to the USB drive. Select the SDT executable (.exe) to
    launch the Surface Diagnostic Toolkit.

4. **Run Touch Display Calibration --** From the SDT launch screen,
    select **Repair** from the drop-down menu. Next, select **Repair
    Setup and Validation** to enter the selection screen. Run the
    **Touch Display (Calibration)** tool to calibrate your new Display.
    Follow all on-screen instructions and allow the device to restart
    when prompted.

**Important:** If the calibration fails, reboot the device, and attempt
again. If the failure continues, then the Display may be faulty and
require replacement.

5. **Allow the Battery to charge --** With the device connected to a
    power supply, allow the battery to charge until the battery icon in
    Windows reads at least 50% remaining battery charge.

6. **Launch SDT --** Once the device has rebooted and is at the Windows
    Desktop, use Windows Explorer to navigate to the USB drive. Select
    the SDT executable (.exe) to launch the Surface Diagnostic Toolkit.

7. **Run Battery Authentication --** From the SDT launch screen, select
    **Repair** from the drop-down menu. Next, select **Repair Setup and
    Validation** to enter the selection screen. Select the **Battery
    Repair (Validation)** tool to ensure the battery is detected as
    properly authenticated. If the battery reads anything other than
    authenticated, run the Validation tool in its entirety.

**Important:** Battery authentication requires a stable internet
connection and the latest version of the [Surface Management
Extension](https://apps.microsoft.com/detail/9NCT159F4QVG?hl=en-US&gl=US).
If the battery validation tool fails or is not detected properly,
install the Surface Management Extension, reboot the device, and try
again with a new internet connection. If failures continue, reach out to
Microsoft Support.

8. **Run the Surface Diagnostic Toolkit (SDT) --** Run all diagnostics
    to ensure the device is functioning as expected before moving
    forward.

9. **Install Feet--Refer to [Procedure -- Installation
    (Feet)](#_Feet_Replacement_Process) for steps to install Feet.

## Keyboard Replacement Process

**Preliminary Requirements**

**Important:** Be sure to follow all special (bolded) notes of caution
within each process section.

**Required Tools**

- Plastic Opening Pick

- Nylon Spudger

- ESD-Safe Tweezers

- Soft ESD-Safe Mat

- 6IP (Torx-Plus) Driver

- 5IP (Torx-Plus) Driver

- 3IP (Torx-Plus) Driver

- 2IP (Torx-Plus) Driver

- Isopropyl alcohol (91% or greater)

- Cleaning swabs

- Anti-Static wrist strap (1M Ohm resistance)

- USB drive loaded with the Surface Diagnostic Toolkit

**Primary Components**

- Keyboard Assembly (Refer to the Illustrated Service Parts List)

  - M1301718 Screws x 4 (Foot screws)

  - M1266593 Screws x 2 (Battery FPC Bracket) ![A black text with a
        white background Description automatically
        generated](/service-guides/images/image46.png){width="0.6in"
        height="0.12445319335083115in"}

  - M1272782 Screws x 8 (Battery) ![A black and white logo
        Description automatically
        generated](/service-guides/images/image47.png){width="0.6in"
        height="0.11395341207349081in"}

  - M1246215 Screws x 1 (Solid-State Drive) ![A number with a white
        background Description automatically
        generated](/service-guides/images/image40.png){width="0.2766765091863517in"
        height="0.1in"}

  - M1265600 Screws x 1 (Hinge & Chassis) ![A black number six on a
        white background Description automatically
        generated](/service-guides/images/image53.png){width="0.30601924759405075in"
        height="0.1in"}

  - M1274578 Screws x 14 (Antenna) ![A black number with a white
        background Description automatically
        generated](/service-guides/images/image82.png){width="0.3170483377077865in"
        height="0.1in"}

  - M1212080 Screws x 1 (Audio Jack Bridge) ![A black number on a
        white background Description automatically
        generated](/service-guides/images/image54.png){width="0.6in"
        height="0.11476706036745407in"}

  - M1263960 Screws x 2 (Audio Jack) ![A black text with letters
        Description automatically
        generated](/service-guides/images/image55.png){width="0.6in"
        height="0.10754702537182852in"}

  - M1235995 Screws x 8 (Motherboard) ![A black text with a white
        background Description automatically
        generated](/service-guides/images/image81.png){width="0.6in"
        height="0.12844160104986876in"}

  - M1263961 Screws x 2 (Motherboard) ![A black letter with a white
        background Description automatically
        generated](/service-guides/images/image88.png){width="0.6in"
        height="0.12033683289588801in"}

  - M1277573 Screws x 1 (Motherboard) ![A black letter with a white
        background Description automatically
        generated](/service-guides/images/image89.png){width="0.6in"
        height="0.11994969378827647in"}

  - M1211014 Screws x 4 (Speakers)

  - M1277572 Screws x 2 (Surface Connect)

  - M1235134 Screws x 3 (Fan)

  - M1249236 Screws x 4 (Mounting Brackets)

  - M1265416 Shield x 2 (Coax Cable Lid)

  - M1271279 Shield x 1 (T1 Shield

  - M1271924 Shield x 1 (T3 Shield)

  - M1288973 Foam x 1 (T3 Shield Foam #1)

  - M1288974 Foam x 1 (T3 Shield Foam #2)

  - M1287120 Tape x 1 (Touchpad FPC Tape)

  - M1167842 Tape x 1 (Right Speaker Tape)

  - M1019757 Syringe x 1 (Thermal Paste)

  - M1301902 PSA x 1 (Surface Connect & Fan)

**Additional Components (Ordered Separately)**

- Feet (Refer to the Illustrated Service Parts List)

**Procedure -- Removal (Keyboard Assembly)**

1. **Place Device--Carefully place the closed device Display side
    down with the Feet facing up on a soft ESD-Safe Mat.

2. **Remove the Feet--Refer to the [Procedure -- Removal
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

3. **Remove the Enclosure --** Refer to the [Procedure -- Removal
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

4. **Remove the Removable Solid-State Drive -** Refer to the [Procedure
    -- Removal (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

5. **Remove the Audio Jack -** Refer to the [Procedure -- Removal
    (Audio](#audio-jack-replacement) Jack) section of this document for
    detailed instructions.

6. **Remove the Battery --** Refer to the [Procedure -- Removal
    (Battery)](#battery-replacement) section of this document for
    detailed instructions.

7. **Remove the Left Speaker --** Refer to the [Procedure -- Removal
    (Left Speaker)](#left-speaker-replacement) section of this document
    for detailed instructions.

8. **Remove the Right Speaker -** Refer to the [Procedure -- Removal
    (Right Speaker)](#right-speaker-replacement) section of this
    document for detailed instructions.

9. **Remove the Micro SD Reader --** Refer to the [Procedure -- Removal
    (Micro SD Reader)](#micro-sd-reader-replacement) section of this
    document for detailed instructions.

10. **Remove the Display Assembly --** Refer to the [Procedure --
    Removal (Display Assembly)](#display-assembly-replacement) section
    of this document for detailed instructions.

11. **Remove the Surface Connect --** Refer to the [Procedure -- Removal
    (Surface Connect)](#surface-connect-replacement) section of this
    document for detailed instructions.

12. **Remove the Motherboard -** Refer to the [Procedure -- Removal
    (Motherboard)](#motherboard-replacement-process) section of this
    document for detailed instructions.

13. **Remove the Fan --** Using a 3IP (Torx-Plus) driver, remove the 3
    screws securing the Fan to the Keyboard Assembly. Remove the Fan
    from the device.

> ![A close up of a fan Description automatically
> generated](/service-guides/images/image100.png){width="2.6in"
> height="2.51500656167979in"}

14. **Remove the Mounting Brackets--** Using a 2IP (Torx-Plus) driver,
    remove the 2 screws holding each of the Mounting Brackets to the
    Keyboard Assembly. Remove the 2 Mounting Brackets from the device.

![A black board with white text and blue and yellow tape Description
automatically generated](/service-guides/images/image101.png){width="2.6in"
height="1.1919444444444445in"}

**Procedure -- Installation (Keyboard Assembly)**

1. **Install the Mounting Brackets --**

    a.  Place the 2 previously removed Mounting Brackets so that the
        yellow side is visible, and they are arranged as shown here.

> ![A black board with white text and blue and yellow tape Description
> automatically generated](/service-guides/images/image101.png){width="2.6in"
> height="1.1919444444444445in"}

b.  Using a 2IP (Torx-Plus) driver, install 4 new Mounting Bracket
    screws until the screws are just snug, and then turn each another
    45-degrees (1/8^th^ turn) until fully fastened.

<!-- -->

2. **Install the Motherboard -** Refer to the [Procedure --
    Installation (Motherboard)](#motherboard-replacement-process)
    section of this document for detailed instructions. Complete steps
    1-4 in that section.

3. **Install the Removable Solid-State Drive --** Refer to [Procedure
    -- Installation (Removable Solid-State
    Drive)](#removable-solid-state-drive-replacement) section of this
    document for detailed instructions.

4. **Install the Fan -**

    a.  Using a 3IP (Torx-Plus) driver, install 3 new Fan screws until
        they are just snug, and then turn each another 45-degrees
        (1/8^th^ turn) until fully fastened.

> ![A close up of a fan Description automatically
> generated](/service-guides/images/image100.png){width="2.6in"
> height="2.51500656167979in"}

b.  Ensure the latch on the Motherboard connector for the Fan is in a
    vertical position before inserting the Fan FPC. Flip the latch down
    to secure the Fan FPC.

<!-- -->

5. **Install the Left Speaker -** Refer to [Procedure -- Installation
    (Left Speaker)](#left-speaker-replacement) section of this document
    for detailed instructions.

6. **Install the Right Speaker -** Refer to [Procedure -- Installation
    (Right Speaker)](#right-speaker-replacement) section of this
    document for detailed instructions.

7. **Continue with Motherboard installation -** Refer to the [Procedure
    -- Installation (Motherboard)](#motherboard-replacement-process)
    section of this document for detailed instructions. You will start
    at Step 6.

8. **Install the Display -** Refer to the [Procedure -- Installation
    (Display)](#surface-connect-replacement) section of this document
    for detailed instructions.

9. **Install the Audio Jack -** Refer to the [Procedure -- Installation
    (Audio Jack)](#audio-jack-replacement) section of this document for
    detailed instructions.

10. **Install the Surface Connect -** Refer to the [Procedure --
    Installation (Surface Connect)](#surface-connect-replacement)
    section of this document for detailed instructions.

11. **Install the Battery -** Refer to the [Procedure -- Installation
    (Battery)](#battery-replacement) section of this document for
    detailed instructions.

12. **Install the Enclosure -** Refer to the [Procedure -- Installation
    (Enclosure)](#enclosure-replacement) section of this document for
    detailed instructions.

13. **Power on device --** Carefully place the device with the screen
    side facing up. Connect the device to a power supply and open the
    Display.

14. **Run the Surface Diagnostic Toolkit (SDT) --** Sitting at the
    desktop, insert the USB drive containing SDT and launch the program.
    Run all diagnostics to ensure the device is functioning as expected
    before moving forward.

15. **Power off the device --** Once the SDT tests have completed, power
    down the device and close the display. Invert the device so that the
    bottom of the device is facing up.

16. **Install the Feet -** Refer to the [Procedure -- Installation
    (Feet)](#feet-replacement) section of this document for detailed
    instructions.

# Environmental Compliance Requirements

All waste electrical and electronic equipment (WEEE), waste electronic
components, waste batteries, and electronic waste residuals must be
managed according to applicable laws and regulations. and H09117,
"Conformance Standards for Environmentally Sound Management of Waste
Electrical and Electronic Equipment (WEEE)" which is available at this
link: <https://www.microsoft.com/en-pk/download/details.aspx?id=11691> .
In case of questions, please contact <AskECT@microsoft.com> .

©2024 Microsoft.
