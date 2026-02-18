---
layout: page
title: projects
permalink: /projects/
nav: true      # show in top nav bar
order: 3       # adjust to control position in navbar
---

- **Centralized Collaborative SLAM**  
  Merged an in-house visual SLAM module with an open-source centralized optimization (COVINS) for collaborative map merging with multiple RC Cars. Deploy on a Jetson Nano Super and equip the robot with a Zed mini camera. **Tools**: C++, ROS 1, OpenCV, Ceres, Eigen <a href="/assets/pdf/MEC_E_652_Final_report.pdf">
     <img src="https://www.svgrepo.com/show/424860/pdf-file-type.svg" height="15em" style="vertical-align: middle;">
  </a>

- **Fuzzified Transformer for EEG Decoding (BSc Thesis)**  
  Implemented a Neuro-fuzzy block Type 1&2 and integrated into a Transformer Neural Network for EEG SSVEP classification to enhance noise  robustness. **Tools**: Python, Scipy, Pytorch <a href="https://github.com/MarceloContreras/FuzzySSVEPFormer">
     <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" height="15em" style="vertical-align: middle;">
  </a>

- **Unified autonomous navigation pipeline for Turtlebot 3**  
  Integrated perception, localization, and planning into a single pipeline to get a unified navigation ROS node for Turtlebot 3, adaptable to changing environments. Designed a two-fold map generation that fuses a static map from ORB-SLAM 3 and the projection of RGB-D images with YOLOv5 to detect moving people. **Tools**: C++, Python, ROS 1, OpenCV, g2o, Pytorch, Gazebo <a href="https://github.com/MarceloContreras/Autonomous-Nav">
     <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" height="15em" style="vertical-align: middle;">
  </a> <a href="/assets/pdf/RAu_proyecto-compressed%20(1).pdf">
     <img src="https://www.svgrepo.com/show/424860/pdf-file-type.svg" height="15em" style="vertical-align: middle;">
  </a>
  
- **Training a Lunar Lander with Reinforcement Learning**  
  We implemented two RL algorithms, Deep-Q network and tile coding, to train the agent in the Lunar Lander environment from Gym library and compare their performance. **Tools**: Python, Tensorflow, Gym, OpenCV <a href="/assets/pdf/Robotica_Avanzada.pdf">
     <img src="https://www.svgrepo.com/show/424860/pdf-file-type.svg" height="15em" style="vertical-align: middle;">
  </a>

- **Designing a non-linear controller for an EV with brushless motors**
  We designed a cascade controller for speed control of an EV by combining a PID controller for low-level control of the brushless motor actuator with a chosen nonlinear controller. We evaluated Sliding mode controller, Feedback linearization, and Adaptive control architectures. **Tools**: MATLAB <a href="/assets/pdf/Control_no_lineal_Proyecto.pdf">
     <img src="https://www.svgrepo.com/show/424860/pdf-file-type.svg" height="15em" style="vertical-align: middle;">
  </a>
  
- **Extending Boston Dynamics Spot Arm to 7 DoF**
  We modify the Spot Arm to include an additional DoF for better dexterity in manipulation tasks. We 3D model the arm, import its mesh, and create a URDF file for loading in Gazebo. We also analyzed the direct and inverse kinematics of the arm, and designed two controllers to handle the kinematic and dynamic behaviour. **Tools**: ROS 1, C++, Python, Fusion 360, RBDL, Gazebo <a href="https://github.com/MarceloContreras/FR_proyecto">
     <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" height="15em" style="vertical-align: middle;">
  </a> <a href="/assets/pdf/FRobotica_Proyecto%20(1).pdf">
     <img src="https://www.svgrepo.com/show/424860/pdf-file-type.svg" height="15em" style="vertical-align: middle;">
  </a>

- **Automated shrimp feeding system powered by computer vision**
  Integrated tank-mounted cameras with real-time image processing to monitor food density to automate the shrimp feeding with a low-cost computer platform. I was in charge of the communication protocols (I2C and Serial) between the main system (Raspberry PI-3) and an MCU (Arduino Pro Mini), and real-time food segmentation. **Tools**: Python, I2C, Raspberry-PI, OpenCV <a href="/assets/pdf/Informe_Final___DSM.pdf">
     <img src="https://www.svgrepo.com/show/424860/pdf-file-type.svg" height="15em" style="vertical-align: middle;">
  </a>

- **Synthesis and comparison of two 8-bar linkages for exoskeletons**
  We synthesized two 8-bar linkages (Peaucellier-Lipkin) using real-world data from Tracker to model human gait. We compared several synthesis results using different optimizers (gradient descent, mesh search and stochastic solvers) **Tools**: MATLAB, Tracker Toolbox, Fusion 360. <a href="https://github.com/MarceloContreras/Proyecto-Mecanismos">
     <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" height="15em" style="vertical-align: middle;">
  </a> <a href="/assets/pdf/PROYECTO_FINAL_MECANISMOS.pdf">
     <img src="https://www.svgrepo.com/show/424860/pdf-file-type.svg" height="15em" style="vertical-align: middle;">
  </a>

  
