# Mini Mars Rover Project

## Project Overview

The **Mini Mars Rover Project** is a multidisciplinary engineering project focused on designing, building, wiring, and programming a small robotic rover inspired by planetary exploration robots.

The project brings together students from **Mechanical Engineering, Electrical/Computer Engineering, and Computer Science** to develop one complete robotic system.

Rather than only assembling a pre-made robot, participants will learn how different parts of a robotic system are designed and integrated. The project begins with mechanical planning and prototyping before progressing into CAD, electrical design, embedded programming, sensor integration, and autonomous operation.

The rover design is inspired by the Adafruit Simple Raspberry Pi Robot:

https://learn.adafruit.com/simple-raspberry-pi-robot

---

## Project Goals

The goal of the Mini Mars Rover Project is to provide students with practical engineering experience outside of the classroom.

Students will experience a simplified engineering development cycle:

```text
Concept
   |
   v
Mechanical Design
   |
   v
Prototype
   |
   v
Electrical Design
   |
   v
Assembly
   |
   v
Programming
   |
   v
System Integration
   |
   v
Testing
   |
   v
Autonomous Rover
```

By the end of the project, students should have a better understanding of how mechanical hardware, electronics, and software interact to create a functional robotic system.

No previous robotics experience is required.

---

## Skills You Can Gain

### Mechanical Engineering

Participants can gain experience with:

- Mechanical design fundamentals
- Robotics fundamentals
- Chassis design
- Motor and wheel placement
- Weight distribution
- Component mounting
- Prototyping
- CAD / AutoCAD
- Mechanical assembly
- Design iteration
- Mechanical and electrical integration

### Electrical and Computer Engineering

Participants can gain experience with:

- Basic circuit design
- Reading and creating electrical schematics
- KiCad
- Raspberry Pi hardware
- GPIO
- DC motors
- Motor drivers
- Sensors
- Power distribution
- Voltage and current requirements
- Wiring and connectors
- Electrical assembly
- Hardware debugging
- Hardware/software integration

### Computer Science and Embedded Programming

Participants can gain experience with:

- Python and/or Embedded C
- Embedded programming fundamentals
- GPIO control
- Motor control
- Sensor interfacing
- Functions and program structure
- Hardware communication
- Sensor data processing
- Decision-making algorithms
- Basic autonomous behavior
- Software debugging

---

# What Can I Contribute?

Students do not need experience in every area of the project.

Participants can choose a team based on their interests, major, or the skills they want to develop.

## Mechanical Engineering Team

Mechanical team members may contribute to:

- Designing the rover chassis
- Building the initial rover prototype
- Selecting wheels and motors
- Determining component placement
- Creating CAD models
- Designing mounting solutions
- Improving rover stability
- Assembling mechanical components
- Testing mechanical designs
- Working with other teams to determine physical design constraints

### Example Responsibilities

```text
Chassis Design
      |
      +-- Motor Placement
      +-- Wheel Placement
      +-- Battery Placement
      +-- Electronics Mounting
      +-- Sensor Mounting
```

---

## Electrical / Computer Engineering Team

Electrical and Computer Engineering team members may contribute to:

- Selecting electrical components
- Creating the rover electrical architecture
- Designing KiCad schematics
- Connecting the Raspberry Pi
- Wiring the motor controller
- Integrating sensors
- Designing power connections
- Assembling circuits
- Testing electrical connections
- Troubleshooting hardware
- Integrating electronics with the mechanical chassis

### Example System

```text
Battery Pack
     |
     v
Motor Driver
     |
     +------> Left DC Motor
     |
     +------> Right DC Motor


USB Battery
     |
     v
Raspberry Pi
     |
     +------> Motor Driver
     |
     +------> Sensors
```

---

## Computer Science / Programming Team

Programming team members may contribute to:

- Raspberry Pi setup
- Writing Python or Embedded C
- Controlling DC motors
- Creating movement functions
- Reading sensor data
- Implementing obstacle detection
- Creating autonomous navigation logic
- Debugging software
- Testing rover behavior
- Integrating software with hardware

### Example Movement Functions

The software team may develop commands such as:

```text
move_forward()
move_backward()
turn_left()
turn_right()
stop()
read_sensor()
```

These functions can eventually be combined to create autonomous behavior.

---

# System Integration

One of the most important parts of the project is combining the work from all three teams.

```text
                 Mini Mars Rover
                       |
         +-------------+-------------+
         |             |             |
         v             v             v
    Mechanical     Electrical     Software
         |             |             |
      Chassis        Sensors       Python/C
      Motors          Power        Control
      Wheels      Motor Driver     Autonomy
         |             |             |
         +-------------+-------------+
                       |
                       v
                System Integration
                       |
                       v
                     Test
                       |
                       v
               Functional Rover
```

Students will learn that engineering teams cannot work completely independently.

For example:

- The mechanical team must provide space for electronics and sensors.
- The electrical team must understand the power requirements of the motors and computing hardware.
- The programming team must understand how the electrical components are connected and controlled.
- All teams must work together during integration and testing.

