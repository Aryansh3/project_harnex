# HARNEX – Smart Large Vehicle Maintenance System 🚛

## 📌 Overview

HARNEX is an innovative **AR/VR and IoT-based vehicle maintenance system** designed to simplify the diagnosis and repair of complex systems in large vehicles such as commercial trucks, buses, and industrial machinery.

The system helps technicians identify faults in complicated **wire harnesses and vehicle components** by combining real-time IoT data with Augmented Reality (AR) guidance. Instead of depending entirely on physical manuals and expert knowledge, technicians can receive interactive, visual, step-by-step instructions directly within their field of view.

---

## 🎯 Problem Statement

Modern large vehicles contain highly complex electrical systems, sensors, and wire harnesses. Identifying a fault manually can be difficult and time-consuming.

Traditional maintenance methods often result in:

- ⏱️ Long diagnostic and repair times
- 💰 Increased maintenance costs
- 🔧 Dependence on highly skilled technicians
- 📚 Frequent use of physical service manuals
- ❌ Higher chances of human error
- 🚛 Increased vehicle downtime

HARNEX aims to address these challenges through AR/VR visualization and IoT-based monitoring.

---

## 💡 Proposed Solution

HARNEX provides technicians with an interactive maintenance assistant that can:

1. Monitor vehicle parameters using IoT sensors.
2. Detect or identify potential system faults.
3. Locate the affected component or wire harness.
4. Display the fault location using AR.
5. Provide step-by-step repair instructions.
6. Help technicians verify the repair.
7. Reduce overall maintenance and diagnostic time.

---

## ✨ Key Features

### 🔍 Wire Harness Fault Identification
Helps technicians locate specific wires, connectors, and components within complex vehicle wiring systems.

### 🥽 Augmented Reality Guidance
AR overlays provide visual guidance directly on the physical vehicle.

### 📡 IoT-Based Monitoring
Real-time sensor data can be used to monitor vehicle components and identify abnormal conditions.

### 🛠️ Interactive Maintenance Instructions
Technicians can follow visual step-by-step instructions for inspection, troubleshooting, and repair.

### 🚛 Large Vehicle Support
Designed for applications involving:

- Commercial Trucks
- Buses
- Industrial Vehicles
- Heavy Machinery

### 📊 Real-Time Information
Important vehicle and component information can be displayed while performing maintenance.

---

## 🏗️ System Architecture

```text
          ┌──────────────────────┐
          │    Vehicle System    │
          └──────────┬───────────┘
                     │
                     ▼
          ┌──────────────────────┐
          │     IoT Sensors      │
          └──────────┬───────────┘
                     │
                     ▼
          ┌──────────────────────┐
          │   Data Processing    │
          │  & Fault Detection   │
          └──────────┬───────────┘
                     │
                     ▼
          ┌──────────────────────┐
          │   Firebase Database  │
          └──────────┬───────────┘
                     │
                     ▼
          ┌──────────────────────┐
          │    Unity AR App      │
          │       + Vuforia      │
          └──────────┬───────────┘
                     │
                     ▼
          ┌──────────────────────┐
          │ Technician Guidance  │
          └──────────────────────┘
