---
title: Surface Repair Safety, Compliance, and Support Instructions
description: Provides safety instructions and related information 
ms.service: surface
ms.localizationpriority: medium
author: coveminer
ms.author: chauncel
ms.topic: overview
ms.date: 03/25/2025
ms.reviewer: 
manager: frankbu
appliesto:
- Windows 10
- Windows 11
---

# Surface Repair Safety, Compliance, and Support Instructions

## General safety precautions

Always follow these general safety precautions when servicing a Microsoft Surface device:

- **Repairing electronic devices can be hazardous.** Activities might result in electric shock, fire, serious injury, death, or property damage. Only proceed if you're technically experienced and have the required tools and knowledge.
- **Use caution when working with batteries.** Mishandling batteries can lead to fire or explosion. Only open device enclosures as instructed in this guide.
- **Do not heat, puncture, crush, or burn devices or batteries.** Avoid exposing devices to direct sunlight or extreme temperatures (outside the range of 0°C to 60°C / 32°F to 140°F). Doing so can cause thermal failure or injury.
- **Wear protective gear.** We recommend using protective eyewear and gloves during disassembly and reassembly.
- **Keep your workspace clean.** Regularly remove dust, debris, and abrasives to avoid damage to components.
- **Avoid conductive accessories.** Remove watches, bracelets, and rings while working to prevent electrical shorts or battery damage.
- **Organize components during disassembly.** As you remove each subassembly, place it—and any screws—away from the immediate workspace.
- **Do not proceed if the battery is damaged.** This includes signs of leaking, swelling, or folding. See the [Thermal event guidance](#actions-to-take-in-a-thermal-event) or contact Microsoft for instructions.

> [!TIP]  
> For more safety information, visit [aka.ms/surface-safety](https://aka.ms/surface-safety) or open the **Surface app** from the Start menu by typing **Surface** in the search box.

---

## Electrostatic discharge (ESD) precautions

- Follow all general and ESD-specific safety steps in this guide before starting.
- Work on a flat, level surface covered with a soft, ESD-safe, nonmarring material.
- Always wear an anti-static wrist strap and ensure your work area is properly grounded.
- Store removed parts in ESD-safe bags and return or recycle them using the original packaging of the replacement part.

---

## Repair-specific precautions and warnings

- For Autopilot-managed devices, refer to the [Windows Autopilot guidance](https://docs.microsoft.com/mem/autopilot/autopilot-mbr).
- **Power off and unplug devices before opening.** Ensure chargers or power cords are disconnected from mains power.
- **Fully discharge the battery** before repair on devices that power on:
  - Disconnect the charger.
  - Set display brightness to maximum.
  - Turn on Wi-Fi and Bluetooth.
  - Open the Camera app.
  - Play video or music until the battery depletes and the device shuts down.
- **If the battery is attached to the back cover,** store the cover in a safe place during repair to prevent puncture or impact damage.
- **Check for loose items** before reassembling (excluding feet-only replacements).
- **Remove the rSSD** (removable solid-state drive) before removing the keyboard. This step disconnects the battery for safety.
- **Do not power on the device without the rSSD and keyboard installed.**
- **Label the serial number** before removing the original cover. Use waterproof ink and apply the label in an accessible location.

---

## Battery safety

This device contains a built-in, lithium-ion rechargeable battery. Exercise caution when handling or replacing the battery.

- **Use only genuine Microsoft replacement batteries** from [microsoft.com](https://www.microsoft.com) or authorized partners like [iFixit](https://www.ifixit.com).
- **Never reuse, modify, or use incompatible batteries.** Improper handling or installation can lead to overheating, swelling, venting, or fire.
- **Prepare your workspace before beginning repairs.**
  - Remove any flammable materials.
  - Ensure adequate ventilation.
  - Have a fire suppressant device nearby (fire blanket, sand, or Class B extinguisher) or store the device in a fireproof enclosure.

> [!NOTE]  
> Fireproof enclosures must be free of combustible or flammable materials.

> [!TIP]  
> Use an ESD-safe battery cover to protect the battery during internal repairs. Make sure it stays aligned with the corners of the device.

- **Wear personal protective equipment (PPE)** when handling damaged, hot, or venting batteries.

### Battery handling best practices

- Fully discharge the battery by playing video with the device unplugged.
- Avoid puncturing, crushing, bending, or impacting the battery.
- Keep your workspace clean and free of sharp or metallic tools.
- Never leave small parts or loose screws inside the device.
- Do not expose the battery to extreme heat or sunlight.
- Follow local laws for battery recycling or disposal.

If repair cannot be completed immediately, store the device safely:

- Choose a location that meets all battery safety guidelines.
- Protect the battery from physical and environmental hazards.
- Reinspect the battery before resuming work.

---

### Battery warning label

Batteries include warning labels that must be followed. Upon opening the device, visually inspect the battery for:

- Leaking or venting
- Physical damage or swelling
- Discoloration or corrosion
- Strong odor (leaked electrolyte smells like nail polish remover)
- Exposed aluminum from scratches
- Dented cell edges or surfaces
- Loose or damaged wires
- Evidence of abuse or mishandling

> [!WARNING]  
> Any battery showing these signs must be replaced immediately.

---

### Handling used, damaged, or defective lithium-ion batteries

- **Do not discard lithium-ion batteries** (even undamaged ones) in household trash or recycling bins.
- **Do not ship damaged or defective batteries alone or inside a device.** These require specialized packaging and transport procedures.

> [!WARNING]  
> Mishandling damaged batteries during shipping might cause serious safety hazards.
**Before transport:**

- Follow instructions from your local hazardous waste collection provider.
- Enclose the battery or device in a nonmetallic bag (such as a zip-to-close plastic bag).
- Cushion the inner packaging with absorbent, nonconductive, and noncombustible material.
- Pack each damaged battery or device in its own box and clearly mark it as containing a damaged battery.

> [!TIP]  
> Learn more from the [PHMSA Lithium Battery Recycling Safety Advisory](https://www.phmsa.dot.gov/sites/phmsa.dot.gov/files/2022-05/Final-5-16-Lithium-Battery-Recycling-Safety-Advisory.pdf).

Undamaged batteries can be taken to certified e-waste or hazardous waste collection sites. For more info, see [Microsoft recycling resources](https://www.microsoft.com/en-us/legal/compliance/recycling).

---

### Actions to take in a thermal event

A thermal event is a rapid chemical reaction within a battery that can release heat, smoke, or flames.

> [!WARNING]  
> **Never use water to extinguish a battery fire.**

If a thermal event occurs:

- Smother the device with clean, dry sand, a fire blanket, or a Class B fire extinguisher.
- Call local fire authorities if needed.
- Ventilate the area and wait at least two hours before touching the device.
- Dispose of the device according to local environmental guidelines.

---

### Report battery thermal events to Microsoft

Thermal events might be caused by physical damage, improper storage, or exposure to extreme temperatures.

Watch for these symptoms:

- Smoke, sparks, soot, or flame
- Sudden swelling of the battery
- Popping or hissing sounds

---

### Stop repair and contact Microsoft

Immediately stop repair and contact Microsoft Surface Customer Support if you observe any of the following scenarios:

- Burned or melted components or signs of heat damage (internal or external)
- Damaged accessories (power supply, keyboard, cable, etc.)
- Device enclosure separating without external force
- Any signs that could pose a safety risk (like exposed sharp edges)

When contacting support, be prepared to provide:

- Model and serial number of the device or accessories
- Description of the damage
- Clear photographs of the symptoms

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

## Environmental Compliance Requirements

All waste electrical and electronic equipment (WEEE), waste electronic
components, waste batteries, and electronic waste residuals must be
managed according to applicable laws and regulations. and H09117,
“Conformance Standards for Environmentally Sound Management of Waste
Electrical and Electronic Equipment (WEEE)” which is available at this
link: <https://www.microsoft.com/en-pk/download/details.aspx?id=11691> .
In case of questions, please contact <AskECT@microsoft.com> .

©2024 Microsoft.
