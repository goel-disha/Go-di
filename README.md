# Hi there! 👋

## About Me

I am Disha Goel.

⚡ Electrical and Electronics Engineering Student | 🤖 Robotics Enthusiast | 💡 Aspiring Researcher

I am a third-year B.Tech student pursuing Electrical and Electronics Engineering at **Birla Institute of Technology, Mesra, India**.

My research interests lie at the intersection of autonomous robotics, computer vision, sensor fusion, reinforcement learning, embedded systems, control systems, and industrial automation.

I enjoy exploring how intelligent algorithms, sensing technologies, and control systems can be integrated to develop autonomous robotic systems and solve real-world engineering problems.

## My Journey

My interest in robotics developed through exploring the intersection of electronics, programming, and intelligent systems. With an academic background in Electrical and Electronics Engineering, I became particularly interested in how sensors, microcontrollers, control algorithms, and computer vision enable machines to perceive and interact with their surroundings.

I started exploring robotics through microcontroller programming and basic autonomous systems, gradually moving towards simulation-based robotics, computer vision, and machine learning.

During my internship at **LG Electronics**, in the RAC Production Engineering Department, I gained practical exposure to industrial automation and manufacturing systems. I worked with Mitsubishi PLCs, ladder programming using GX Works2, HMI systems, VFDs, servo drives, industrial communication, AGVs, and palletizer robots. This experience strengthened my interest in industrial robotics and intelligent manufacturing.

Alongside this, I have explored autonomous ground vehicle navigation, UAV simulation using PX4, reinforcement learning through robotic simulation, and machine learning-based image classification.

Through these experiences, I aim to develop a deeper understanding of autonomous systems and contribute to research in robotics, perception, sensor fusion, and intelligent control.

## Skills

### Robotics and Autonomous Systems
- ROS 2
- Gazebo
- PX4 Autopilot
- Robot Navigation
- Sensor Integration
- Computer Vision
- PID Control
- CoppeliaSim

### Programming and Software
- Python
- C++
- MATLAB
- OpenCV
- Scikit-learn
- TensorFlow
- Git and GitHub
- React
- Backend API Integration

### Industrial Automation
- PLC Programming
- Mitsubishi GX Works2
- Ladder Logic
- HMI Systems
- VFDs and Servo Drives
- Industrial Communication

### Research Interests
- Autonomous Mobile Robotics
- Sensor Fusion and Localization
- Computer Vision
- Reinforcement Learning
- SLAM and Robot Navigation
- Embedded Systems
- Industrial Robotics
- Machine Learning

---

# My Projects

## 1. Autonomous Ground Vehicle – Sensor Fusion and Autonomous Navigation

**Research Project | Autonomous Robotics**

Autonomous ground vehicles must continuously perceive their surroundings and estimate their motion to navigate safely through unfamiliar environments. However, measurements from individual sensors are often affected by noise, uncertainty, and environmental conditions.

This project focuses on exploring sensor-based navigation and obstacle avoidance for an Autonomous Ground Vehicle (AGV) using a simulation-based robotics framework.

The development environment uses **ROS 2** for robot software integration and **Gazebo** for modelling and testing the robotic system in a simulated environment.

My work and exploration involve:

- Setting up and working with an autonomous ground vehicle simulation using ROS 2 and Gazebo.
- Exploring LiDAR-based obstacle detection and environmental awareness.
- Studying IMU measurements for understanding vehicle motion and orientation.
- Investigating sensor fusion approaches to combine complementary sensor information.
- Exploring Kalman filtering for estimating the robot's state from noisy measurements.
- Studying fuzzy logic-based approaches for navigation and obstacle avoidance.
- Understanding the interaction between sensing, localization, and motion control in autonomous navigation.

The project has helped me understand the challenges involved in developing reliable autonomous navigation systems and the importance of sensor information in robotic decision-making.

**Technologies:** ROS 2, Gazebo, Python, LiDAR, IMU, Sensor Fusion, Kalman Filtering.

**Research Direction:** Robust localization, multi-sensor perception, and autonomous navigation under uncertain environmental conditions.

