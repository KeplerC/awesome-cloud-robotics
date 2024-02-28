# Awesome Cloud Robotics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated collection of awesome platforms, papers and software related to Cloud Computing frameworks for Robotics.

> Cloud robotics is a field of robotics that attempts to invoke cloud technologies such as cloud computing, cloud storage, and other Internet technologies centered on the benefits of converged infrastructure and shared services for robotics. - [Wikipedia](https://en.wikipedia.org/wiki/Cloud_robotics)

> Cloud Robot and Automation systems can be broadly defined as any robot or automation system that relies on  data or code from a network to support its operation, i.e., where not all sensing, computation, and memory is integrated into a single standalone system. - James Kuffner

[Submit PR to help maintain the list](https://github.com/KeplerC/awesome-cloud-robotics/blob/main/contributing.md)

## Contents

- [Platforms](#platforms)
  - [Development Platforms](#development-platforms)
  - [Cloud Robotics Platforms](#cloud-robotics-platforms)
  - [Network Platforms](#network-platforms)
- [Publications](#publications)
  - [Survey](#survey)
  - [Management](#management)
  - [Network](#network)
  - [Security](#security)
  - [Serverless](#serverless)
  - [Fog Robotics](#fog-robotics)
- [Scenarios](#scenarios)
  - [Grasp Planning](#grasp-planning)
  - [HealthCare](#healthcare)
  - [Motion and Path Planning](#motion-and-path-planning)
  - [Mapping](#mapping)
- [Conferences](#conferences)
- [Related Lists](#related-lists)

## Platforms 

### Development Platforms 
- [ROS](https://www.ros.org/) - The de-facto open source framework for building general robot applications.
- [ROS2](https://github.com/ros2/ros2) - A new version of ROS with different design and architecture.
- [RoboEarth](https://roboearth.ethz.ch/) - An open source platform that allows robots to store, share, offload and collaborate.
- [ERDOS](https://github.com/erdos-project/erdos) -  A platform for developing self-driving cars.

### Cloud Robotics Platforms 
- [FogROS2](https://github.com/BerkeleyAutomation/FogROS2) - An adaptive and extensible platform for cloud and fog Robotics Using ROS 2.
- [Rapyuta](https://www.rapyuta-robotics.com/) - An open source Platform-as-a-Service (Paas) framework designed for robotics applications.
- [Google Cloud Robotics Core](https://googlecloudrobotics.github.io/core/) - An Google Cloud Platform(GCP)-based platform for building and running robotic solutions.
- [AWS IoT Greengrass](https://aws.amazon.com/greengrass/) - An AWS-based cloud platform that helps build, run, manage IoT and robotic devices.

### Network Platforms 
- [Rosbridge](http://wiki.ros.org/rosbridge_suite) - A websocket server suite that provides a JSON API to ROS functionality for non-ROS programs.
- [FogROS2 SGC](https://github.com/data-capsule/fogros2-sgc) - A P2P secure routing framework that connects disjoint ROS2 networks across heterogenous environment.
- [Husarnet VPN](https://github.com/husarnet/husarnet) - A P2P, secure network layer dedicated for ROS & ROS 2.


## Publications 
### Survey
- [A Survey of Research on Cloud Robotics and Automation](https://goldberg.berkeley.edu/pubs/T-ASE-Cloud-RA-Survey-Paper-Final-2015.pdf) - Kehoe et al. IEEE Transactions of Automation Science and Engineering 2015.
- [Robots and the return to collaborative intelligence](https://www.nature.com/articles/s42256-018-0008-x) - Ken Goldberg. Nature Machine Intelligence 2019. 
- [Cloud, Fog, and Mist Computing: Advanced Robot Applications](https://ieeexplore.ieee.org/abstract/document/8960619) - Galambos et al. IEEE Systems, Man, and Cybernetics Magazine 2022. 

### Management 
- [EMS: A Massive Computational Experiment Management System towards Data-driven Robotics](https://sites.google.com/view/project-emsr) - Lin et al. ICRA 2023.
- [FogROS: An Adaptive Framework for Automating Fog Robotics Deployment](https://arxiv.org/abs/2108.11355) - Chen et al. CASE 2021. 
- [FogROS2: An Adaptive Platform for Cloud and Fog Robotics Using ROS 2](https://arxiv.org/abs/2205.09778) - Ichnowski et al. ICRA 2023.
- [RILaaS: Robot Inference and Learning as a Service](https://ieeexplore.ieee.org/document/9103220) - Tanwani et al. IEEE RAL 2020
- [RobotCore: An Open Architecture for Hardware Acceleration in ROS 2](https://ieeexplore.ieee.org/abstract/document/9982082) - Mayoral-Vilches et al. IROS 2022.

### Network 
- [AFR: An Efficient Buffering Algorithm for Cloud Robotic Systems](https://ieeexplore.ieee.org/abstract/document/9981400) - Wang et al. IROS 2022.
- [Learning Important Regions via Attention for Video Streaming on Cloud Robotics](https://ieeexplore.ieee.org/abstract/document/9981132) - Itsumi et al. IROS 2022.

### Security 
- [Privacy-Preserving Grasp Planning](https://goldberg.berkeley.edu/pubs/jeff_case2016_privacy_v11.pdf) - Mahler et al. CASE 2016.
- [SROS2: Usable Cyber Security Tools for ROS 2](https://arxiv.org/abs/2208.02615) - Mayoral-Vilches et al. 

### Serverless 
- [Fog Robotics Algorithms for Distributed Motion Planning Using Lambda Serverless Computing](https://ieeexplore.ieee.org/abstract/document/9196651) - Ichnowski et al. ICRA 2020.
- [Serverless Architecture for Service Robot Management System](https://ieeexplore.ieee.org/abstract/document/9561824) - Nishimiya et al. ICRA 2021.
- [Serverless multi-query motion planning for fog robotics](https://goldberg.berkeley.edu/pubs/ICRA21-ichnowski-serverless-motion-planning-submitted.pdf) - Anand et al. ICRA 2021.

### Fog Robotics 
- [A Fog Robotic System for Dynamic Visual Servoing](https://ieeexplore.ieee.org/abstract/document/8793600) - Tian et al. ICRA 2019.
- [A Fog Robotics Approach to Deep Robot Learning: Application to Object Recognition and Grasp Planning in Surface Decluttering](https://ieeexplore.ieee.org/abstract/document/8793690) - ICRA 2019.
- [Low Latency Bounty Hunting and Geographically Adjacent Server Configuration for Real-Time Cloud Control](https://ieeexplore.ieee.org/document/7487738) - Lofaro et al. ICRA 2016. 
## Scenarios 

### Grasp Planning
- [A Cloud Robot System Using the Dexterity Network and Berkeley Robotics and Automation as a Service (Brass)](https://ieeexplore.ieee.org/abstract/document/7989192) - Tian et al. ICRA 2017.
- [Dex-Net as a Service (DNaaS): A Cloud-Based Robust Robot Grasp Planning System](https://ieeexplore.ieee.org/abstract/document/8560447) - Li et al. CASE 2018.
- [Cloud-based robot grasping with the google object recognition engine](https://ieeexplore.ieee.org/abstract/document/6631180) - Kehoe et al. ICRA 2013.


### HealthCare
- [Cloud services for robotic nurses? Assessing legal and ethical issues in the use of cloud services for healthcare robots](https://ieeexplore.ieee.org/abstract/document/8593591) - Fosch-Villaronga et al. IROS 2018.

### Motion and Path Planning 
- [Path planning as a service PPaaS: Cloud-based robotic path planning](https://ieeexplore.ieee.org/document/7090603) - Lam et al. ROBIO 2014. 
- [Cloud Automation: Precomputing Roadmaps for Flexible Manipulation](https://ieeexplore.ieee.org/document/7124626) - Bekris et al. IEEE Robotics & Automation Magazine 2015. 

### Mapping 
- [Cloud-Based Collaborative 3D Mapping in Real-Time With Low-Cost Robots](https://ieeexplore.ieee.org/document/7057681) - Mohanarajah et al. IEEE Trans. Automation Science and Engineering 2015. 

## Conferences 
- [IEEE International Conference on Robotics and Automation (ICRA)](http://www.ieee-ras.org/conferences-workshops/fully-sponsored/icra)
- [IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)](http://www.iros.org/)
- [Robotics: Science and Systems Conference (RSS)](http://www.roboticsconference.org/)
- [IEEE International Conference on Automation Science and Engineering (CASE)](https://www.ieee-ras.org/conferences-workshops/fully-sponsored/case)
- [ROSCon](https://roscon.ros.org/) - A ROS developers conference.


## Related Lists 
- [Awesome Robotics](https://github.com/kiloreux/awesome-robotics) - By kiloreux.
- [Awesome Robotics](https://github.com/ahundt/awesome-robotics) - By ahundt.
- [Awesome Robotics Libraries](https://github.com/jslee02/awesome-robotics-libraries)
- [Awesome ROS2](https://github.com/fkromer/awesome-ros2)
