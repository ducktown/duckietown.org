---
layout: default
title: Google Summer of Code project ideas
permalink: ideas.html
---

This is a list of ideas for projects that contribute to Duckietown.

They are calibrated for about 12 weeks of almost-full-time (35 hours/week) work.


## Mentors for GSoC

Mentors will be professors, postdoctoral researchers, and senior Ph.D. students at the universities in which the Duckietown development took place.

The senior mentors will be:
prof. Liam Paull (University of Montréal),
Dr. Andrea Censi (ETH Zürich),
Dr. Jacopo Tani (ETH Zürich),
prof. Nick Wang (National Chiao Tung University, Taiwan),
prof. Matthew Walter (Toyota Technological Institute at Chicago, USA).

We plan to assign the students to mentors based on a combination of interest matches and time zones (so that they can easily communicate over chat).

## Description of pre-requisites and skills

We use the following tags to discuss the projects:

* <span class="SW"/>: These are projects for which it is necessary to have **good Python skills**.
* <span class="SWP"/>: These are infrastructure projects that require having **advanced software engineering background**, including knowledge of continuous integration.
* <span class="AI"/>: For these, you need to know or learn the required **AI/robotics/computer vision** techniques. At least an advanced undergraduate preparation is necessary.
* <span class="AIP"/>: These are projects that are close to the state of the art. A **graduate-level education in CS, EE, machine learning,** or similar discipline is required.
* <span class="PHY"/>: For these projects, it is essential to work with a physical Duckiebot.
* <span class="PHYP"/>: For these projects, it is essential to work with a physical Duckiebot, and it is necessary to have some space to build a Duckietown or portions thereof.
* <span class="EDU"/>: These projects are tailored to improving the educational contribution.

## Idea Group: Performance optimization

Performance optimization projects are relatively easy. You have some functionality already implemented and you need to make it more efficient. Easy!

### Improving the line detection optimization

<span class="SW"/>

<span class="SWP"/>

### Improving
(TODO)

### Developer tools

(TODO)

## Idea Group: New functionality

### Increasing robustness

(TODO)

* Make everything work on a different robot.

## Idea Group: UI

### Increasing user-friendliness

* Make it easier to interact with the robot, such as starting and stopping, and activating the various behaviors through a graphical interface.
* **Building monitoring platform for teachers**. There is a class with 20 people and 20 robots: how can the teacher know that everything is ready for the next experience?
* Scratch interface.

## Idea Group: Infrastracture

### Improving backend

The Duckietown project relies on several backend tools for cloud-based integration tests and regression tests. These tools can be greatly improved. Some of the examples are:

* Improving log database, adding automatic submissions;
* Improving the regression tests.



<style>
.SW, .SWP,
.AI, .AP, .EDU,
.PHY, .PHYP {
    display: block:
    
border:solid 1px red;
    color: white;
    font-size: smaller;
    font-variant: small-caps;
    padding-left: 2px;
    padding-right: 4px;
    padding-top: 2px;
    padding-bottom: 2px;

}
.SW { background-color: darkred; }
.SWP { background-color: red; }
.AI { background-color: darkblue; }
.AIP { background-color: blue; }
.EDU { background-color: brown; }
.PHY { background-color: darkgreen; }
.PHYP { background-color: green; }

.SW::before { content: "programming"; }
.SWP::before { content: "programming++"; }
.AI::before { content: "AI"; }
.AIP::before { content: "AI++"; }
.PHY::before { content: "physical"; }
.PHYP::before { content: "physical++"; }
.EDU::before { content: "educational"; }

</style>

<span class="SW"/>

<span class="SWP"/>

<span class="AI"/>

<span class="AIP"/>

<span class="EDU"/>

<span class="PHY"/>

<span class="PHYP"/>
