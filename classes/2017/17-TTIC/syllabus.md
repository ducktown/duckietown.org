---
layout: page
title: Syllabus
permalink: classes/2017/17-TTIC/syllabus/index.html
---


**Title**: TTIC 31240 Self-driving Vehicles: Models and Algorithms for Autonomy (a.k.a. Duckietown)

**Instructor**: Matthew Walter

**Website**: <http://duckietown.org/classes/2017/17-TTIC>


## Course Description

Self-driving vehicles are poised to become one of the most pervasive and impactful applications of autonomy, and have received a great deal of attention of-late. The development of self-driving vehicles provides the opportunity to address difficult challenges that are shared throughout the robotics domain and more broadly to the fields of machine learning, computer vision, and artificial intelligence. These challenges include the co-design of hardware components and algorithms, the coupled interaction between perception and control, the optimal allocation of finite computational resources to concurrent processes, and safe multi-agent behaviors.

This course considers problems in perception, planning, and control, and their systems-level integration in the context of self-driving vehicles through an open-source curriculum for autonomy education that emphasizes hands-on experience. Integral to the course, students will collaborate to implement concepts covered in lecture on a low-cost autonomous vehicle with the goal of navigating a model town complete with roads, signage, traffic lights, obstacles, and citizens. The wheeled platform is equipped with a monocular camera and a  performs all processing onboard with a Raspberry Pi 3, and must: follow lanes while avoiding obstacles, pedestrians and other robots; localize within a global map; navigate a city; and coordinate with other robots to avoid collisions. The platform and environment are carefully designed to allow a sliding scale of difficulty in perception, inference, and control tasks, making it usable in a wide range of applications, from undergraduate-level education to research-level problems. For example, one solitary robot can successfully wander the environment using only line detection and reactive control, while successful point-to-point navigation requires recognizing street signs. In turn, sign detections can be “simulated” either by using fiducials affixed to each sign, or it can be implemented using “real” object detection. Realizing more complex behaviors, such as vision-based decentralized multi-robot coordination, poses research-level challenges, especially considering resource constraints. In this manner, the course is well suited to facilitate undergraduate and graduate-level education in autonomy.

The course will be taught in concurrently and in conjunction with classes at the University of Montreal and ETH Zurich, which provides opportunities for interaction and collaboration across institutions.


## Learning Objectives

Two of the main challenges in creating autonomous systems are:

1. **the problem of "integration"**: How to make sure that subsystems developed separately work well together. For example, how to decide on a common representation of belief?
2. **the problem of "co-design"**: How to design the subsystems together, such that performance is maximized, while (shared) resource usage is minimized. For example: given that there is a limited power budget, how do you allocate it between perception and planning?



The teaching objectives that we most care about are:

* Have the students understand how methods from **heterogenous disciplines** such as control theory, machine learning, computer vision, and artificial intelligence are integrated together to create a complex autonomous system.
* Discuss the **co-design constraints** and the design trade-offs explicitly. A typical example is a trade-off like "use cheap mechanisms with sophisticated algorithms" vs. "use reliable hardware and simple algorithms".
* Familiarize the students with the basic practices of **reliable system development**, including test-driven and data-driven development.
* Familiarize the students with the tools and the dynamics of **software and hardware open-source development**. All homework is shared on a central Git repository. After each milestone, everybody's software is readable for everybody to re-use.


Upon completion of the course, you will have an understanding of fundamental techniques in perception, planning, and control for autonomous agents and their integration as part of a complex system. Specific topics include:

* camera geometry, intrinsic/extrinsic calibration;
* minimal sufficient representations for visual tasks;
* nonlinear filtering, including robust localization and mapping (e.g., localize in a given map, or create your own map);
* shared control and level 2,3 autonomy;
* complex perception pipelines: (use of) object detection (e.g., reading traffic signs) and tracking;
* safety and correctness (e.g., navigate intersections); and
* signaling and coordination for distributed robotics (e.g., reason about the intent of the other drivers).


## Instructor

Matthew R. Walter  
TTIC Room 429  
&#109;&#119;&#097;&#108;&#116;&#101;&#114;&#064;&#116;&#116;&#105;&#099;&#046;&#101;&#100;&#117;  
773-834-3637

