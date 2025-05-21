---
description: Provides safety instructions and related information 
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

# Repair Safety Guidelines

## General safety precautions

> [!WARNING]
> Always follow these general safety precautions when servicing a Microsoft Surface device:

- **Repairing electronic devices can be hazardous.** Opening and/or repairing any electronic device can present a risk of electric shock, fire, serious personal injury, death, damage to the device or other property, and/or other hazards. Exercise caution when undertaking the repair activities described in this Guide. The repair activities identified in this Guide should only be undertaken by technically inclined individuals with the knowledge, experience, and specialized tools required to repair Microsoft devices.

- **Use caution when working with batteries.** Improper use or handling of devices or their batteries can result in fire or explosion. Only open the enclosure on a device as outlined in this Guide.

- **Do not heat, puncture, mutilate, or dispose of devices or their batteries in fire.** Do not leave or charge devices in direct sunlight or expose devices or their batteries to temperatures outside the recommended operating range of 0°C to 60°C/32°F to 140°F for an extended period. Doing so can result in battery failure, electric shock, fire, serious personal injury, death, and/or damage to the device or other property.

- **Wear protective gear.** We recommend wearing protective eyewear and gloves when disassembling/re-assembling a device.

- **Keep your workspace clean.** Clean your work surface regularly to remove debris and abrasive particles.

- **Avoid conductive accessories.** While working on devices, avoid the use of clothing accessories such as bracelets, rings, or watches that can cause electrical shorts and/or damage the battery.

- **Organize components during disassembly.** As you remove each subassembly from the device, place the subassembly (and all accompanying screws) away from the work area to prevent damage to the device or to the subassembly.