---

# Final Rover Capabilities

Depending on project progress, the final rover may be capable of:

- Forward movement
- Reverse movement
- Left and right turning
- Software-controlled motor movement
- Sensor data collection
- Obstacle detection
- Basic autonomous navigation
- Navigating a simulated Mars obstacle course

Additional capabilities may be added as the project develops.

---

# Engineering Workflow

## 1. Requirements

Determine what the rover needs to accomplish and identify the project's major mechanical, electrical, and software requirements.

## 2. Mechanical Design

Plan the chassis, motors, wheels, component placement, and physical layout.

## 3. Prototype

Build an initial non-autonomous rover platform to evaluate the mechanical design.

## 4. CAD

Create a digital representation of the mechanical system and refine component placement.

## 5. Electrical Design

Determine the required electrical components and create schematics using KiCad.

## 6. Electrical Assembly

Connect the Raspberry Pi, motor controller, motors, sensors, and power systems.

## 7. System Integration

Combine the mechanical and electrical systems into one rover.

## 8. Programming

Develop software to control motors and read sensors.

## 9. Testing

Test individual subsystems before testing the complete rover.

## 10. Autonomous Operation

Combine sensor information and motor control to allow the rover to perform basic autonomous actions.

---

# Tools and Technologies

| Area | Tools / Technologies |
| --- | --- |
| Mechanical Design | AutoCAD / CAD |
| Electrical Design | KiCad |
| Computing | Raspberry Pi |
| Motor Control | DC Motors / Motor Driver |
| Programming | Python / Embedded C |
| Electronics | GPIO, Sensors, Power Systems |
| Robotics | Motor Control, Sensors, Navigation |
| Development | Git / GitHub |
| Documentation | Markdown |

---

# How to Put This Project on a Resume

Once you have contributed to the project, it can be included in the **Projects** section of your resume.

Only list technologies and accomplishments that you personally worked with.

## General Example

**Mini Mars Rover | Multidisciplinary Robotics Project**

- Collaborated with mechanical, electrical, and software teams to design and integrate a Raspberry Pi-based robotic rover.
- Assisted with mechanical, electrical, and software integration through prototyping, assembly, and system testing.
- Developed and tested rover functionality including motor control, sensor integration, and basic autonomous behavior.

## Electrical / Computer Engineering Example

**Mini Mars Rover | Electrical/Computer Engineering**

- Designed and documented rover electrical interconnections using **KiCad**, integrating a Raspberry Pi, motor controller, DC motors, sensors, and power system.
- Integrated and tested electrical hardware including GPIO interfaces, motor control, sensor connections, and power distribution.
- Supported hardware/software integration and system-level debugging of a mobile robotic platform.

## Mechanical Engineering Example

**Mini Mars Rover | Mechanical Engineering**

- Designed and prototyped a mobile robotic chassis incorporating DC motors, wheels, batteries, sensors, and embedded electronics.
- Created CAD models to evaluate component placement, mounting, and mechanical constraints.
- Collaborated with electrical and software teams to integrate hardware while maintaining rover stability and accessibility.

## Computer Science / Software Example

**Mini Mars Rover | Embedded Software**

- Developed **Python/C** software for Raspberry Pi-based motor control and sensor acquisition.
- Implemented movement and sensor-processing functions supporting forward/reverse motion, turning, obstacle detection, and autonomous behavior.
- Debugged hardware/software interactions through iterative testing of motors, sensors, and GPIO interfaces.

---

# Resume Guidelines

Your resume should describe **what you personally contributed**, not everything the entire rover team accomplished.

For example:

### If you worked primarily on KiCad and electronics

Focus on:

- KiCad
- Circuit design
- Schematics
- GPIO
- Sensors
- Motor drivers
- Hardware integration
- Hardware testing

### If you worked primarily on programming

Focus on:

- Python
- Embedded C
- GPIO
- Sensor interfaces
- Motor control
- Autonomous logic
- Software debugging

### If you worked primarily on mechanical design

Focus on:

- CAD
- Mechanical design
- Prototyping
- Chassis design
- Component mounting
- Mechanical assembly
- System integration

---

# Who Should Join?

This project is suitable for students interested in:

- Mechanical Engineering
- Electrical Engineering
- Computer Engineering
- Computer Science
- Embedded Systems
- Robotics
- Aerospace
- Autonomous Systems
- Hardware Design
- Software Development

Beginners are welcome.

The purpose of the project is not to already know how to build a robot. The purpose is to learn how to design, build, program, integrate, and test one.

---

# Final Objective

By the end of the Mini Mars Rover Project, participants should have experience taking an engineering idea from an initial concept to a working physical system.

The final rover represents the integration of:

```text
Mechanical Design
        +
Electrical Engineering
        +
Embedded Programming
        +
System Integration
        +
Testing
        =
Functional Mini Mars Rover
```

More importantly, each participant should leave the project with a technical contribution that they can explain in an **interview, portfolio, GitHub repository, or resume**.
