# 6-DOF Manipulator Project Collection

Welcome to my repository for 6-Degree-of-Freedom (6-DOF) robotic arm designs. This collection serves as a centralized archive for my mechanical design projects created using SolidWorks 2026.

### Project Overview
The goal of this repository is to document the iterative design process of various 6-DOF manipulators. The designs featured here range from conceptual inspirations to high-fidelity recreations of real-world industrial robotic arms.

### Design Specifications
To keep the files lightweight and focused on geometry, these models are provided as follows:

* **CAD Software:** SolidWorks 2026.
* **Completeness:** Includes all individual .SLDPRT files and the master .SLDASM assembly file.
* **State:**
    * ✅ Components possess assigned materials.
    * ✅ Correct mating relations are applied for structural positioning.
    * ❌ No motion studies, collision detection, or stress/FEA analysis are included.

### Repository Structure
* **/*.SLDPRT**: Individual part files for each link, joint, and drive unit.
* **/*.SLDASM**: The main assembly file for the 6-DOF manipulator.
* **/Docs**: Supporting documentation, including mass property breakdowns and design references.

### Usage & Contribution
These models are intended for educational and reference purposes. You are welcome to use these CAD files for your own kinematic simulations, academic projects, or as a starting point for your own custom builds.

> **Note:** As these files are designed without collision constraints or motion studies, ensure you verify clearance and kinematics within your own simulation environment (e.g., MATLAB/Simulink or Gazebo) before attempting to implement these designs in hardware.

***
*Created by Syed M Ayan Abbas Zaidi*
