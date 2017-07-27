---
layout: page
title: Course Description
permalink: classes/2017/17-Montreal/description/index.html
parent: classes/2017/17-Montreal/index.html
---

**Title**: Autonomous Vehicles (aka. Duckietown)

**Instructor**: Liam Paull

**Email:** paulll@iro.umontreal.ca

**Website:** duckietown.org, duckietown.org/classes/2017/17-Montreal/ 

## Background and Description:

Self-driving vehicles are poised to become one of the most pervasive and impactful applications of autonomy, and have received a great deal of attention of-late. The development of self-driving vehicles provides the opportunity to address difficult challenges that are shared throughout the robotics domain and more broadly to the fields of machine learning, computer vision, and artificial intelligence. These challenges include the co-design of hardware components and algorithms, the coupled interaction between perception and control, understanding and quantifying uncertainty, the optimal allocation of finite computational resources to concurrent processes, and safe multi-agent behaviors.

This course considers problems in perception, navigation, and control, and their systems-level integration in the context of self-driving vehicles through an open-source curriculum for autonomy education that emphasizes hands-on experience. Integral to the course, students will collaborate to implement concepts covered in lecture on a low-cost autonomous vehicle with the goal of navigating a model town complete with roads, signage, traffic lights, obstacles, and citizens. The wheeled platform is equipped with a monocular camera and a  performs all processing onboard with a Raspberry Pi, and must: follow lanes while avoiding obstacles, pedestrians and other robots; localize within a global map; navigate a city; and coordinate with other robots to avoid collisions. The platform and environment are carefully designed to allow a sliding scale of difficulty in perception, inference, and control tasks, making it usable in a wide range of applications, from undergraduate-level education to research-level problems. 

**Important Note 1**: Every student will be given their **own robot** to build, personalize and use for the semester.

**Important Note 2:** The course will be taught in **concurrently and in conjunction** with classes at the University of Chicago and ETH Zurich, which provides opportunities for interaction and collaboration across institutions.

**Important Note 3:**  This is a completely **open source class**. As a result, this class will never be the same twice since we always **build** on what already exists. Students who do a great job have the potential that their work will become the new repository standard for others to try and beat in subsequent iterations.

## Outcomes:

Two of the main challenges in creating autonomous systems are:

1. **the problem of "integration"** - How to make sure that subsystems developed separately work well together. For example, how to decide on a common representation of belief? 

2. **the problem of "co-design" **- how to design the subsystems together, such that performance is maximized, while (shared) resource usage is minimized. For example: given that there is a limited power budget, how do you allocate it between perception and planning?

The **teaching objectives** that we most care about are:

* Have the students understand how methods from **heterogenous disciplines **such as control theory, machine learning, computer vision, and artificial intelligence are integrated together to create a complex autonomous system.

* Discuss the** co-design constraints **and the design trade-offs** **explicitly**.** A typical example is a trade-off like "use cheap mechanisms with sophisticated algorithms" *vs* “use reliable hardware and simple algorithms”.

* Familiarize the students with the basic practices of **reliable system development**, including test-driven and data-driven development.

* Familiarize the students with the tools and the dynamics of **software and hardware open-source development. **All homework is shared on a central Git repository. After each milestone, everybody's software is readable for everybody to re-use.  

## Syllabus:

The course will cover the theory and application of probabilistic techniques for autonomous mobile robotics with particular emphasis on their application in the context of self-driving vehicles. Topics include probabilistic state estimation and decision making for mobile robots; stochastic representations of the environment; dynamic models and sensor models for mobile robots; algorithms for mapping and localization; planning and control in the presence of uncertainty; cooperative operation of multiple mobile robots; mobile sensor networks.

Following is a list of topics discussed in the class, roughly ordered from "metal" to “systems”:

* **camera geometry; intrinsic/extrinsic calibration**

* **minimal sufficient representations for visual tasks**

* **nonlinear filtering, including robust localization** and **mapping** (localize in a given map, or create your own map);

* **level 2,3 autonomy; shared control**

* **complex perception pipelines: **(use of)** **object** detection **(reading traffic signs)** and tracking**;

* **safety** and **correctness** (navigate intersections);

* **signaling** **and** **coordination for distributed robotics** (reason about the intent of the other drivers);

## Details

**Meeting Times**: M 10:30-12:30, W 11:30am–1:30pm

**Location: TBD**

**Pre-requisites**: Permission of the instructor. Please come to the first class and fill out an application and/or email the instructor to discuss.

**Intended Enrollment**: 12 students

**Intended Degree Level**: Senior Undergraduates and Graduates

