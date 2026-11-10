# Hi, I'm Diego Méndez Carter

**Mechatronics Engineer (UNAM)** · **M.Sc. in Robotics Candidate (Universidad de Zaragoza / EINA)**  
Working on **robotic manipulation of deformable objects (DOM)**, **GPU physics simulation**, and **robot perception**.

 **Personal Website & Portfolio:** [https://deimencart.github.io](https://deimencart.github.io)

---

### About Me

I’m a mechatronics engineer from UNAM (Mexico) currently completing my Master’s in Robotics, Graphics and Computer Vision at Universidad de Zaragoza (Spain).

My background is hands-on. I started in the workshop: designing CAD mechanisms, soldering boards, and building physical prototypes—including an autonomous beach-cleaning rover for my undergraduate thesis and mobile robotics projects at the UNAM robotics club (CROFI). I also spent 2.5 years as a Sourcing Engineer at Chamberlain Group conducting electromechanical component and failure analysis.

Today, my research focus centers on one of the most challenging frontiers in robotics: **deformable objects manipulation (cloth and textiles)**. For my Master's thesis and research internship at UNIZAR, I simulate and control Franka Emika Panda and UR10e arms in **Genesis World**, leveraging GPU-accelerated physics (PBD/XPBD) and deep reinforcement learning (Soft Actor-Critic) to execute robust manipulation tasks.

---

### Current Focus & Research

- **Deformable Object Manipulation (DOM):** Developing autonomous manipulation and folding pipelines for non-rigid materials (cloth) using Franka Emika Panda and UR10e arms.
- **Physics Simulation (Genesis World):** Simulating dynamic interactions with Position Based Dynamics (PBD) and FEM solvers on parallel GPU environments.
- **Continuous Residual Reinforcement Learning (SAC):** Combining analytical nominal Bézier trajectories with learned high-frequency Cartesian corrections.
- **Field Robotics & Outdoor Navigation (UGV Voyager 3):** ROS 2 navigation architecture on an Ackermann-steered UGV with Pixhawk (The Cube Black), 360° LiDAR scanning, and reactive navigation.
- **Robot Perception & Active Vision:** Leveraging differential surface geometry, feature matching (SuperGlue/LightGlue), and RGB-D cameras to handle occlusions and wrinkles.

---

###  Featured Projects & Repositories

-  [**SAC-Curriculum-Repro**](https://github.com/deimencart/SAC-Curriculum-Repro)  
  *Soft Actor-Critic (SAC) & Multi-Stage Curriculum Learning for Robotic Cloth Folding in Genesis World (XPBD GPU Physics).* Includes analytical nominal trajectory generators, learned Cartesian residual policy, and evaluation rollouts.
  
-  [**Voyager 3 UGV Platform**](https://github.com/deimencart/Voyager)  
  *Autonomous All-Terrain Field Rover with Ackermann Steering (EU H2020 RAWFIE platform).* Integrates The Cube Black (Pixhawk 2.1) running ArduRover, a Raspberry Pi 3B companion gateway, a 360° LightWare SF40/C LiDAR, and native ROS 2 Humble mapping.

-  [**CLASP-Repro**](https://github.com/deimencart/CLASP-Repro)  
  *Semantic Keypoint Detection and Grasp Planning for Garment Manipulation.* ResNet-50 spatial heatmap backbone predicting garment landmarks (waistbands, hems, crotch) for autonomous grasping.

-  [**SFM-Seminar-Project**](https://github.com/deimencart/SFM-Seminar-Project)  
  *Structure from Motion (SfM) & Historical Camera Localization.* Implements feature matching with SuperGlue, 8-point RANSAC, Essential matrix decomposition, linear triangulation, and bundle adjustment.

-  [**Topological-SUN-Repro**](https://github.com/deimencart/Topological-SUN-Repro)  
  *Active Vision & Topological Scene Mapping (Sun et al., 2016).* Next-Best-View (NBV) frontier exploration, volumetric occupancy grids, and topological graph extraction from RGB-D observations.

-  **Autonomous Beach Cleaner Rover (B.S. Thesis — UNAM)**  
  Designed, fabricated, and tested an autonomous mobile robot tailored for granular terrain navigation and waste collection. Covered full mechanical architecture, actuator sizing, and low-level motor control.

---

###  Tech Stack

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Robotics & Simulation** | Genesis World (XPBD/GPU), ROS / ROS 2 (Humble), Gazebo, PyBullet, MAVLink/ArduPilot |
| **Perception & AI** | PyTorch (CUDA), Gymnasium, Soft Actor-Critic (SAC), OpenCV, SuperPoint, SuperGlue, SfM |
| **Languages & Tools** | Python (Vectorized/NumPy), C++ (14/17), MATLAB, Linux / Bash, Git, LaTeX |
| **Hardware & Mechatronics**| Pixhawk (The Cube Black), Raspberry Pi, Arduino, Motor Drivers, LiDAR, Fusion 360, Eagle PCB |

---

###  Connect with Me

- **Personal Website:** [https://deimencart.github.io](https://deimencart.github.io)
- **LinkedIn:** [linkedin.com/in/diegomendezcarter](https://www.linkedin.com/in/diegomendezcarter)
- **Email:** [960616@unizar.es](mailto:960616@unizar.es)
- **GitHub:** [github.com/deimencart](https://github.com/deimencart)
