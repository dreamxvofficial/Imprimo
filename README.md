# Imprimo by DreamXV

> A custom high-speed enclosed CoreXY 3D printer designed from the ground up.

## Overview

**Imprimo** is a concept for a custom 3D printer by **DreamXV**.

The goal is to design a sleek, enclosed CoreXY printer with a **256 × 256 × 256 mm build volume**, custom electronics, a touchscreen interface, and a modular design that can be used for future hardware projects.

The project is currently in the **concept and design stage**. The images in this repository represent the current design direction and ideas for the mechanical structure, electronics placement, PCB connections, and overall appearance.

---

## Why Imprimo?

I wanted to build a 3D printer that is more than just a machine for printing parts.

The idea behind Imprimo is to create a printer that I can continue using for future hardware projects, prototypes, enclosures, robotics projects, and other ideas.

Instead of buying an existing printer and modifying it, I want to understand and design the important parts of the machine myself from the frame and motion system to the electronics and controller PCB.

---

## Current Concept

The current design direction includes:

- Enclosed CoreXY architecture
- 256 × 256 × 256 mm target build volume
- Aluminium extrusion frame
- Tempered-glass enclosure
- Linear-rail motion system
- Heated build plate
- Direct-drive toolhead
- Custom main controller PCB
- Raspberry Pi-based control system
- Touchscreen interface
- Camera monitoring
- Automatic bed leveling
- Filament detection
- Input-shaping support
- AI-assisted print monitoring as a future feature

These are currently **design goals/concepts**, not claims that all of these systems have already been built.

---

# Concept Art

The following images show the current visual and engineering concepts for Imprimo.

## Overall Concept

![Imprimo Concept](Concept%20Art/Sketch.png)

The initial concept showing the overall form and design direction of the printer.

---

## Full Design & Dimensions

![Imprimo Dimensions](Concept%20Art/Small%20Measurements.png)

Conceptual measurements and proportions for the printer enclosure and overall structure.

---

## Detailed Measurements

![Imprimo Detailed Measurements](Concept%20Art/Also%20Small%20Measurements.png)

Additional concept measurements used to help plan the mechanical design.

---

## Frame & Mechanical Connections

![Frame Connections](Concept%20Art/Connections.png)

Concept showing how the aluminium extrusion frame could be connected using mechanical brackets, fasteners, and printed parts.

---

## PCB Connections

![PCB Connections](Concept%20Art/PCB%20Connections.png)

Concept showing the planned external connections between the main controller PCB and the printer's motors, heaters, fans, sensors, and other electronics.

---

## PCB Concept

![PCB Concept](Concept%20Art/PCB.png)

Early visual concept for the custom Imprimo controller PCB.

This is a **conceptual representation only** and is not the final PCB layout.

---

# Design Direction

The current design focuses on three main ideas:

### 1. Custom Hardware

The printer is intended to use a custom controller PCB rather than relying entirely on an existing printer control board.

### 2. Modular Design

The mechanical and electronics layout is being planned so that components can be accessed, replaced, and upgraded without redesigning the entire machine.

### 3. Future Use

Imprimo is intended to become a long-term tool for building other hardware projects rather than being a one-time prototype.

---

# Project Status

**Current stage: Concept / Initial Design**

Currently completed:

- Initial printer concept
- Overall design direction
- Initial dimensional concepts
- Frame connection concepts
- PCB connection concept
- Initial PCB appearance concept

The detailed CAD, PCB schematic/layout, electronics selection, firmware, assembly, and final BOM are planned as later stages of the project.

---

# Project Structure

```text
Imprimo/
│
├── Concept Art/
│   ├── Also Small Measurements.png
│   ├── Connections.png
│   ├── PCB Connections.png
│   ├── PCB.png
│   ├── Sketch.png
│   └── Small Measurements.png
│
└── README.md
