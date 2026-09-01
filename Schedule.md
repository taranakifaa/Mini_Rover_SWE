# Mini Mars Rover Project Schedule

## Project Goal

Design, build, wire, and program a small Mars-inspired robotic rover while introducing students to:

- Mechanical Engineering
- Electrical Engineering
- Computer Engineering / Embedded Systems
- Computer Science
- Robotics
- CAD and PCB/Schematic Design
- Embedded Programming

The final rover will be based on the concepts demonstrated in the Adafruit Simple Raspberry Pi Robot project.

Reference:
https://learn.adafruit.com/simple-raspberry-pi-robot

---

# Meeting 1 — Project Introduction

**Date:** TBD

## Goal

Introduce the Mini Mars Rover project and explain how the different engineering teams will work together.

## Topics

- What are we building?
- What does a Mars rover do?
- Basic robotic systems
- Project timeline
- Team responsibilities
- Required skills
- Safety and project expectations

## Project Teams

### Mechanical Engineering
Responsible for:

- Rover chassis
- Wheel placement
- Motor mounting
- Component mounting
- CAD design
- Physical assembly

### Electrical / Computer Engineering
Responsible for:

- Motors
- Motor controller
- Raspberry Pi / microcontroller
- Power system
- Sensors
- Wiring
- Schematics
- Electrical integration

### Computer Science / Programming
Responsible for:

- Rover movement
- Motor control
- Sensor data
- Embedded programming
- Autonomous behavior

## Deliverable

Students understand their team roles and the overall rover architecture.

---

# Meeting 2 — Mechanical Design & Robotics Basics

**Date:** TBD

## Goal

Teach students how to plan the physical design and functionality of a small rover.

## Topics

- Basic rover physics
- Wheels and traction
- Weight distribution
- Center of gravity
- DC motors
- Torque
- Speed
- Chassis design
- Component placement

Students will begin planning a rover that can move but is not autonomous.

## Deliverable

Initial mechanical rover design/sketch.

---

# Meeting 3 — Mechanical Prototype

**Date:** TBD

## Goal

Build the first physical prototype of the rover.

The prototype focuses on the mechanical system before adding the complete electrical system.

## Activities

- Assemble rover chassis
- Install wheels
- Install DC motors
- Install caster/support wheel
- Determine Raspberry Pi mounting location
- Determine battery mounting location
- Test wheel movement manually
- Identify mechanical problems

## Deliverable

Working mechanical rover prototype.

---

# Meeting 4 — AutoCAD / CAD Design

**Date:** TBD

## Goal

Teach students how mechanical designs can be modeled digitally before manufacturing or assembly.

## Topics

- Introduction to CAD
- Measurements and dimensions
- Chassis modeling
- Motor placement
- Wheel placement
- Mounting holes
- Electronics mounting locations

Students will create a CAD model based on the physical prototype from Meeting 3.

## Deliverable

Digital CAD model of the Mini Mars Rover.

---

# Meeting 5 — Electronics & Microcontroller Basics

**Date:** TBD

## Goal

Introduce the electrical system that will control and power the rover.

## Topics

- Raspberry Pi / microcontroller basics
- GPIO
- DC motors
- Motor drivers
- Adafruit Motor HAT
- Batteries and power
- Voltage
- Current
- Ground
- Sensors
- Capacitors
- Electrical safety

## Rover System Overview

Battery
→ Motor Driver
→ Motors

USB Battery
→ Raspberry Pi

Raspberry Pi
→ Motor Driver
→ Left / Right Motors

Sensors
→ Raspberry Pi

## Deliverable

Electrical component list and basic rover block diagram.

---

# Meeting 6 — KiCad & Schematic Design

**Date:** TBD

## Goal

Teach students how the rover's electrical components connect together before physically wiring them.

## Topics

- Introduction to KiCad
- Reading schematics
- Symbols
- Power connections
- Ground
- Motor connections
- Raspberry Pi connections
- Sensors
- Motor driver connections
- Connectors
- Capacitors and supporting components

## Activities

Create a schematic showing the rover's major electrical systems.

## Deliverable

Completed Mini Mars Rover electrical schematic.

---

# Meeting 7 — Electronic Circuit Assembly

**Date:** TBD

## Goal

Build and test the electrical system based on the schematic created in KiCad.

## Activities

- Mount Motor HAT / motor controller
- Connect DC motors
- Connect motor battery supply
- Connect Raspberry Pi power
- Connect sensors
- Verify polarity
- Check wiring against schematic
- Perform basic electrical testing

## Deliverable

Functional rover electrical system.

---

# Meeting 8 — Mechanical + Electrical Integration

**Date:** TBD

## Goal

Combine the mechanical and electrical systems into one complete rover.

## Activities

- Mount Raspberry Pi
- Mount motor controller
- Mount batteries
- Route motor wires
- Install sensors
- Secure wiring
- Check wheel clearance
- Check weight distribution
- Verify component accessibility

The prototype created during Meeting 3 can be used to determine where the electrical components should be mounted.

## Deliverable

Fully assembled Mini Mars Rover hardware.

---

# Meeting 9 — Embedded Programming

**Date:** TBD

## Goal

Teach students how software controls physical hardware.

Programming can be taught using:

- Python
- Embedded C

## Topics

- GPIO
- Variables
- Functions
- Motor control
- Direction control
- Speed control
- Delays
- Sensor inputs
- Basic debugging

## First Movement Commands

Students will program the rover to:

1. Move Forward
2. Stop
3. Move Backward
4. Turn Left
5. Turn Right

## Deliverable

Rover successfully moves using software commands.

---

# Meeting 10 — Sensor Integration

**Date:** TBD

## Goal

Teach students how a robot can sense its environment.

## Topics

- Sensor inputs
- Distance measurement
- Obstacle detection
- Reading sensor data
- Decision making
- Sensor calibration

## Activities

Program the rover to detect objects or environmental conditions using its sensors.

Example:

Sensor detects obstacle
→ Raspberry Pi processes data
→ Rover stops
→ Rover changes direction

## Deliverable

Rover responds to at least one environmental sensor.

---

# Meeting 11 — Autonomous Rover Programming

**Date:** TBD

## Goal

Combine programming, sensors, electronics, and mechanical design to create basic autonomous behavior.

## Example Autonomous Logic

START

↓
Move Forward

↓
Check Sensor

↓
Obstacle?

NO → Continue Forward

YES → Stop → Turn → Continue

## Deliverable

Rover demonstrates basic autonomous navigation.

---

# Meeting 12 — Testing, Competition & Final Demonstration

**Date:** TBD

## Goal

Test the completed Mini Mars Rover and demonstrate everything learned throughout the project.

## Testing

- Forward movement
- Reverse movement
- Left/right turning
- Motor speed
- Sensor operation
- Obstacle detection
- Battery performance
- Mechanical stability
- Autonomous navigation

## Final Challenge

Create a small "Mars Course" containing:

- Obstacles
- Turns
- Narrow paths
- Start zone
- Finish zone

Each rover must navigate through the course.

## Final Deliverable

A functional Mini Mars Rover demonstrating:

**Mechanical Design + Electronics + Embedded Programming + Autonomous Robotics**
