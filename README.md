# Arctron-Arm
Modular 5DOF Robotic Arm with Plug-and-Play Plugins
# Arctron Arm V1.0

> Modular 5DOF Robotic Arm with Plug-and-Play Precision  
> Designed by **Navdeep** · Sponsered by **Highway** (A Hack Club Event) · Made to Explore!

---

## Overview

**Arctron Arm V1.0** is a sleek and developer-friendly robotic arm built for modularity and expandability. It features:

- 🔁 **5 Degrees of Freedom** (DOF) for precise motion
- 🔌 A **plugin interface** for custom plugins by the community
- 🛠️ Fully open-source design using **OnShape**, **KiCad** and more!


---

## 🦾 Core Features

| Feature                    | Description                                              |
|----------------------------|----------------------------------------------------------|
| 🎯 5DOF Motion              | Base rotation, shoulder, elbow, wrist pitch & yaw       |
| 🧩 Modular End-Effector    | Hot-swappable plugins with 3-pin power/signal port      |
| 🔋 Independent Power       | External servo power support for high torque handling   |
| 🖼️ Open CAD & Circuitry    | Designed in OnShape and KiCad – easy to remix and improve |

---

## 🧩 Available Plugins (Swappable Tools)

Each plugin is a separate smart module that can be plugged into the arm:

| Plugin                 | Description                                           |
|------------------------|-------------------------------------------------------|
| 🤖 Gripper             | Pick-and-place claw using an SG90 servo              |
| 📸 Face Tracker        | ESP32-CAM gimbal that follows your face in real time |
| 🔴 Laser Pointer       | Precision-guided laser mount with servo control       |

---

## 🛠️ Project Structure

```bash
Arctron-Arm-V1.0/
├── base-arm/            # Core 5DOF arm design
│   ├── OnShape_Design/  # CAD models
│   ├── KiCad_PCB/       # ESP32-based control board
│   ├── Firmware/        # Arduino/ESP32 control code
│   └── README.md
├── plugins/             # Modular plugin add-ons
│   ├── gripper/
│   ├── face-tracker/
│   └── laser-pointer/
└── docs/                # Logo, diagrams, specs
