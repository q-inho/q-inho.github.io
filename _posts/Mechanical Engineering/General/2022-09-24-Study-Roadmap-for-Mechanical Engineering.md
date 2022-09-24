---
title:  "Study Roadmap for Mechanical Engieering"
excerpt: "Energy, Engineering Design, Materials, Aerospace Engineering and others.."

categories:
  - mech-general
tags:
  - [Mechanical Engineering]

toc: false
toc_sticky: false
 
date: 2022-09-24
last_modified_at: 2022-09-24
---

# My Roadmap for Mechanical Engieering

<div class="mermaid"> 
      graph LR
        MATH2023[Multivariable Calculus]
        MATH2121[Linear Algebra]
        MATH2352[Differential Equations]

        ELEC2420[Basic Electronics]

        COMP2011[Programming with C++]
        
        MECH2020[Statics and Dynamics]
        MECH2020 --> MECH2040[Solid Mechanics I]
        MATH2023 & MECH2310 --> MECH2210[Fluid Mechanics]
        MECH2310[Thermodynamics]
        MECH2410[Engineering Materials I]
        MECH2520[Design and Manufacturing I]
        MECH2020 --> MECH3010[Solid Mechanics I]
        MECH2040 --> MECH3020[Solid Mechanics II]
        MECH2020 --> MECH3030[Mechanisms of Machinery]
        MECH3110[Materials for Energy Technologies]
        MECH2310 --> MECH3300[Energy Conversion]
        MECH2210 & MECH2310 --> MECH3310[Heat Transfer]
        MECH2040 & MECH2410 --> MECH3400[Introduction to Composite Materials]
        MECH2410 --> MECH3420[Energy Materials II]
        MECH3510[CAD/CAM]
        MECH2520 --> MECH3520[Design and Manufacturing II]
        MECH3610[Control Principles]
        MECH3660 & MECH3670 --> MECH3620[Aircraft Design]
        MECH3630[Electrical Technology]
        MECH2210 --> MECH3640[Aerodynamics]
        MECH2040 --> MECH3650[Aircraft Structural Analysis]
        MATH2121 & MECH3640 --> MECH3660[Gas Turbines and Jet Propulsion]
        MECH2020 --> MECH3670[Aircraft Performance and Stability]
        ELEC2420 & COMP2011 --> MECH3680[Avionics Systems]
        MECH2410 --> MACH3710[Manufacturing Processes and Systems]
        MECH2520 --> MECH3907[Mechatronics Design and Prototyping]
        MECH2410 --> MECH4010[Materials Failure in Mechanical Applications]
        MECH2020 & MECH2310 --> MECH4100[Experimental Projects in Aerospace Engineering]
        MECH3310 --> MECH4340[Air Conditioning Systems]
        MECH2310 --> MECH4350[Indoor Air Quality in Buildings]
        MECH2310 & MECH3610 --> MECH4360[Introduction to Intelligent Building Systems]
        MECH2410 --> MECH4430[Materials Characterization]
        MECH2040 --> MECH4450[Introduction to Finite Element Analysis]
        MECH2020 --> MECH4710[Introduction to Robotics]
        MECH2520 --> MECH4720[Introduction to Precision Engineering]
        MECH4740[Numerical Methods in Engineering]
        MECH2020 & MECH2040 --> MECH4750[Mechanical Vibration]
        MECH3680 --> MECH4810[Unmanned Aviation Vehicle]
        MECH3640 --> MECH4870[Computational Fluid Dynamics]
        MATH2121 & MATH2023 --> MECH4890[Introduction to Nanosatellite Engineering]
        MECH4902[Solar Energy Conversion Technology]

        subgraph Advanced Study
        MECH5010[Foundation of Solid Mechanics]
        MECH5210[Fluid Dynamics]
        MECH5230[Computational Fluid Dynamics and Heat Transfer]
        MECH5280[Transport Phenomena and Its Application in Energy Systems]
        MECH5320[Convective Heat and Mass Transfer]
        MECH5410[Advanced Mechanical Behavior of Materials]
        MECH5430[Thermodynamics and Kinetics of Materials]
        MECH5480[Nanocomposite Science and Technology]
        MECH5520[Theories and Practice of CAD/CAM/CAE]
        MECH5540[Precision Engineering]
        MECH5550[Precision Machining]
        MECH5561[Robot Manipulation]
        MECH5925[LED Packaging Technology for Solid-State Lighting]
        MECH5930[Finite Element Methods]
        MECH5931[Introduction to Mechanics of Defects in Materials]
        MECH5940[Continuum Mechanics for Crystalline Solids]
        MECH5950[Introduction to Microsystems: Technology and Devices]
        MECH5960[Flow Instability]
        MECH5961[Acoustics and Aeroacoustics]
        MECH5980[Processes in Manufacturing Systems]
        end

        MECH3020 --> MECH5010
        MECH2210 --> MECH5210
        MECH3310 --> MECH5230
        MECH5210 --> MECH5320
        MECH3420 --> MECH5410
        MECH3310 --> MECH5430
        MECH3510 --> MECH5520
        MECH4720 --> MECH5540
        MECH4720 --> MECH5550
        MECH4710 --> MECH5561
        MECH3020 --> MECH5930
        MECH2040 & MECH5010 --> MECH5931
        MECH3020 --> MECH5940
        MECH3640 --> MECH5961
        MECH3010 & MECH3520 --> MECH5980

        subgraph Aeronautical Engineering
        CIVL3310[Structural Analysis]
        CIVL4370[Computer Methods of Structural Analysis]
        COMP2012[Object-Oriented Programming and Data Structures]
        COMP2611[Computer Organization]
        COMP3111[Software Engineering]
        COMP3511[Operating Systems]
        ELEC2100[Signals and Systems]
        ELEC3200[System Modeling, Analysis and Control]
        IEDA2200[Engineering Management]
        IEDA2410[Logistics and Freight Transportation Operations]
        CENG2210[Chemical and Biological Engineering Thermodynamics]
        CENG2220[Transport Phenomena I]
        end

        MECH2020 & MECH2040 --> CIVL3310
        CIVL3310 --> CIVL4370
        COMP2011 --> COMP2012
        COMP2012 --> COMP3111
        COMP2011 --> COMP2611
        COMP2611 --> COMP3511
        ELEC2100 & MATH2121 & MATH2352 --> ELEC3200