- **Do not proceed if the battery is damaged.** If battery damage (for example, leaking, expansion, folds, or other) is discovered during device repair or if the battery is impacted or damaged during replacement, DO NOT proceed. Refer to the [Actions to take if there is a Thermal Event](#actions-to-take-in-a-thermal-event) section or contact Microsoft directly for proper device disposition.

- **Use genuine AC power supply.** Always select and use a genuine AC power supply and AC power cord for your Microsoft device. A genuine Microsoft power supply unit is provided with every device. Failure to take the following steps during device repair or component replacement can result in serious personal injury or death from electric shock or in damage to your device.

- **Use standard power outlet.** Use only AC power provided by a standard (mains) wall outlet. Do not use nonstandard power sources, such as generators or inverters, even if the voltage and frequency appear acceptable.

- **Proper disposal** Do not dispose of your old device in a household garbage can or recycling bin. Refer to the [Environmental compliance requirements](surface-environmental-compliance.md) for electronic waste management guidelines.

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

> [!WARNING]
> Before opening a device, ensure it is powered off and disconnected from its power source. Disconnect the device charger or power cord from mains power.

- For Autopilot-managed devices, refer to the [Windows Autopilot guidance](/mem/autopilot/autopilot-mbr).

- For devices with rechargeable lithium-ion batteries that power on, fully discharge the battery before beginning repair. To expedite the battery discharge process:
    - Disconnect the charger from the device.
    - Increase display brightness to the highest level.
    - Turn on wi-fi and Bluetooth.
    - Open the Camera app in Windows.
    - Play music or video files from a local drive or streaming service.

- Operate the device in this mode until the battery is fully discharged and the device powers off.

> [!WARNING]
> For Surface devices where the battery is affixed to the back cover, place the back cover with the battery in a location where it can be protected from possible punctures, impacts, crushing, or drops during the repair process. For more information, see [Battery Safety](#battery-safety).
> [!WARNING]
> During all activities check to ensure that no loose articles are on the back cover or remain inside the device before reassembling it.
> [!IMPORTANT]
> **For devices with a rSSD (removable Solid-State Drive)**: Remove the rSSD whenever the Keyboard is removed from the device (for laptops). rSSD removal disconnects the battery from all device logical components for safety purposes. Whenever the rSSD is removed, powering on the device requires that the rSSD and Keyboard are installed.
> [!IMPORTANT]
> The serial number for your device model is located on its original cover. To keep track of the device’s serial number, record it using waterproof ink on a sticker or label and apply the sticker or label to an easily accessible area on the device exterior. For serial number location, see the Device Information section in the service guide for your device. The serial number cannot be added permanently to a replacement part. Microsoft may provide a label for this use in the replacement part’s packaging.

### Personal protective equipment

- We recommend wearing protective eyewear and gloves when disassembling/re-assembling a device. 
- While working on devices, avoid the use of clothing accessories such as bracelets, rings, or watches that can cause electrical shorts.
- Before opening device, always check that an anti-static wrist strap is worn, and work area is properly grounded to ensure electrostatic discharge (ESD) safe environment.
- Check to make sure that general guidelines and ESD compliance steps are followed prior to starting activities. Refer to Prerequisite Steps section for details.
Workspace
- Clean your work surface regularly to remove debris and abrasive particles. As you remove each subassembly from the device, place the subassembly (and all accompanying screws) away from the work area to prevent damage to the device or to the subassembly.

---

## Battery safety

If your device contains a built-in, lithium-ion rechargeable battery, exercise caution when handling or replacing the battery. Battery safety is a significant concern when repairing a device.

- For optimum compatibility, performance, and product safety, we recommend using genuine Microsoft replacement parts available on [microsoft.com](https://www.microsoft.com/store/b/surface-repair-parts) or authorized partners like [iFixit](https://www.ifixit.com). Use of non-Microsoft (non-genuine), incompatible, reused, or modified batteries; improper battery installation; improper handling or storage of batteries; and/or failure to follow the instructions in this Guide could cause battery overheating, expansion, venting, leaking, or a thermal event which could result in fire, serious personal injury, death, data loss, or damage to the device or other property damage.
- Before beginning device repair, ensure your workspace is free of flammable debris or materials, has adequate ventilation, and that you have a fire suppressant device (example: fire blanket, container of sand, Class B fire extinguisher) within easy reach or you are within 20 feet of a fireproof enclosure. Fireproof enclosures should be kept free of combustible or flammable materials

> [!WARNING]
> It is recommended that you place an ESD-safe battery cover across the device to protect the battery from any physical contact or accidental damage whenever the display is removed for internal repairs. Ensure corners of cover are always aligned with the corners of the device while battery is exposed. If the battery cover is misaligned during activities in any way, re-align before continuing work.

- Use personal protective equipment (PPE) when handling damaged, venting, or hot battery packs.
- Use the following best practices when handling batteries:
    - Always fully discharge batteries by running an application such as video playback with the device unplugged. If the device does not function while unplugged, you may leave out this step.
    - Do not puncture, impact, strike, bend, or crush the battery or a device containing a battery.
    - Keep your workspace clear of debris, extra tools, and sharp objects.
    - Exercise caution when using sharp tools near the battery to avoid impacting or poking the battery.
    - Do not leave loose screws or small parts inside the device.
    - Avoid using tools that conduct electricity.
    - Do not drop or throw a lithium-ion battery.
    - Do not expose the battery to excessive heat, sunlight, or temperatures outside the battery’s normal operating range (0°C to 60°C) / (32°F to 140°F)
    - Ensure you handle, recycle, and/or dispose of used or damaged batteries in accordance with local laws and regulations. Follow [Handling Used, Damaged, or Defective Li-ion Batteries](#handling-used-damaged-or-defective-lithium-ion-batteries).
- If the device repair cannot be completed immediately and the device needs to be stored temporarily before restarting the repair
    - Select a storage location and process that follows the battery safety precautions in this Guide.
    - Avoid exposing the device to environmental conditions and objects that could damage the battery pack.
    - Reinspect the battery pack as outlined in this Guide prior to restarting repair and installing the new battery pack.

### Battery Warning Level

> [!WARNING]
> Note that the device battery bears the following warning label. Heed the information provided on the label.

:::image type="content" source="./images/Safety/battery-warning-level.png" alt-text="Battery Warning Level":::

### Lithium-Ion Battery Inspection

Upon device opening, we recommend that you visually inspect the battery for signs of damage. Factors to consider when inspecting the battery include, but are not limited to:

- Evidence of leaking or venting
- Visible signs of physical or mechanical damage, such as:
- Expansion or swelling. In expanded or swollen batteries, the soft pouch encasing the cell pulls away from the inner material and appears baggy, loose, or puffy.
- Discoloration of the battery casing.
- Odor, smell, or visible corrosion. Leaked battery electrolyte smells like nail polish remover (acetone).
- Dents along the battery cell edges or on the top surface.
- Surface scratches that expose the aluminum beneath the black coating layer on the battery.
- Loose or damaged wires.
- Known misuse or abuse.

> [!WARNING]
> Any battery exhibiting the signs listed must be replaced immediately.

### Handling Used, Damaged, or Defective Lithium-Ion Batteries

- **Do not discard lithium-ion batteries** (even undamaged ones) in household garbage or recycling bins.

> [!WARNING]
> **Do not ship damaged or defective batteries alone or inside a device.** These batteries require specialized packaging and transport procedures.

Prior to transport:

- Follow all instructions provided by your local e-waste recycling or household hazardous waste collection provider.
- Place the device or battery in individual, non-metallic inner packaging, such as a zip-to-close plastic bag, that completely encloses the device or battery.
- Surround the inner packaging with non-combustible, electrically non-conductive, absorbent cushioning material.
- Each damaged battery or device containing a damaged battery should be packed individually in its own carton and that carton should be clearly marked as containing a damaged battery.

> [!TIP]  
> Learn more from the [PHMSA Lithium Battery Recycling Safety Advisory](https://www.phmsa.dot.gov/sites/phmsa.dot.gov/files/2022-05/Final-5-16-Lithium-Battery-Recycling-Safety-Advisory.pdf).

Undamaged batteries can be taken to certified e-waste or hazardous waste collection sites. For more info, see [Microsoft recycling resources](https://www.microsoft.com/legal/compliance/recycling).

---

### Actions to take in a thermal event

A thermal event is a rapid chemical reaction within a battery that can release heat, smoke, or flames.

> [!WARNING]  
> Never use water to extinguish a battery fire.

If a thermal event occurs:

- Smother the device with clean, dry sand, a fire blanket, or a Class B fire extinguisher.
- Call local fire authorities if needed.
- Ventilate the area and wait at least two hours before touching the device.
- Dispose of the device according to local environmental guidelines. See [Environmental compliance requirements](surface-environmental-compliance.md).

---

### Report battery thermal events to Microsoft

A thermal event is a rapid chemical chain reaction that can occur inside a battery cell. During a thermal event, the energy stored inside the battery is released suddenly, resulting in heating and/or smoke and, in some instances, fire or flame. A battery thermal event can be triggered by physical damage to the battery (including during replacement/repair), improper storage, or exposure to temperatures outside of the battery’s operating range.

Act immediately if you see any of the following symptoms of a battery thermal event:

- Smoke, soot, sparks, or flame emitted by the battery or from a device containing a battery.
- The battery pouch suddenly expands in size.
- A popping or hissing noise from the battery or a device containing a battery.

---

### Stop repair and contact Microsoft

Before and during repair of any Microsoft device, watch for the following indicators of a potential problem. If you see any of these indicators, stop repairing. Visit the [Microsoft Product Safety](https://aka.ms/productsafety) page to report and obtain next steps:

- Any burned or melted components, traces, or plastic parts on the outside of the device, or which otherwise exhibits heat damage, including charring seen in charging or other ports.
- Any burned or melted components, traces, or plastic parts on the inside of the device, or which otherwise exhibits heat damage.
- Any accessories exhibiting melting or heat damage that are included with the Microsoft device such as power supplies, keyboards, mice, cables, charging connectors, etc. included with the Microsoft device.
- Any devices that exhibit a separated or opened case for reasons other than impact damage from dropping or evidence of tampering.
- Any other finding that may constitute a potential safety hazard to the user, such as sharp edges on plastics.

When contacting support, be prepared to provide:

- Model and serial number of the device or accessories
- Description of the damage
- Clear photographs of the symptoms