**Repository:** [AGV – Sensor Fusion and Navigation](https://github.com/goel-disha/AGV)

The AGV repository also includes a separate conceptual reference diagram for lateral vehicle-motion kinematics. It is labelled there as a bicycle-model reference, not as the differential-drive model used in the current AGV simulation.

![Reference diagram of lateral vehicle-motion kinematics](https://raw.githubusercontent.com/goel-disha/AGV/main/docs/references/lateral_vehicle_kinematics.webp)

**Results / Evaluation:** _To be added._

---

## 2. Autonomous UAV Navigation – ISRO ASCEND Challenge

**Autonomous Aerial Robotics | GPS-Denied Navigation**

Autonomous UAV navigation in GPS-denied environments is a challenging problem because conventional satellite-based positioning may be unavailable or unreliable. In such situations, UAVs must rely on onboard sensing, visual perception, and autonomous decision-making to perform navigation tasks.

As part of the **ISRO ASCEND challenge**, I worked on a simulation-based autonomous UAV project using **Gazebo and PX4**.

The project focuses on exploring autonomous UAV navigation and visual perception, particularly the use of visual markers for target identification and landing.

My work involved:

- Exploring UAV simulation using Gazebo and PX4 Autopilot.
- Understanding the interaction between the flight controller and the simulated UAV.
- Working with OpenCV for ArUco marker detection.
- Studying how visual markers can provide reference information for target identification and landing.
- Exploring camera and depth-sensing information for environmental awareness.
- Investigating the challenges of autonomous navigation when GPS information is unavailable.

This project provided practical exposure to aerial robotics and helped me understand the role of computer vision, onboard sensing, and flight-control systems in autonomous UAV applications.

**Technologies:** Python, OpenCV, Gazebo, PX4 Autopilot, ArUco Markers, Computer Vision.

**Research Direction:** Vision-based navigation, visual localization, and autonomous UAV landing in GPS-denied environments.

**Repository:** [UAV Simulation](https://github.com/goel-disha/px4_drone_simulation)

**Results / Evaluation:** _To be added._

---

## 3. Q-Learning-Based Robotic Line Following

**Reinforcement Learning | e-Yantra Robotics Sprint, IIT Bombay**

Traditional line-following robots generally rely on predefined control algorithms to determine their movement based on sensor readings. Reinforcement learning provides an alternative approach in which an agent learns suitable actions through repeated interaction with its environment and feedback in the form of rewards.

As part of the **e-Yantra Robotics Sprint**, I worked on developing a Q-learning-based line-following approach for a simulated mobile robot using **CoppeliaSim**.

The objective was to enable the robot to learn appropriate movement decisions based on its line sensor readings.

My work involved:

- Modelling the line-following task as a reinforcement learning problem.
- Defining the robot's state using readings from multiple line sensors.
- Designing discrete actions corresponding to different robot movements.
- Developing a reward mechanism to encourage correct line tracking and penalise undesirable behaviour.
- Exploring the Q-learning algorithm and its state-action value representation.
- Studying the influence of learning rate, discount factor, and exploration strategy on the learning process.
- Evaluating the robot's behaviour through CoppeliaSim simulation.

The project helped me understand how reinforcement learning can be applied to robotic control problems and how an agent can learn a policy through interaction with its environment.

**Achievement:** Secured **46th rank** in the e-Yantra Robotics Sprint.

**Technologies:** Python, Q-Learning, Reinforcement Learning, CoppeliaSim.

**Research Direction:** Learning-based control and reinforcement learning for autonomous robotic systems.

**Repository:** [Q-Learning Model](https://github.com/goel-disha/eyantra_rl_model)

**Results / Evaluation:** _To be added._

---

## 4. Hola The Explorer – e-Yantra Robotics Sprint

**Robotics | Computer Vision | Autonomous Navigation**

Hola The Explorer is a robotics project involving perception and autonomous navigation tasks. The project focuses on enabling robots to interpret their environment, identify relevant regions, and execute navigation tasks through programmed control algorithms.

I have been working on image-processing and multi-robot navigation tasks as part of this project.

### Task 1A – Trapezoid Detection

The objective was to detect three coloured trapezoidal regions in an arena image and generate a binary mask highlighting their outlines.

My implementation involved:

- Processing arena images using OpenCV.
- Identifying cyan, green, and orange trapezoidal regions.
- Extracting the relevant shapes from the image.
- Generating a binary image of resolution **1280 × 720** with the detected trapezoid outlines represented in white.

### Task 2A – Multi-Robot Navigation

The objective is to move three robots, r1, r2, and r3, simultaneously from their respective initial positions to their goal positions while maintaining their starting heading.

The task involves:

- Understanding robot odometry and coordinate frames.
- Converting global position information into robot-centric motion commands.
- Implementing coordinate transformations.
- Developing a Go-To-Point controller using PID-based control.
- Converting body velocities into wheel velocities.
- Coordinating the simultaneous movement of multiple robots towards their respective goals.

This project provides practical exposure to the integration of computer vision, coordinate transformations, and motion control in autonomous robotic systems.

**Technologies:** Python, ROS 2 Humble, OpenCV, Gazebo Classic, PID Control.

**Research Direction:** Robot perception, autonomous navigation, and coordinated multi-robot control.

**Repository:** [Hola The Explorer – e-Yantra](https://github.com/plsh-jade/eyrc-HolaTheExplorer)

**Results / Evaluation:** _To be added._

---

## 5. IndustrialAI – AI-Powered Industrial Monitoring Platform

**Industrial Automation | Full-Stack Development**

Industrial manufacturing systems generate large amounts of operational information through machines, sensors, controllers, and production equipment. Organising and analysing this information can help improve machine monitoring, operational visibility, and production efficiency.

**IndustrialAI** is a platform I have been developing to explore the integration of industrial monitoring systems with AI-based analytics and interactive dashboards.

My development work involves:

- Developing interactive dashboards using React and Material UI.
- Integrating frontend components with backend APIs.
- Fetching and displaying project and live-monitoring information.
- Organising industrial data into structured dashboard components.
- Exploring real-time data visualisation and machine monitoring workflows.
- Investigating how AI-based analytics can be integrated into industrial monitoring platforms.

The project has helped me explore the software side of industrial automation and understand how frontend systems, backend services, and industrial data can work together in a unified monitoring platform.

**Technologies:** React, JavaScript, Material UI, Backend APIs, Python.

**Research Direction:** AI-assisted industrial monitoring, intelligent manufacturing, and industrial digitalisation.

**Repository:** [IndustrialAI](https://github.com/goel-disha/industrialAI-)

**Results / Evaluation:** _To be added._

---

## 6. RRT Image Classification – Machine Learning and Computer Vision

**Machine Learning | Image Processing**

Image classification involves identifying patterns and extracting meaningful information from images to distinguish between different categories. The performance of a classification model depends on image quality, feature representation, preprocessing techniques, and the selected learning algorithm.

I worked on an image-classification project involving the classification of normal and abnormal images using traditional machine learning and deep learning approaches.

My work involved:

- Performing image preprocessing and region-of-interest extraction.
- Resizing images to a standard resolution of **128 × 128 pixels**.
- Extracting handcrafted features using Local Binary Patterns (LBP), Gray-Level Co-occurrence Matrix (GLCM), and Histogram of Oriented Gradients (HOG).
- Applying Principal Component Analysis (PCA) for dimensionality reduction.
- Training and evaluating SVM, Random Forest, and K-Nearest Neighbours classifiers.
- Exploring CNN-based classification using MobileNetV2.
- Comparing different feature extraction and classification approaches.

An important part of this project was investigating how different feature representations affected classification performance and analysing the limitations of traditional machine learning approaches.

**Technologies:** Python, OpenCV, Scikit-learn, TensorFlow, MobileNetV2, PCA.

**Research Direction:** Feature engineering, image classification, and deep learning-based visual recognition.

**Repository:** [Eye Image Classifier](https://github.com/goel-disha/eye_image_classifier)

**Results / Evaluation:** _To be added._

---

## 7. PID-Based Robotic Line Following

**Control Systems | Robotics Simulation**

Line-following robots use feedback mechanisms to continuously compare their current position with the desired path. PID controllers use proportional, integral, and derivative terms to minimise tracking error and improve system response.

I worked on implementing and tuning a PID-based line-following controller in CoppeliaSim.

My work involved:

- Understanding the relationship between sensor readings and tracking error.
- Implementing a feedback-based PID control loop.
- Studying the influence of proportional, integral, and derivative gains on robot movement.
- Tuning controller parameters to improve path tracking.
- Analysing oscillations and instability during curves and sharp turns.
- Evaluating robot behaviour on straight and curved paths.

The project helped me understand practical control-system challenges, particularly the trade-off between tracking accuracy, stability, and response speed.

**Technologies:** Python, CoppeliaSim, PID Control, Feedback Systems.

**Research Direction:** Controller optimisation and intelligent control for mobile robotic systems.

**Related Repositories:**
- [e-Yantra PID Model](https://github.com/goel-disha/eyantra_pid_model)
- [PID Task 2A](https://github.com/goel-disha/eyantra_pid_task2a)
- [PID Task 2B](https://github.com/goel-disha/eyantra_pid_task2b)
- [Line Controller](https://github.com/goel-disha/LineController)

![CoppeliaSim e-Yantra Task 2B simulation showing line-tracing sensor views and the track layout](https://raw.githubusercontent.com/goel-disha/eyantra_pid_task2b/main/assets/eyr_task2b_simulation.webp)

**Results / Evaluation:** _To be added._
---

# Industrial Experience

## LG Electronics – Summer Intern

**RAC Production Engineering Department | May–July 2026**

Gained practical exposure to industrial automation, electrical systems, and manufacturing processes.

My learning and activities included:

- Mitsubishi PLC programming using GX Works2.
- Ladder logic programming and HMI systems.
- VFD mechanisms and servo motor control.
- Industrial communication systems.
- Electrical panel studies.
- AGV and palletizer robot studies.
- Split AC manufacturing processes.
- PCB manufacturing processes.

This internship strengthened my understanding of industrial control systems and the practical implementation of automation technologies in manufacturing environments.

---

# Achievements and Activities

- Secured **46th rank** in the e-Yantra Robotics Sprint.
- Participated in the ISRO ASCEND autonomous UAV challenge.
- Worked on research-oriented AGV navigation and sensor integration.
- Served as **Treasurer of the Robolution Club, BIT Mesra**.
- Participated in organising technical and robotics events.

---

# Research Interests

I am particularly interested in research opportunities involving:

- Autonomous mobile robots and aerial robotics.
- Robot perception and computer vision.
- Sensor fusion and visual-inertial navigation.
- Reinforcement learning for robotics.
- Embedded intelligence and edge AI.
- SLAM and autonomous navigation.
- Industrial robotics and intelligent automation.

---

# Contact Me

📧 **Email:** [Add your email]

🔗 **LinkedIn:** [Add your LinkedIn profile]

💻 **GitHub:** [github.com/goel-disha](https://github.com/goel-disha)

---

_This portfolio is a work in progress. Project results, evaluation plots, demonstrations, and additional documentation will be added as the projects are further developed._