</div>

---

# Undergraduate Mechanical Engineering
- Statics and Dynamics
- Solid Mechanics I
- Fluid Mechanics
- Thermodynamics
- Engineering Materials I
- Design and Manufacturing I
- Solid Mechanics II
- Mechanisms of Machinery
- Materials for Energy Technologies
- Energy Conversion
- Heat Transfer
- Introduction to Composite Materials
- Engineering Materials II
- CAD/CAM
- Design and Manufacturing II
- Control Principles
- Aircraft Design
- Electrical Technology
- Aerodynamics
- Aircraft Structural Analysis
- Gas Turbines and Jet Propulsion
- Aircraft Performance and Stability
- Avionics Systems
- Manufacturing Processes and Systems
- Mechatronic Design and Prototyping
- Materials Failure in Mechanical Applications
- Experiential Projects in Aerospace Engineering
- Air Conditioning Systems
- Indoor Air Quality in Buildings
- Introduction to Intelligent Building Systems
- Materials Characterization
- Introduction to Finite Element Analysis
- Introduction to Robotics
- Introduction to Precision Engineering
- Numerical Methods in Engineering
- Mechanical Vibration
- Unmanned Aviation Vehicle
- Computational Fluid Dynamics (CFD)
- Introduction to Nanosatellite Engineering
- Solar Energy Conversion Technology

# Undergraduate Chemical Engineering
- Chemical and Biological Engineering Thermodynamics
- Transport Phenomena I

# Undergraduate Civil Engineering
- Structural Analysis
- Computer Methods of Structural Analysis

# Undergraduate Computer Science
- Programming with C++
- Object-Oriented Programming and Data Structures
- Computer Organization
- Software Engineering
- Operating Systems

# Undergraduate Electrical Engineering
- Signals and Systems
- Basic Electronics
- System Modeling, Analysis and Control

# Undergraduate Mathematics
- Multivariable Calculus
- Linear Algebra
- Differential Equations

# Undergraduate Industrial Engineering and Decision Analytics
- Engineering Management
- Logistics and Freight Transportation Operations

# Postgraduate Mechanical Engineering
- Foundation of Solid Mechanics
- Fluid Dynamics
- Computational Fluid Dynamics and Heat Transfer
- Transport Phenomena and Its Application in Energy Systems
- Convective Heat and Mass Transfer
- Advanced Mechanical Behavior of Materials
- Thermodynamics and Kinetics of Materials
- Nanocomposite Science and Technology
- Theories and Practice of CAD/CAM/CAE
- Precision Engineering
- Precision Machining
- Robot Manipulation
- LED Packaging Technology for Solid-State Lighting
- Finite Element Methods
- Introduction to Mechanics of Defects in Materials
- Continuum Mechanics for Crystalline Solids
- Introduction to Microsystems: Technology and Devices
- Flow Instability
- Acoustics and Aeroacoustics
- Processes in Manufacturing Systems






# Details
## Statics and Dynamics
<details>
<summary>Study material</summary>
<div markdown="1">
- *Textbook* by Author
</div>
</details>
>Fundamental course on the analysis of the equilibrium and dynamic behavior of mechanical systems. Statics: equilibrium of particles and of rigid bodies; distributed forces; analysis of structures, including, trusses, frames, cables and beams. Dynamics: kinematics of particles; kinetics of particles, Newton's second law, energy, momenta, impact dynamics; systems of particles; kinematics of rigid bodies; kinetics of rigid bodies in two and three dimensions.



#### Reference

- https://prog-crs.hkust.edu.hk/ugcourse
- https://prog-crs.hkust.edu.hk/pgcourse
- http://stellar.mit.edu/index.html