**Office Hours**: TBD in TTIC 429


## Lectures

**Meeting Times**: Mondays and Wednesdays, 9:00am--10:00am

**Location**: TTIC 530

## Labs

**Meeting Times**: Mondays and Wednesdays, 10:00am--11:00am

**Location**: Robotics lab on the 4th floor


## Course Syllabus

We will post slides, problem sets, and checkoffs (labs) to the [Chicago branch diary](http://purl.org/dt/fall2017/schedule_TTIC).


## Course Grading

The class will assess your grasp of the material through a combination
of problem sets, exams, and a final project. The contribution of each
to your overall grade is as follows:

* 20%: Problem sets
* 10%: Checkoffs
* 20%: Participation
* 50%: Final project (includes report and presentation). The projects will be group-based, but we will assess the contribution of each student individually.

See below for more information on how the participation and final project components of the grade are determined.

## Course Documents

The important documents (aka "Duckuments") are listed in the [Duckiebook](http://book.duckietown.org/master/duckiebook/index.html), which simultaneously serves as a textbook, instruction guide, and source for course logistics.

All documents are distributed using the Creative Commons Attribution license. This license lets others distribute, remix, tweak, and build upon your work, even commercially, as long as they credit you for the original creation. This is the most accommodating of licenses offered. Recommended for maximum dissemination and use of licensed materials.

**If you are a student not at TTIC**: There is enough information in the materials page to make your own robot if you are not at TTIC.

**If you are an instructor not at TTIC**: We are working for you! We want this class to be reproducible everywhere else. Please get in touch with us to give us advice about how to reach that goal and to be added to a low-frequency interest list.

## Equipment

**The Duckie Box**: On the second day, each student will get The Duckie Box containing an autonomous vehicle to be assembled (we did the soldering for you) and various other supplies. See document "What’s in the box?!?".

You can take The Duckie Box with you. You have to bring The Duckie Box (and contents) back at the end of the class.

Once teams are formed, each team will get an even bigger box, with more equipment, sufficient to build a section of Duckietown.

## Teaming and Projects

Students are required to form teams. It is suggested to choose these teams based on:

* complementarity of skills;
* compatibility of schedule; and
* compatibility of character.

Each team works on the same project.


## Measuring Participation

"Participation" means "open source participation". A good member of the team improves Duckietown by:

* improving the software provided;
* documenting the software provided;
* adding functionality;
* taking logs;
* helping other members of the team; and
* running demos

The way this is graded is the following: at the end of the class, every member on the team (including students and instructors) will answer a questionnaire about the value of every other member on the team (including students and instructors). Advanced statistical techniques will be used to normalize everything and to make sure that this scheme is robust to any form of hacking. Anonymity will be preserved.

## Measuring Projects

The projects require: a demo, a presentation, and a project report.

The way these are graded is the following: at the end of the class all the senior staff (i.e., people with a PhD) will vote anonymously on every project. A mentor will not vote on the project that they are mentoring.
This number is shared about the members of the team and counts for 70% of the project grade.

The other 30% of the project grade is assigned by the mentor. It is thus possible for the members of the team to obtain a different grade for the project part.



## Policy on Late Assignments and Collaboration

Late problem sets will be penalized 10% for each day that they are
late. Those submitted more than three days beyond their due date will
receive no credit.

Each student has a budget of three days that they can use to avoid late penalties. It is up to the student to decide when/how they use these days (i.e., all at once or individually). Students must identify whether and how many days they use when they submit an assignment.

It is not acceptable to use code or solutions from outside class
(including those found online), unless the resources are specifically
suggested as part of the problem set.

You are encouraged to collaborate through study groups and to discuss
problem sets and the project in person and over Slack. However, you must
acknowledge who you worked with on each problem set. You must write up
and implement your own solutions and are not
allowed to duplicate efforts. The correct approach is to discuss
solution strategies, credit your collaborator, and write your
solutions individually. Solutions that are too similar will be
penalized.

<style>
#times thead { font-weight: bold; }
#times tbody td { padding-right: 1em; padding-top:0.2em;}
</style>


<style>
[href="#"] {color: red; }
[href="#"]:after { content: " (broken link) ";
    color: red;}
</style>
