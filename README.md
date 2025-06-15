# 🤖 LeRobotHackathon – Gripper Module

## 📘 Overview

This repository contains the design and documentation of a **custom parallel gripper** developed for the LeRobot Hackathon. The gripper is designed for integration with robotic arms such as the SO-100 and is optimized for tasks requiring precision and adaptability.

---

## 🖼️ Visual Renders

### 💡 Assembly Views

![Gripper View A - Left](./media/Gripper_a_v1_L.png)  
*Gripper – Left-side view (assembled)*

![Gripper View A - Orthogonal](./media/Gripper_a_v1_O.png)  
*Gripper – Orthogonal view (assembled)*

![Gripper View B - Orthogonal](./media/Gripper_b_v1_O.png)  
*Gripper – Orthogonal view (mechanical constraints visible)*

---

## 🛠️ Gripper Description

### 🔧 General Structure

- Composed of **two synchronized jaws** that open and close in parallel.
- Built with **3D printed or machined parts**, designed with triangular geometries to reduce weight and preserve strength.
- Includes a **motor mount** at the rear for housing the actuator (e.g., NEMA motor).

### ⚙️ Motion System

- Incorporates **two horizontal guide rods** (top and bottom) for maintaining parallelism during motion.
- Movement is transmitted through a **linkage system** connecting the jaws to a central mechanism.
- The driving force is likely supplied via a **worm gear, cam, or eccentric rotary system**.

### 🔩 Assembly and Mounting

- CAD design includes **degrees of freedom constraints**, represented with standard DoF symbols (used in Onshape/SolidWorks).
- A **rigid rear plate** ensures proper alignment and solid structural support during operation.

### 📦 Potential Applications

- Handling **small to medium-sized objects** in structured environments.
- Integration with **robotic platforms** such as the SO-100 for education, research, or prototyping.
- Potential use in **medical tasks** (e.g., robotic auscultation) when adapted to hold specialized instruments like stethoscopes.

---

## 🧰 Bill of Materials (BoM)


| Component              | Description                                            | Reference Image                                   |
|------------------------|--------------------------------------------------------|--------------------------------------------------|
| **3D Printing Filament** | PLA or ABS (chosen based on strength and availability) |                                                  |
| **Servo Motor**        | Feetech STS3215                                       | ![Servo Motor](./media/shopping.webp)            |
| **Sleeve Bearings**    | Inner Ø 3 mm, Outer Ø 5 mm                             | ![Sleeve Bearing](./media/Sleeve.jpg)            |
| **Steel Shafts**       | Diameter: 3 mm                                        | ![Steel Shaft](./media/61RdWxkbsAL.jpg)          |
| **Screws**             | M3 metric screws (3 mm diameter)                      |                                                  |


---

## Video

[![Demo del Gripper](media/Gripper_a_v1_O.png)](https://www.youtube.com/watch?v=_b54mGpSRdc)


