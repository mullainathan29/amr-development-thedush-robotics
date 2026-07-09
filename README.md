# Mobile Logistics Robot (AMR)

> Autonomous Mobile Robot (AMR) developed during an industrial internship for warehouse material transportation and logistics automation.

> **Note**
>
> This repository showcases the overall system architecture, hardware design, and development process.
>
> Due to a Non-Disclosure Agreement (NDA), the complete ROS workspace, source code, CAD files, and proprietary software cannot be published.

---

# Overview

This project involved the design, fabrication and integration of an Autonomous Mobile Robot capable of indoor logistics and material transportation.

The robot was designed as an industrial AMR platform capable of autonomous navigation using LiDAR, onboard computing, and ROS.

The work included:

- Mechanical Design
- CAD Modeling
- Hardware Selection
- Robot Fabrication
- ROS Integration
- LiDAR Integration
- Navigation Stack Setup
- Sensor Integration
- Testing and Validation

---

# Features

- Differential Drive Mobile Robot
- ROS-Based Software Architecture
- LiDAR Mapping
- Autonomous Navigation
- Obstacle Detection
- Emergency Stop System
- Battery Powered Platform
- Charging Dock Support
- Remote Monitoring
- Expandable Sensor Platform

---

# System Architecture

```text
                 +----------------------+
                 |     Operator PC      |
                 +----------+-----------+
                            |
                            |
                      ROS Communication
                            |
                            ▼
                 +----------------------+
                 |  NVIDIA Jetson Nano  |
                 +----------+-----------+
                            |
      +----------+----------+-----------+-----------+
      |          |                      |           |
      ▼          ▼                      ▼           ▼
  LiDAR      RealSense             Motor Driver    HMI
      |                               |
      +---------------+---------------+
                      |
                      ▼
            Differential Drive Robot
```

---

# Workflow

```text
Mission Request
       │
       ▼
Localization
       │
       ▼
SLAM / Mapping
       │
       ▼
Path Planning
       │
       ▼
Obstacle Detection
       │
       ▼
Motion Control
       │
       ▼
Material Transportation
```

---

# Development Process

```text
Requirements
      │
      ▼
CAD Design
      │
      ▼
Mechanical Fabrication
      │
      ▼
Electrical Integration
      │
      ▼
ROS Setup
      │
      ▼
Sensor Integration
      │
      ▼
Navigation Testing
      │
      ▼
Validation
```

---

# Hardware

| Component | Purpose |
|-----------|----------|
| NVIDIA Jetson Nano | Onboard Computer |
| YDLIDAR G2 | Environment Mapping |
| Intel RealSense Camera | Depth Perception |
| NEMA 34 Stepper Motors | Robot Drive |
| Planetary Gearbox | Torque Multiplication |
| Emergency Stop | Safety |
| HMI | User Interface |
| Lithium Battery | Power Supply |

---

# Software Stack

- ROS Noetic
- RViz
- Ubuntu
- PTC Creo
- SolidWorks
- Fusion 360

---

# Navigation Pipeline

```text
LiDAR
   │
   ▼
Laser Scan
   │
   ▼
SLAM
   │
   ▼
Generated Map
   │
   ▼
Localization
   │
   ▼
Planner
   │
   ▼
Velocity Commands
   │
   ▼
Motor Controller
```

---

# Mechanical Design

The robot uses a differential drive configuration consisting of:

- Two powered drive wheels
- Supporting caster wheels
- Polyurethane traction wheels
- Steel chassis
- Modular electronics enclosure

---

# Safety Features

- Emergency Stop
- Obstacle Detection
- Differential Drive Control
- Collision Prevention
- Industrial Battery System

---

# Repository Contents

```
docs/
    System architecture
    Images
    CAD renders
    Screenshots

images/
    Robot photos
    RViz screenshots
    LiDAR visualization
```

---

# Project Gallery

Replace the placeholders below with project images.

## Final Robot

![Robot](images/final_robot.jpg)

---

## CAD Model

![CAD](images/cad_render.png)

---

## RViz

![RViz](images/rviz.png)

---

## LiDAR Visualization

![LiDAR](images/lidar_scan.png)

---

## Hardware Integration

![Hardware](images/hardware.jpg)

---

# Skills Demonstrated

- Mechanical Design
- CAD Modeling
- Robotics
- ROS
- Linux
- Sensor Integration
- LiDAR
- Embedded Systems
- Robot Fabrication
- Industrial Automation
- System Integration

---

# Confidentiality Notice

This repository is intended solely as a portfolio showcasing the engineering work performed during an industrial internship.

Certain implementation details—including source code, ROS workspaces, CAD assemblies, firmware, configuration files, and other proprietary materials—are not included due to a Non-Disclosure Agreement (NDA).

Only non-confidential documentation, photographs, and high-level system descriptions are shared.

---

# License

This repository is released under the MIT License.
