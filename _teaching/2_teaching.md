---
layout: page
title: "Cognitive Robotics"
description: # with background image
img: assets/img/CR.png
importance: 2
category: Carnegie Mellon University
related_publications: false
---

# Course description
This course provides an introduction to cognitive robotics, a branch of robotics in which knowledge plays a central role in supporting action selection, planning, and execution. Cognition is essential for robots to be able to perform tasks in response to a request by a human, but without the human having to specify explicitly everything that is needed to fulfill the task. Many everyday activities fall into this category. For example, when we ask someone to fetch something for us, we don’t have to say how they are to fetch it. The goal of the course is to give students an understanding of what is involved in the design of a cognitive robot and give them the knowledge and skills to produce working implementations for simple instances of cognitive fetch and place tasks. Students will learn through a combination of classroom lectures and laboratory assignments that consolidate their understanding through practical exercises using both robot simulators and physical robots. Student progress is assessed by a series of multiple-choice tests and individual & group assignments. 

# Learning objectives
Students will be introduced to the general area of robotics. They will learn how to develop software using ROS (Robot Operating System) and they will learn the principles of robot manipulation and task-level robot programming, including the mathematical tools required to specify the position and orientation of robots and objects in the robot environment. Students will be introduced to the main topics in artificial cognitive systems, including the different paradigms of cognitive science and cognitive architectures. These components form the foundation for the remainder of the course, involving a detailed study of the CRAM (Cognitive Robot Abstract Machine) cognitive architecture, building on ROS, and exploiting functional programming in Lisp to reason about and execute under-determined tasks in everyday activities. Students will learn how to write CRAM plans in the Lisp-based CRAM plan language for the PR2 humanoid mobile robot in a simulation environment and the Lynxmotion AL5D robot manipulator, both simulated and real.

# Outcomes
After completing this course, students will be able to:

- Explain what differentiates cognitive robotics from other branches of robotics.

- Write publisher, subscriber, and services software C++ using ROS.

- Use homogeneous transformations, vectors, and quaternions to specify object pose.

- Program a robot manipulator in C++ to perform pick-and-place tasks.

- Describe the main paradigms of cognitive science.

- Identify several examples of cognitive architectures and describe how they work.

- Explain the operation of the CRAM cognitive architecture.

- Write and execute Turtlesim programs using the Lisp-based CRAM plan language.

- Write and execute robot manipulation programs using the Lisp-based CRAM plan language.

- Use the Bullet and Gazebo physics engine robot simulators to execute CRAM plans.

- Write and execute pick-and-place plans for the Lynxmotion AL5D robot manipulator.

- Content details

- Overview of cognitive robotics

- The components, structure, and operation of a robot

- Software development with ROS: packages, topics, publishers, and subscribers

- Robot manipulation and task-level robot programming

- Artificial cognitive systems

- Cognitive architectures

- The CRAM cognitive architecture

- Functional programming in Lisp

- The CRAM plan language

- Turtlesim with CRAM: plans, motion designators, process modules, and reasoning with Prolog

- Writing fetch-and-place CRAM plans for the PR2

- Writing pick-and-place CRAM plans for the Lynxmotion AL5D robot manipulator